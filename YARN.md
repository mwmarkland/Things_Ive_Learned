# Introduction - Resource Management for Spark.

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
Executors on a given node.


# The Teradata Box.

Ran `yarn node -list` to get a list of nodes and then tried this.

```
yarn node -status hdpr04dn04.mayo.edu:45454
16/07/01 10:27:14 INFO impl.TimelineClientImpl:  Timeline service address: http://hdpr04mn01.mayo.edu:8188/ws/v1/timeline/
Node Report :
    Node-Id : hdpr04dn04.mayo.edu:45454
    Rack : /default-rack
    Node-State : RUNNING
    Node-Http-Address : hdpr04dn04.mayo.edu:8042
    Last-Health-Update : Fri 01/Jul/16 10:26:29:963CDT
    Health-Report :
    Containers : 0
    Memory-Used : 0MB
    Memory-Capacity : 98304MB
    CPU-Used : 0 vcores
    CPU-Capacity 24 vcores
    Node-Labels :
```

So it looks like if I asked for 2 executors with 10 cores each, I
could get both of them on the same node on this box?

