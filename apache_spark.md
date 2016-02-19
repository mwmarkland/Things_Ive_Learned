* Submitting from the command-line.

Running outside of the spark-shell, you have to build jar's containing everything you need to run your app so that it can be distributed across the cluster. Reminds me of static linking on HPCs.

Here's an example submit (to a local instance) based on the example in the Spark docs.

~~~
spark-submit --class "SimpleApp" target/scala-2.10/simple-project_2.10-1.0.jar
~~~

The jar was built using `sbt`.
