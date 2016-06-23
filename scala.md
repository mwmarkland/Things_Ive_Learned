# Scala Hints

## Maven setup of scala project

Using [scala-archetype-simple](https://github.com/davidB/scala-archetype-simple)

mvn archetype:generate -B -DarchetypeGroupId=net.alchim31.maven -DarchetypeArtifactId=scala-archetype-simple -DarchetypeVersion=1.5 -DgroupId=edu.mayo.analytics -DartifactId=PageRank -Dversion=0.1 -Dpackage=edu.mayo.analytics

## Reading from binary file in Scala
- [StackOverflow answer](http://stackoverflow.com/questions/9334590/reading-from-binary-file-scala)

## Scala and Maven
-[Scala and Maven Getting Started](https://blogs.oracle.com/arungupta/entry/scala_and_maven_getting_started). I ran the command from this and got a project laid out with sampe source.
-[scala-lang page on Maven](http://docs.scala-lang.org/tutorials/scala-with-maven.html)

## flatMap

With all the Spark stuff I look at I see a lot of `flatMap()` but I've had a hard time understanding it. I think I've got a better feeling now. There are two ways to think about it; the first is that it is a `map` followed by a `flatten`. I find this somewhat intuitive, but when I look at things I don't ever see it that way. I think the better way of looking at it is that flatMap takes a function that generates a Sequence, maps it across the entries, and then flattens the result. My example for this is

~~~scala
arr.map(_.split(' '))
res24: Array[Array[String]] = Array(Array(Now, is, the, time, for, all, good, men, to, come, to, the, aid, of, their, party.))
~~~

So, if I did a `flatMap()` to the item above it would flatten out the `Array`'s into a single array of `String`. This matches the most common cannonical example.

You could also look at it as:

~~~scala
scala> val t = res14
t: Seq[Int] = List(1, 3, 5, 8)

scala> t.flatMap(x => Seq(x,2))
res16: Seq[Int] = List(1, 2, 3, 2, 5, 2, 8, 2)
~~~

Here the `flatMap` map portion would create a list of lists that is then flattened out.

I agree that a common use, seen with many web examples, has to do with lists of `Option` types.

[Good link.](http://tfs/tfs/MayoClinic/IMA/Advanced%20Analytics)

## Scala I/O

I was (am) confused about the correct methods to use for I/O. You can
access the Java ones, of course, but Scala does have a `scala.io`
package. One thing that confused me when looking at `scala.io.Source`
was that I couldn't seem to find the documentation for `fromFile()` on
the web. I discovered that this interface doesn't exist in the *class
Source* but is instead in the **object Source** denoted by the little
icons next to the name `Source` in the API docs. I will have to think
abou this some more. The object would be a singleton that must be
created and available within the `scala.io` package.

