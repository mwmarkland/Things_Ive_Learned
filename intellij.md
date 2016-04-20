# Install on Mac

Downloaded IntelliJ community edition for the Mac to setup to try SBT
and Scala tooling. Installed Scala plugin and the sbt plugin. sbt
plugin points to
[github link](https://github.com/orfjackal/idea-sbt-plugin/wiki) as
documentation. It recommends adding the `sbt-idea` plugin to work with
IntelliJ.

After this, I restarted. Next I pulled down the `sbt-idea` plugin and
set it up in sbt. I then ran the `gen-idea` sbt command to build the
project files for IntelliJ. Import errors happened, mostly messages
about SDK stuff. Opening up the project and then double-clicking on
the source file popped up two message dialogs that "Project JDK is not
defined." and "No Scala SDK in module." with links to set each
up. Trying that.

Importing the project seemed to not go well. Warning from IntelliJ
about using the `sbt-idea` plugin as it creates something "downlevel."
May want to blow away all IDE project files in the directory and just
try to import a straight up directory.

Moving further in the process, it appears that the sbt plugin isn't really needed for IntelliJ. The IDE has its own setup and you can open an SBT console window using View->Tool Windows. From that console you can do builds. The Build menu pulldown didn't seem to do what I wanted.


