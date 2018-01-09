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

## Spark Performance Discussion with Arvind

Conversation opened. 1 read message.

Skip to content
Using Gmail with screen readers
Click here to enable desktop notifications for Gmail.   Learn more  Hide
 
 
More 
39 of 40
 
FW: Update.... was RE: Getting the Scale 29 graph running in Spark/GraphX.
Inbox
	x
Markland, Matthew W. (Matt), M.S. Markland.Matthew@mayo.edu via srs.acm.org 
	
6/7/16
	
to marklandm

 

 

From: Arvind Chhabra [mailto:achhabra@cray.com]
Sent: Tuesday, June 07, 2016 9:46 AM
To: Markland, Matthew W. (Matt), M.S.
Cc: Techentin, Robert W.; Poole, Ruth J.; Jim Maltby
Subject: Re: Update.... was RE: Getting the Scale 29 graph running in Spark/GraphX.

 

Hi Matt,

 

My "guess" is that if the partitions are not too big i.e. if all partitions on a node can fit in the memory, it is best to leave 2-3 cores free for the OS etc. and have 1 partition for each of the remaining cores. Leaving a few cores per node free for OS etc. is important else the performance gets worse. Configuring the number of partitions is the easiest way I know to make sure that a few cores per node will be left for OS etc.

 

There is a lot of guesswork involved because you never know how much memory is going to be used. For example the scale 29 graph file of 166 GB used about 1 TB of memory for RDDs across the 41 nodes. I had allocated about 4.1 TB of memory across 41 nodes (executor-memory was 100G), out of which about 

2 TB (50%) is available for RDDs and the job used only 1 TB. That means I could have used a lower number for executor-memory and left a larger chunk for OS file cache. When I run on 32 nodes, I might lower the executor memory to 80 GB. That will give me about 1.28 TB  (80 * 0.5 * 32) of memory for RDDs.

 

If the data size is much larger, it would be ideal to make sure that the number of partitions is a multiple of the number of cores (leaving 2-3 cores free per node). I am not sure how I would make sure that a few cores are left free for the OS in that case. For example if I had a 10 node cluster with 32 cores on each node and I split the RDD into 600 partitions, spark will probably run 320 tasks first and then run 280 tasks. Using all 320 cores will probably slow things down. I will ask around to see how this situation can be avoided.

 

In extreme situations, if the number of partitions is even off by 1, it can double the time taken to do the job. Let us say you have a 10 node cluster with 32 cores and create 321 partitions. Spark will process 320 partitions in parallel and then process the last partition. When the last partition is being processed, 319 cores will be idle.

 

I use block size just to avoid repartitioning after the initial load. If the number of partitions when reading the data from Lustre is the same as the number of partitions when I am manipulating the data, I avoid repartitioning.

 

- Arvind

Ph: +1-(650) 619-8006

 

From: "Markland, Matthew W. (Matt), M.S." <Markland.Matthew@mayo.edu>
Date: Tuesday, June 7, 2016 at 9:48 AM
To: Arvind Chhabra <achhabra@cray.com>
Cc: "Techentin, Robert W." <techentin.robert@mayo.edu>, "Poole, Ruth J." <Poole.Ruth@mayo.edu>, Jim Maltby <jmaltby@cray.com>
Subject: RE: Update.... was RE: Getting the Scale 29 graph running in Spark/GraphX.

 

Arvind:

 

Awesome!

 

Now for the questions…. ;-)

 

Is it typical to want to create at least one partition per executor core. Appears to be the case and makes sense, but want confirmation.

How key is the block size to the performance? That’s something I haven’t thought much about so far.

 

Thanks!

 

Matt

 

From: Arvind Chhabra [mailto:achhabra@cray.com]
Sent: Tuesday, June 07, 2016 7:49 AM
To: Markland, Matthew W. (Matt), M.S.
Cc: Techentin, Robert W.; Poole, Ruth J.; Jim Maltby
Subject: Re: Update.... was RE: Getting the Scale 29 graph running in Spark/GraphX.

 

Hi Matt,

 

After experimenting a little, I am able to get reasonable performance for Page Rank on the Scale 29 graph that Bob had uploaded to Cray's FTP server. The job took about an hour using all 41 compute nodes. I will try running it tonight on 32 nodes. I have attached the script I used. Here are the parameters I used for the script:

 

=============================================

./page_rank.sh 41 file:///mnt/lustre/achhabra/graph_perf/rmat_scale29/mat29_graph.txt out/rmat29_pr

Num Cores = 1312

Num Partitions = 1189

File Name = /mnt/lustre/achhabra/graph_perf/rmat_scale29/mat29_graph.txt

File Size = 166237782813

Block Size = 139813105

=============================================

 

Using 29 partitions for every 32 cores leaves 3 cores for the OS, Data Node etc. on each node.

 

