## dtrace and friends
[Top 10 dtrace scripts](http://dtrace.org/blogs/brendan/2011/10/10/top-10-dtrace-scripts-for-mac-os-x/)

## MacPorts
### How to select gcc version.
[Webpage](ficksworkshop.com/blog/14-coding/64-installing-gcc-on-mac)

Basic gist

`sudo port select --list gcc`
`sudo port select --set gcc mp-gcc*`

## Homebrew

## Java
Checking installed versions `/usr/libexec/java_home -V`:
``` 
R5081566:~ m134910$ /usr/libexec/java_home -V
Matching Java Virtual Machines (2):
    1.8.0_102, x86_64:	"Java SE 8"	/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
    1.7.0_80, x86_64:	"Java SE 7"	/Library/Java/JavaVirtualMachines/jdk1.7.0_80.jdk/Contents/Home

/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
```
This was run after doing `brew install Caskroom/versions/java7` on the box.

Changing to a different version
```
R5081566:nlp-complex-pap m134910$ java -version
java version "1.8.0_102"
Java(TM) SE Runtime Environment (build 1.8.0_102-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.102-b14, mixed mode)
R5081566:nlp-complex-pap m134910$ /usr/libexec/java_home -V
Matching Java Virtual Machines (2):
    1.8.0_102, x86_64:	"Java SE 8"	/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
    1.7.0_80, x86_64:	"Java SE 7"	/Library/Java/JavaVirtualMachines/jdk1.7.0_80.jdk/Contents/Home

/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
R5081566:nlp-complex-pap m134910$ export JAVA_HOME=`/usr/libexec/java_home -v 1.7.0_80`
R5081566:nlp-complex-pap m134910$ echo $JAVA_HOME
/Library/Java/JavaVirtualMachines/jdk1.7.0_80.jdk/Contents/Home
```


