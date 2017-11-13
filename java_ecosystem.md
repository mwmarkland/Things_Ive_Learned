## Running a maven project main class directly
[Simple](https://stackoverflow.com/questions/9846046/run-main-class-of-maven-project)
`mvn exec:java -Dexec.mainClass="markland.AppHello"`

## Running from command line
[With packages](https://stackoverflow.com/questions/19433366/running-java-in-package-from-command-line#19433387)

## Properties files.
[Examples](http://www.mkyong.com/java/java-properties-file-examples/)

## Hibernate

Hibernate validate library. [Getting Started Guide](http://hibernate.org/validator/documentation/getting-started/)
## JVM

[Useful JVM Flags Part 8](https://blog.codecentric.de/en/2014/01/useful-jvm-flags-part-8-gc-logging/)

`jvisualvm`
`jconsole`
`jhat`

## Java Memory Details/Issues
[Hunting Memory Leaks in Java](https://www.toptal.com/java/hunting-memory-leaks-in-java)

[The Secret Life of the Finalizer](http://www.fasterj.com/articles/finalizer1.shtml)

## Maven

Shade plugin creates JARs with all the dependencies needed to run.

`mvn dependency:resolve -X `
`mvn dependency:tree`
`mvn dependency:purge-local-repository`
`mvn versions:set -DnewVersion=1.3.8-RELEASE`

### Archetypes
``mvn archetype:generate -DarchetypeArtifactGroup=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart``

## Eclipse

[Wrong newlines](http://stackoverflow.com/questions/1886185/eclipse-and-windows-newlines#1887619)

## Various tools.

`jmap` can attach and give heap information for a running process.
