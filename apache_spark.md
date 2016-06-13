
# Gotchas(?)

I think that match exceptions may be silently caught and ignored.

Avoid **groupByKey**. `aggregateByKey`, `reduceByKey`, `combineByKey` are better.

~~~
val initialValue = (0.0,0.0,0.0)
def seqOp(u: (Double, Double, Double), v: Double) = (u._1 + v, u._2 + v*v, u._3 + 1)
def combOp(u1: (Double, Double, Double),  u2: (Double, Double, Double)) = (u1._1 + u2._1, u1._2 + u2._2, u1._3 + u2._3)
rdd.aggregateByKey(initialValue)(seqOp, combOp)
~~~


# Getting one output file.

`coalesce` is your friend.

# Documentation

I sometimes find it hard to find documentation for stuff. What I've
discovered is that not all API stuff is at the "top-level". For
example, in GraphX many items are in the `GraphOps` *class* which is
part of `org.apache.spark.graphx` but you won't find the API members
by doing a search.

There are also items that are only in *objects* which are another
piece of the documentation puzzle. My Scala notes discuss this also.

# Quieting it down.

In the shell:
`sc.setLogLevel(“WARN”)`

In an app:
~~~
val log = LogManager.getRootLogger
log.setLevel(Level.WARN)
~~~

although I'd think the sc function would work also.

# Debugging

- [How can I debug Spark application locally](http://stackoverflow.com/questions/30403685/how-can-i-debug-spark-application-locally)

# Hints on keeping ordering.

In general Spark won't retain the order of lines in a file when you
generate output, but you can create a unique key to add to your input
so that there is a way to recreate the ordering at the end.

[Which operations preserve rdd order?](http://stackoverflow.com/questions/29284095/which-operations-preserve-rdd-order?lq=1)

# Good websites

http://spark-packages.org/
[RDD API Examples](http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html)

[How-to: Tune Your Apache Spark Jobs Part One](http://blog.cloudera.com/blog/2015/03/how-to-tune-your-apache-spark-jobs-part-1/)

# Controlling driver and executor memory limits

http://stackoverflow.com/questions/27181737/how-to-deal-with-executor-memory-and-driver-memory-in-spark

# Submitting from the command-line.

Running outside of the spark-shell, you have to build jar's containing everything you need to run your app so that it can be distributed across the cluster. Reminds me of static linking on HPCs.

Here's an example submit (to a local instance) based on the example in the Spark docs.

~~~
spark-submit --class "SimpleApp" target/scala-2.10/simple-project_2.10-1.0.jar
~~~

When you need additional packages

~~~
spark-submit --packages com.databricks:spark-csv_2.10:1.4.0 --class mayo.athena.ga_demo.sparksql.SQLExample target/scala-2.10/sparksql-example_2.10-0.0.1.jar
~~~

The jar was built using `sbt`.

# Why does `reduceByKey((a,b) => a + b)` work?

At first glance this didn't make sense to me. If `a` and `b` are
(Key,Value) pairs, then there would have to be an overloaded addition
operator that worked. However, digging in the Spark source showed me
the error of my understanding. The signature of reduceByKey is really
`reduceByKey[RDD(K,V)](func: (V, V) => V) : RDD[(K,V)]` so the
function, in this case `+` only needs to be defined on the value
type. The documentation does call out that func has to be `(V,V) =>
V`, but I missed that the first time. `reduceByKey` actually gets
turned into a call to `combineByKeyWithClassTag` which looks like an
interesting function. The code is in
`core/src/main/scala/org/apache/spark/rdd/PairRddFunctions.scala`

# How do I avoid exceptions when I try to write to an already existing path.

This code will delete the directory before you use it.

~~~
val hadoopConf = new org.apache.hadoop.conf.Configuration()
val hdfs = org.apache.hadoop.fs.FileSystem.get(new java.net.URI("hdfs://localhost:9000"), hadoopConf)
try { hdfs.delete(new org.apache.hadoop.fs.Path(filepath), true) } catch { case _ : Throwable => { } }
~~~

# Using eclipse for Scala/Spark development.

The idea was to be able to build on a laptop and move JAR file to a different computer. For the Mac, here is what I did.
1. Installed Eclipse (I used the parallel tools one) using the Eclipse installer.
2. Installed ScalaIDE from the Marketplace.
3. Installed sbt via MacPorts.
4. Installed `sbteclipse` plugin for sbt in `.sbt\` directory.
5. Create a src dir for the project.
6. Ran `sbt eclipse` to create Eclipse project files.

The instructions next are you import the project into Eclipse using a
generic import. This gets you editing and stuff. You have to do manual
refresh to keep things in sync. Builds are done manually outside of
Eclipse.

This seemed to succesfully work. Didn't try anything too complicated
code-wise. However, it seems sort of heavy with Eclipse not being able
to do all of the heavy lifting.

# Dependencies in sbt.

sbt searchs out in the Maven and other "repositories" for
dependencies. When I tried my first GraphX program, I couldn't get it
to resolve the GraphX stuff. So I did a search on Maven2 to find the
repository and then followed org.apache.spark down the
hierarchy. There I saw a bunch of files labled spark-core-XXXX which
seemed to be the idea behind the spark-core library dependency. So I
looked for graphx and found spark-graphx. Adding a library dependency
entry in my build.sbt file got me going.


# Performance

After reading through notes from Arvind and looking at performance of
various Spark runs, it is clear that you get better performance from
Spark the more you look at the instance of your application and data
and tune it. From Arvind's reports, it is clear that this tuning is
key; for example he got the Scale 29 PageRank test running on 41 nodes
in about an hour, but when he took the same invocation ran it on 32
nodes and it ran for 16+ hours and didn't finish. When he changed the
memory allocation, things went better. Arvind has also see cases where
the work does not spread evenly across executors (either in the number
of tasks or the amount of memory needed for operations) in which case
you have to figure out how to reprocess/repartition the work to get
better balance. What Arvind has is access to the engineers on the
system who more closely know how Spark works.

So, the place to start is the Executors tab in the Spark History for
the job. Within Mesos (i.e. Athena) there will be one executor per
worker node (and with the coarse mode we are using, one worker node =
one node). You can see how many tasks were assigned to each
executor. If these numbers are not balanced, there may be an issue in
how the data is partitioned (data partitions in Spark map to tasks at
execution time). The amount of shuffled data needs to be examined
also. Shuffling data is essentially lost time/work in one sense.

So, watching the memory allocation per executor, using cache() to
avoid recomputation of values, watching the memory split on the
executors, watching the partitions (i.e. tasks) and how they spread
over the executors, remembering which Spark operations cause
shuffles. All of these things are very important.



## Sites

[Shuffling and repartitioning of RDDs in Apache Spark](https://blog.knoldus.com/2015/06/19/shufflling-and-repartitioning-of-rdds-in-apache-spark/)

[Repartition strategy after reading text file.](http://stackoverflow.com/questions/28127119/spark-repartition-strategy-after-reading-text-file)

[Apache Spark Resource Management and YARN App Models](http://stackoverflow.com/questions/28127119/spark-repartition-strategy-after-reading-text-file)

## Locality

[Meaning of locality](http://stackoverflow.com/questions/26994025/whats-the-meaning-of-locality-levelon-spark-cluster)