- Arvind

Ph: +1-(650) 619-8006

 

From: "Markland, Matthew W. (Matt), M.S." <Markland.Matthew@mayo.edu>
Date: Monday, May 23, 2016 at 11:40 AM
To: Arvind Chhabra <achhabra@cray.com>
Cc: "Techentin, Robert W." <techentin.robert@mayo.edu>, "Poole, Ruth J." <Poole.Ruth@mayo.edu>
Subject: Update.... was RE: Getting the Scale 29 graph running in Spark/GraphX.

 

Arvind:

 

Just an FYI… I modified the source to set the edge partitions to be 1024 and ran the test on 32 nodes; the test took 44 hours to complete. So I’m thinking there must be locality issues. The history server can’t load the logs from the run into the web interface so I’ll see if I can dig around a little bit.

 

At the moment, though, I’m going to be summarizing and writing more than running tests, just FYI.

 

Thanks!

 

Matt

 

From: Arvind Chhabra [mailto:achhabra@cray.com]
Sent: Friday, May 20, 2016 11:59 AM
To: Markland, Matthew W. (Matt), M.S.
Cc: Techentin, Robert W.; Poole, Ruth J.
Subject: RE: Getting the Scale 29 graph running in Spark/GraphX.

 

I am still not able to work on the laptop but I am making some progress. Hope I can start working a few hours next week.

 

Can you upload the data file to box.com or Cray FTP site and I will try to run the job on a machine here. I was wondering if the number of partitions should be at least the same as the number of cores. Looking at Spark history data can also help determine the bottlenecks.

 

- Arvind

Ph : 650-619-8006

Sent from phone



-------- Original message --------
From: "Markland, Matthew W. (Matt), M.S." <Markland.Matthew@mayo.edu>
Date: 5/20/2016 11:15 AM (GMT-05:00)
To: Arvind Chhabra <achhabra@cray.com>
Cc: "Techentin, Robert W." <techentin.robert@mayo.edu>, "Poole, Ruth J." <Poole.Ruth@mayo.edu>
Subject: Getting the Scale 29 graph running in Spark/GraphX.

Arvind:

 

I hope that you are feeling better. Bob Techentin noted that you offered to take a look at my work to get the Scale 29 graph to run in Spark/GraphX. I finally had a successful run last night, successful in that it didn’t drop any executors and completed. However, it did take 7 hours to run which seems a little high given that Flink was able to do it in 2 hours (and we won’t mention CGE here because it isn’t fair. ;-)).

 

So, here is the spark-submit I did:

 

/usr/bin/time spark-submit --conf spark.network.timeout=360 --conf spark.shuffle.compress=true --conf spark.locality.wait=3 --total-executor-cores 1024 --executor-memory 96G --class mayo.athena.ga_demo.algm.RunPageRank.RunPageRank target/scala-2.10/runpagerank_2.10-0.5.jar GA_Demo/graphs/mat29_graph.txt

 

I added the spark.network.timeout as it seemed to help with the dropping of executors as execution went on.  For source code changes, I find that setting the numEdgeListPartitions value when you load the graph can have an effect on performance in the general case, and that it should be tuned to match the number of nodes you are running on. This makes sense given that Spark parallelizes based on partitions. 480 is just a current value I came up with; it does not have any special meaning.

 

I’m wondering if the partitioning of memory on the nodes may need to be tweaked in this case to improve locality. There are definitely some tasks that have locality “ANY”, although I’m having some troubles with the history server right now so I can’t say for sure how many.

 

Any thoughts you might have are welcomed. I’d like to be able to beat Flink. ;-)

 

Matt

 

 

Here is the code for the benchmark.

 

nid00046:~/lustre_home/athena_ga.svn/trunk/PageRank> cat src/main/scala/mayo/athena/ga_demo/algm/RunPageRank/RunPageRank.scala

/**

  * \file

  * \date April 7, 2016

  * \author Ruth Poole

  *

  * \copyright 2016, Mayo Clinic, All Rights Reserved.

  *

 

  * This program is free software: you can redistribute it and/or

  * modify it under the terms of the GNU General Public License as

  * published by the Free Software Foundation, either version 3 of the

  * License, or (at your option) any later version.

  *

  * This program is distributed in the hope that it will be useful,

  * but WITHOUT ANY WARRANTY; without even the implied warranty of

  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the

  * GNU General Public License for more details.

  *

  * You should have received a copy of the GNU General Public License

  * along with this program.  If not, see <http://www.gnu.org/licenses/>.

  */

 

package mayo.athena.ga_demo.algm.RunPageRank

 

import org.apache.log4j.{Level,LogManager,PropertyConfigurator}

import org.apache.spark._

import org.apache.spark.graphx._

import org.apache.spark.graphx.lib._

 

