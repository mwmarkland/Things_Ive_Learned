# Submitting from the command-line.

Running outside of the spark-shell, you have to build jar's containing everything you need to run your app so that it can be distributed across the cluster. Reminds me of static linking on HPCs.

Here's an example submit (to a local instance) based on the example in the Spark docs.

~~~
spark-submit --class "SimpleApp" target/scala-2.10/simple-project_2.10-1.0.jar
~~~

The jar was built using `sbt`.

# Why does `reduceByKey((a,b) => a + b)` work?

At first glance this didn't make sense to me. If `a` and `b` are
(Key,Value) pairs, then there would have to be an overloaded addition
operator that worked. However, digging in the Spark source showed me
the error of my understanding. The signature of reduceByKey is really
`reduceByKey[RDD(K,V)](func: (V, V) => V) : RDD[(K,V)]` so the
function, in this case `+` only needs to be defined on the value
type. The documentation does call out that func has to be `(V,V) => V`, but I missed that the first time. `reduceByKey` actually gets turned into a call to `combineByKeyWithClassTag` which looks like an interesting function. The code is in
`core/src/main/scala/org/apache/spark/rdd/PairRddFunctions.scala`

# How do I avoid exceptions when I try to write to an already existing path.

This code will delete the directory before you use it.

~~~
val hadoopConf = new org.apache.hadoop.conf.Configuration()
val hdfs = org.apache.hadoop.fs.FileSystem.get(new java.net.URI("hdfs://localhost:9000"), hadoopConf)
try { hdfs.delete(new org.apache.hadoop.fs.Path(filepath), true) } catch { case _ : Throwable => { } }
~~~
