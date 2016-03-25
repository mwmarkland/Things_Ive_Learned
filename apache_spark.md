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

# Using eclipse for Scala/Spark development.

The idea was to be able to build on a laptop and move JAR file to a different computer. For the Mac, here is what I did.
1. Installed Eclipse (I used the parallel tools one) using the Eclipse installer.
2. Installed ScalaIDE from the Marketplace.
3. Installed sbt via MacPorts.
4. Installed `sbteclipse` plugin for sbt in `.sbt\` directory.
5. Create a src dir for the project.
6. Ran `sbt eclipse` to create Eclipse project files.

The instructions next are you import the project into Eclipse using a generic import. This gets you editing and stuff. You have to do manual refresh to keep things in sync. Builds are done manually outside of Eclipse.

This seemed to succesfully work. Didn't try anything too complicated code-wise. However, it seems sort of heavy with Eclipse not being able to do all of the heavy lifting.

# Dependencies in sbt.
sbt searchs out in the Maven and other "repositories" for dependencies. When I tried my first GraphX program, I couldn't get it to resolve the GraphX stuff. So I did a search on Maven2 to find the repository and then followed org.apache.spark down the hierarchy. There I saw a bunch of files labled spark-core-XXXX which seemed to be the idea behind the spark-core library dependency. So I looked for graphx and found spark-graphx. Adding a library dependency entry in my build.sbt file got me going.