object RunPageRank {

 

  def usage():Unit = {

    println("Usage: RunPageRank <directory>")

  }

 

  def main(args: Array[String]):Unit = {

 

    val log = LogManager.getRootLogger

    log.setLevel(Level.WARN)

 

    if(args.length != 0) {

      // Command line arguments

      val directory = args(0)

 

      println( "Will read from " + directory )

 

      var conf = new SparkConf()

      conf.set("spark.serializer","org.apache.spark.serializer.KryoSerializer")

 

      val sc = new SparkContext(conf)

      println("%%%%%%%%%% - App Id" + sc.applicationId)

      // Load a file with edges specified as tab-delimited vertex source and destination.

      //val my_graph = GraphLoader.edgeListFile( sc, directory )

      val my_graph = GraphLoader.edgeListFile( sc, directory , numEdgePartitions = 480 )

 

      val my_verts = my_graph.vertices.map{ case (v,i) => v }

      // Compute page rank, the numeric is the tolerance for convergence, smaller will probably run more iterations

      val my_pageRank = PageRank.runUntilConvergence( my_graph, 0.1 )

 

      // Write results, this will force the lazy execution

      my_pageRank.vertices.saveAsTextFile(directory + "_pr")

    }

    else {

      usage()

    }

  }

}

--------------------------

Matthew Markland | Sr. Analyst/Programmer | Advanced Analytics Unit |  507-538-5493 | markland.matthew@mayo.edu

Mayo Clinic | 200 First Street SW | Rochester, MN 55905 | www.mayoclinic.org

## Additional Notes

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

### Spark Performance Tuning

What runs well at a given number of nodes may blow up on a different number of nodes. To try and diagnose these issues, start with the `Executors` tab in the Spark History. Often there will be one executor per worker node (in Mesos setup on box I was on). The executor may process multiple `tasks` perhaps in parallel.

Tasks map to the partitions that RDDs are broken into. **Watch the balance of tasks per executor and memory being shuffled.**

On the hardware I was on, 

`--total-executor-cores 64` yields Mesos gave me two nodes.

This gives me two executors in this case. If your work has two partitions, than each executor gets one task.

Spark performance is **highly dependent on finding the right number of tasks and correct amount of memory per executor.**

In my example, a 32-node PageRank run on a scale 29 graph didn't work because the memory settings that I tried were from a a 41-node run didn't work; led to a huge amount of data being shuffled.

Upping memory allocation allows run on fewer nodes; it gives more suffle space.

So, `cache()` to avoid recomputation; watch out for shuffles.

# Notes on Apache Spark

`Transformations` produce new RDDs.

`Actions` produce a vaule back to the Spark driver. May cause lazy RDD
computations to be evaluated.

## RDD

An RDD comprises a fixed number of `partitions` each of which has a
number of `records`.

For `narrow` transformations (map, filter) the records required to
compute the new records in a single partion reside in a single
partition in the parent RDD; each object is only dependent on a single
object in the parent.

`Coalesce` can result in a task processing multiple input partitions,
but the transformation is still narrow because the input records used
to compute any single output record can still only reside in a limited
subset of the partitions.

For `wide` transformations (groupByKey, reduceByKey) the data required
to compute the records in a single partition may reside in may
partitions of the parent RDD. Spark must shuffle the data leading to a
new stage with a new set of partitions.


## Execution Environment

Source
[How to Tune Your Apache Spark Jobs Part One](http://blog.cloudera.com/blog/2015/03/how-to-tune-your-apache-spark-jobs-part-1/)

Application consists of a `driver` process and a set of `executor`
processes scattered across nodes. Each `executor` has a number of
slots for running `tasks` into which the work is broken up into.

### Driver

In charge of the high-level control flow of work. Has `jobs` as base
unit. An `action` within a Spark application triggers the lauch of a
Spark job to fulfill it. Spark creates the `job` by examining the
graph of RDDs on which the action depends and creates an execution
plan. An `execution plan` consists of assembling the job's
transformations into `stages`. A `stage` corresponds to a collection
of `tasks` that all execute the same code, each on a different subset
of the data. Each `task` processes its data sequentially. The number
of tasks in a stage is the same as tne number of partitions in the
last RDD in the stage. The number of partitions in an RDD is the same
as the number of partiions in the RDD on which it depends (except for
`coalesce`, `union`, or `cartesian`).

RDDs produced by `textFile` or `hadoopFile` have their partitions
determined by the underlying MapReduce InputFormat; typically a
partition for each HDFS block.

Each stage contains a sequence of transformations which can be
complted without `shuffling` the full data.

Want more tasks to take advantage of the CPUs available.
### Executor

Executes the work in the form of `tasks` as well as store data that is
cached.  Each executor has a number of slots for running tasks and
will run many concurrently throughout its lifetime.
