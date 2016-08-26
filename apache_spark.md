# Maven setup of scala project

## General project:
Using [scala-archetype-simple](https://github.com/davidB/scala-archetype-simple)

~~~
mvn archetype:generate -B -DarchetypeGroupId=net.alchim31.maven -DarchetypeArtifactId=scala-archetype-simple -DarchetypeVersion=1.5 -DgroupId=edu.mayo.analytics -DartifactId=PageRank -Dversion=0.1 -Dpackage=edu.mayo.analytics
~~~

## Spark Project
[Spark In Action Book](https://github.com/spark-in-action/scala-archetype-sparkinaction)

~~~
#### From the terminal or a shell script (batch mode): Don't forget to change the parameter values in the last line.

mvn archetype:generate -B \
-DarchetypeCatalog=https://github.com/spark-in-action/scala-archetype-sparkinaction/raw/master/archetype-catalog.xml \
-DarchetypeRepository=https://github.com/spark-in-action/scala-archetype-sparkinaction/raw/master \
-DarchetypeGroupId=org.sparkinaction \
-DarchetypeArtifactId=scala-archetype-sparkinaction \
-DarchetypeVersion=0.13 \
-DgroupId=com.sia -DartifactId=chapter03App -Dversion=0.1-SNAPSHOT -Dpackage=com.sia
~~~

# Useful APIs
SparkConf -- `getAll()` returns `Array[(String,String)]` shows configuration values.

# Spark SQL example.

Hacking on the spark application history JSON output.
~~~
val appHistory = sqlContext.jsonFile("file:///users/markland/linux_box/a53a2d80-3405-4872-8aaf-d24d160f3a41-0138",250)
appHistory.registerTempTable("appHistory")
val taskInfo = sqlContext.sql("SELECT `Task Info` FROM appHistory")
taskInfo: org.apache.spark.sql.DataFrame = [Task Info: struct<Accumulables:array<string>,Attempt:bigint,Executor ID:string,Failed:boolean,Finish Time:bigint,Getting Result Time:bigint,Host:string,Index:bigint,Launch Time:bigint,Locality:string,Speculative:boolean,Task ID:bigint>]
val stuff = sqlContext.sql("SELECT `Task Info`.`Executor ID` FROM taskI")
val stuff = sqlContext.sql("SELECT `Task Info`.`Executor ID`,`Task Info`.`Task ID` FROM taskI")
[08c79742-4fa1-476b-bdde-b994f9d9ebee-S27,33323]

scala> stringRDD2.map(x => (x(0),x(1)))
res43: org.apache.spark.rdd.RDD[(String, String)] = MapPartitionsRDD[64] at map at <console>:41

scala> res43.take(2)
res44: Array[(String, String)] = Array((08c79742-4fa1-476b-bdde-b994f9d9ebee-S18,0), (08c79742-4fa1-476b-bdde-b994f9d9ebee-S18,1))

scala> res43.groupByKey
res45: org.apache.spark.rdd.RDD[(String, Iterable[String])] = ShuffledRDD[65] at groupByKey at <console>:43

scala> res45.take(2)
res46: Array[(String, Iterable[String])] = Array((08c79742-4fa1-476b-bdde-b994f9d9ebee-S30,CompactBuffer(32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 35, 55, 47, 60, 45, 44, 53, 40, 49, 54, 63, 46, 61, 48, 62, 43, 51, 59, 57, 52, 50, 56, 41, 58, 42, 39, 37, 32, 33, 38, 36, 34, 110, 114, 118, 122, 126, 130, 134, 138, 142, 146, 150, 154, 158, 162, 166, 170, 174, 178, 182, 186, 190, 194, 198, 202, 206, 210, 214, 218, 222, 226, 230, 234, 244, 234, 251, 218, 252, 226, 255, 222, 259, 230, 262, 244, 283, 190, 288, 194, 291, 162, 293, 182, 296, 255, 301, 252, 305, 118, 306, 130, 308, 142, 309, 198, 311, 206, 315, 158, 317, 251, 319, 202, 323, 186, 262, 259, 174, 146, 126, 178, 170, 166, 150, 154, 283, 288, 138, 2...

scala> res45.map(x => (x._1,x._2.count(x => true)))
res55: org.apache.spark.rdd.RDD[(String, Int)] = MapPartitionsRDD[67] at map at <console>:45

scala> res55.take(2)
res56: Array[(String, Int)] = Array((08c79742-4fa1-476b-bdde-b994f9d9ebee-S30,16680), (08c79742-4fa1-476b-bdde-b994f9d9ebee-S5,16604))

scala> res55.collect.foreach(println)
(08c79742-4fa1-476b-bdde-b994f9d9ebee-S30,16680)
(08c79742-4fa1-476b-bdde-b994f9d9ebee-S5,16604)
(08c79742-4fa1-476b-bdde-b994f9d9ebee-S18,16688)
(08c79742-4fa1-476b-bdde-b994f9d9ebee-S27,16736)
~~~

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
[Mastering Apache Spark GitBook](https://www.gitbook.com/book/jaceklaskowski/mastering-apache-spark/details)

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

# Resource Managers
## YARN
Trying to understand YARN better. These notes have been gleened from a number of sources including.

Books:

- _Apache Hadoop YARN:  Moving beyond MapReduce and Batch Processing with Apache Hadoop 2_ 

Web:

- [Apache Spark Resource Management and YARN App Models](http://blog.cloudera.com/blog/2014/05/apache-spark-resource-management-and-yarn-app-models/)

# Pieces of YARN

Three main components

- ResourceManager (RM):  Arbitrator of all cluster resources.
- NodeManager (NM):  One per node. Manages users' jobs and workflow on a given node.
- Application Master:  User job life-cycle manager. Where the application resides. The first container started for the application. Requests resources from the *RM* and when allocated tells *NMs* to start containers on its behalf.

Also have

- Containers:  A logical bundle of resources (memory, cores, etc) bound to a particular cluster node.

## ResourceManager

A standalone daemon on a dedicated machine.
Central authority for allocating resources to the competing applications in the cluster.

Central/global view of all cluster resources.

Dynamically allocates resource containers to applications to run on particular nodes.

Communicates with NodeManagers.

## NodeManager

Daemon running on each node which enforces and tracks containers assigned to a node. Note that there could be multiple containers assigned to a node.

Heartbeat communications with the ResourceManager.

Local monitoring of resource availability, fault reporting, and container life-cycle management (starting and killing jobs).



## Containers

A container is a collection of physical resources (RAM, CPU cores, disks) on a single node. There can be multiple containers or a single large container on a given node. Every node in the system is considered to be composed of multiple containers of (minimum memory size and CPU). Application Master can request any container so as to occupy a multiple of the minimum size.

Supervised by the NodeManager.
Scheduled by the ResourceManager.

Acquisition and release of containers can be dynamic.

Described by a container launch context (CLC). Includes env vars, dependency information, security tokens, payloads for NodeManager services, and the command to start the process.

## ApplicationMaster

Is a container (sometimes called container 0).

Applications start as the ApplicationMaster which then negotiates with the ResourceManager for more containers.

Works with the NodeManagers to execute and monitor the running tasks.
# Spark Application Architecture

A Spark application corresponds to an instance of the `SparkContext` class. An application will have processes called **Executors** running on the cluster on its behalf even when there are no jobs running.

Many tasks may run concurrently in a single process and processes live for the lifetime of the Spark application even when no jobs are running.

Tasks can start up quickly and process in-memory data. Requires coarser-grained resource management. The number of executors for for an app is fixed and each one has a fixed allotment of resources.

# Spark Cluster Management

Spark supports pluggable cluster management. The cluster manager is responsible for starting executor processes.

Spark supports the following managers, each having two components. The master service decides which applications get to run executor processes, as well as where and when they get to run. The slave service running on every node starts the executor processes and may monitor their liveliness and resource consumption.


|Cluster Manager| Master Service| Slave Service|
|YARN|YARN Resource Manager| YARN NodeManager |
|Mesos|Mesos Master | Mesos slave |
|Standalone| Standalone Master | Standalone Slave |

## Spark and YARN

Benefits of security, configurable number of executors, ability to
play well with others, and benefits of the YARN schedulers for
categorizing, isolation, prioritization.

Each Spark executor runs as a YARN container. Multiple Spark tasks may
then run in this container. Note that you can have multiple YARN
containers on a given physical node, so you could have multiple Spark
Executors on a given physical node.

The number of Spark executors maps to the number of YARN containers
one-to-one with the number or cores and executor memory then defining
the resources for the container. **It is better to have more
containers than more CPUS/container.** Best to keep one core per
container.

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

## Chicken Scratches 

RDDs are paritioned. An action on an RDD becomes a *job* which is
transformed into a set of *stages*. A stage is a physical unit of
execution; a step in a physical execution plan. It is also a set of
parallel *task*s one per partition within the RDD. Stage boundaries
are marked by shuffle dependencies which are essentially like
barriers. Executors run tasks.

From [Mammoth Data](http://www.mammothdata.com) here are 9 tips for best practices with Spark (paraphrased)
1. Scala will get new features first.
2. If using Java, use Java 8 or later.
3. Spark can be unit-tested and integration-tested, and code should be reused between streaming and batch jobs wherever possible.
4. Minimize shuffling (i.e. don't use groupByKey), and speed serialization.
5. Use connection pools instead of dedicated connections when connecting to external data sources (don't want RDD to create many connections for each partition/element).
6. Checkpoint when running streaming apps.
7. G1 GC can be more performant on large datasets. Tuning will be required to get best performance.
8. Use Dataframes rather than RDDs (this is even more true in 2.0).
9. Spark Streaming is microbatch, not streaming.

Spark performance is highly dependent on finding the right number of tasks (i.e. partitioning of data) and correct ammount of memory per executor. Changing the number of executors while keeping the memory allocation per executor the same can change the shuffle pattern for the data and kill performance.

`cache()` to avoid recomputation of RDDs.
