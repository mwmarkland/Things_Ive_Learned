# Acquire Eclipse.

[Eclipse](http://www.eclipse.org)

Click on the `Download` link.

Once you have the installer and run it, select the Eclipse version to
install. I chose `Eclipse IDE for Java Developers`.

# Add Extensions/Plugins

## From InfoWorlds 21 plug-ins to make the most of Eclipse
- Darkest Dark
- Spotbugs
- Checkstyle
- M2Eclipse
- Unnecessary Code Detector
- SonarLint
- JRebel
- TestNG
- Bytecode Outline
- PyDev
- Nodeclipse
- Scala IDE
- Kotlin
- YEdit
- UML Designer
- ImageJ

## From the Eclipse Marketplace

- Scala-IDE
- Maven Integration for Eclipse
- Markdown Text Editor
- PyDev
- Nodeclipse
- Spring support
- Angular support

Optionally you could also add this for "advanced" TFS support:
- Team Explorer Everywhere Plugin

## Other items.

### Searching for things.

It seems like there are a lot of possible ways to search for things. 
Try the following:

Highlight a function/class and do "CMD-SHIFT-G" on a Mac to get the references in the Workspace for something.
"CTRL-H" brings up the search menu.

### A dump of what I have installed on my Mac
```
*** Date: Tuesday, May 2, 2017 at 8:13:48 AM Central Daylight Time

*** Platform Details:

*** System properties:
applicationXMI=org.eclipse.ui.workbench/LegacyIDE.e4xmi
awt.toolkit=sun.lwawt.macosx.LWCToolkit
eclipse.application=org.eclipse.ui.ide.workbench
eclipse.buildId=4.6.3.M20170301-0400
eclipse.commands=-os
macosx
-ws
cocoa
-arch
x86_64
-showsplash
-launcher
/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/MacOS/eclipse
-name
Eclipse
--launcher.library
/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.launcher.cocoa.macosx.x86_64_1.1.401.v20161122-1740/eclipse_1615.so
-startup
/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/MacOS//../Eclipse/plugins/org.eclipse.equinox.launcher_1.3.201.v20161025-1711.jar
--launcher.appendVmargs
-product
org.eclipse.epp.package.jee.product
-data
file:/Users/m134910/Documents/workspace/nlp/
-launcher
/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/MacOS/eclipse
-product
org.eclipse.epp.package.jee.product
-keyring
/Users/m134910/.eclipse_keyring
-vm
/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/server/libjvm.dylib
eclipse.home.location=file:/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/Eclipse/
eclipse.launcher=/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/MacOS/eclipse
eclipse.launcher.name=Eclipse
eclipse.p2.data.area=file:/Users/m134910/.p2/
eclipse.p2.max.threads=10
eclipse.p2.profile=_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse
eclipse.product=org.eclipse.epp.package.jee.product
eclipse.startTime=1493730761900
eclipse.stateSaveDelayInterval=30000
eclipse.vm=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/server/libjvm.dylib
eclipse.vmargs=-Dosgi.requiredJavaVersion=1.8
-XX:+UseG1GC
-XX:+UseStringDeduplication
-XstartOnFirstThread
-Dorg.eclipse.swt.internal.carbon.smallFonts
-Dosgi.requiredJavaVersion=1.8
-Xms256m
-Xmx1024m
-Xdock:icon=../Resources/Eclipse.icns
-XstartOnFirstThread
-Dorg.eclipse.swt.internal.carbon.smallFonts
-Declipse.p2.max.threads=10
-Doomph.update.url=http://download.eclipse.org/oomph/updates/milestone/latest
-Doomph.redirection.index.redirection=index:/->http://git.eclipse.org/c/oomph/org.eclipse.oomph.git/plain/setups/
-Dosgi.requiredJavaVersion=1.8
-XX:+UseG1GC
-XX:+UseStringDeduplication
-XstartOnFirstThread
-Dorg.eclipse.swt.internal.carbon.smallFonts
-Dosgi.requiredJavaVersion=1.8
-Xms256m
-Xmx1024m
-Xdock:icon=../Resources/Eclipse.icns
-XstartOnFirstThread
-Dorg.eclipse.swt.internal.carbon.smallFonts
-Declipse.p2.max.threads=10
-Doomph.update.url=http://download.eclipse.org/oomph/updates/milestone/latest
-Doomph.redirection.index.redirection=index:/->http://git.eclipse.org/c/oomph/org.eclipse.oomph.git/plain/setups/
-Djava.class.path=/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/MacOS//../Eclipse/plugins/org.eclipse.equinox.launcher_1.3.201.v20161025-1711.jar
equinox.init.uuid=true
equinox.use.ds=true
file.encoding=UTF-8
file.encoding.pkg=sun.io
file.separator=/
ftp.nonProxyHosts=local|*.local|169.254/16|*.169.254/16
gopherProxySet=false
gosh.args=--nointeractive
guice.disable.misplaced.annotation.check=true
java.awt.graphicsenv=sun.awt.CGraphicsEnvironment
java.awt.printerjob=sun.lwawt.macosx.CPrinterJob
java.class.path=/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/MacOS//../Eclipse/plugins/org.eclipse.equinox.launcher_1.3.201.v20161025-1711.jar
java.class.version=52.0
java.endorsed.dirs=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/endorsed
java.ext.dirs=/Users/m134910/Library/Java/Extensions:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/ext:/Library/Java/Extensions:/Network/Library/Java/Extensions:/System/Library/Java/Extensions:/usr/lib/java
java.home=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre
java.io.tmpdir=/var/folders/q8/f25xtcp13v5b6nh_zmn3w2v8x1r8qq/T/
java.library.path=/Users/m134910/Library/Java/Extensions:/Library/Java/Extensions:/Network/Library/Java/Extensions:/System/Library/Java/Extensions:/usr/lib/java:.
java.runtime.name=Java(TM) SE Runtime Environment
java.runtime.version=1.8.0_102-b14
java.specification.name=Java Platform API Specification
java.specification.vendor=Oracle Corporation
java.specification.version=1.8
java.vendor=Oracle Corporation
java.vendor.url=http://java.oracle.com/
java.vendor.url.bug=http://bugreport.sun.com/bugreport/
java.version=1.8.0_102
java.vm.info=mixed mode
java.vm.name=Java HotSpot(TM) 64-Bit Server VM
java.vm.specification.name=Java Virtual Machine Specification
java.vm.specification.vendor=Oracle Corporation
java.vm.specification.version=1.8
java.vm.vendor=Oracle Corporation
java.vm.version=25.102-b14
line.separator=

oomph.redirection.index.redirection=index:/->http://git.eclipse.org/c/oomph/org.eclipse.oomph.git/plain/setups/
oomph.update.url=http://download.eclipse.org/oomph/updates/milestone/latest
org.apache.commons.logging.Log=org.apache.commons.logging.impl.NoOpLog
org.eclipse.equinox.launcher.splash.location=/Users/m134910/.p2/pool/plugins/org.eclipse.platform_4.6.3.v20170301-0400/splash.bmp
org.eclipse.equinox.simpleconfigurator.configUrl=file:org.eclipse.equinox.simpleconfigurator/bundles.info
org.eclipse.m2e.log.dir=/Users/m134910/Documents/workspace/nlp/.metadata/.plugins/org.eclipse.m2e.logback.configuration
org.eclipse.swt.internal.carbon.smallFonts=
org.eclipse.swt.internal.deviceZoom=100
org.eclipse.update.reconcile=false
org.osgi.framework.executionenvironment=OSGi/Minimum-1.0,OSGi/Minimum-1.1,OSGi/Minimum-1.2,JavaSE/compact1-1.8,JavaSE/compact2-1.8,JavaSE/compact3-1.8,JRE-1.1,J2SE-1.2,J2SE-1.3,J2SE-1.4,J2SE-1.5,JavaSE-1.6,JavaSE-1.7,JavaSE-1.8
org.osgi.framework.language=en
org.osgi.framework.os.name=MacOSX
org.osgi.framework.os.version=10.11.6
org.osgi.framework.processor=x86-64
org.osgi.framework.system.capabilities=osgi.ee; osgi.ee="OSGi/Minimum"; version:List<Version>="1.0, 1.1, 1.2",osgi.ee; osgi.ee="JRE"; version:List<Version>="1.0, 1.1",osgi.ee; osgi.ee="JavaSE"; version:List<Version>="1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8",osgi.ee; osgi.ee="JavaSE/compact1"; version:List<Version>="1.8",osgi.ee; osgi.ee="JavaSE/compact2"; version:List<Version>="1.8",osgi.ee; osgi.ee="JavaSE/compact3"; version:List<Version>="1.8"
org.osgi.framework.system.packages=javax.accessibility,javax.activation,javax.activity,javax.annotation,javax.annotation.processing,javax.crypto,javax.crypto.interfaces,javax.crypto.spec,javax.imageio,javax.imageio.event,javax.imageio.metadata,javax.imageio.plugins.bmp,javax.imageio.plugins.jpeg,javax.imageio.spi,javax.imageio.stream,javax.jws,javax.jws.soap,javax.lang.model,javax.lang.model.element,javax.lang.model.type,javax.lang.model.util,javax.management,javax.management.loading,javax.management.modelmbean,javax.management.monitor,javax.management.openmbean,javax.management.relation,javax.management.remote,javax.management.remote.rmi,javax.management.timer,javax.naming,javax.naming.directory,javax.naming.event,javax.naming.ldap,javax.naming.spi,javax.net,javax.net.ssl,javax.print,javax.print.attribute,javax.print.attribute.standard,javax.print.event,javax.rmi,javax.rmi.CORBA,javax.rmi.ssl,javax.script,javax.security.auth,javax.security.auth.callback,javax.security.auth.kerberos,javax.security.auth.login,javax.security.auth.spi,javax.security.auth.x500,javax.security.cert,javax.security.sasl,javax.sound.midi,javax.sound.midi.spi,javax.sound.sampled,javax.sound.sampled.spi,javax.sql,javax.sql.rowset,javax.sql.rowset.serial,javax.sql.rowset.spi,javax.swing,javax.swing.border,javax.swing.colorchooser,javax.swing.event,javax.swing.filechooser,javax.swing.plaf,javax.swing.plaf.basic,javax.swing.plaf.metal,javax.swing.plaf.multi,javax.swing.plaf.nimbus,javax.swing.plaf.synth,javax.swing.table,javax.swing.text,javax.swing.text.html,javax.swing.text.html.parser,javax.swing.text.rtf,javax.swing.tree,javax.swing.undo,javax.tools,javax.transaction,javax.transaction.xa,javax.xml,javax.xml.bind,javax.xml.bind.annotation,javax.xml.bind.annotation.adapters,javax.xml.bind.attachment,javax.xml.bind.helpers,javax.xml.bind.util,javax.xml.crypto,javax.xml.crypto.dom,javax.xml.crypto.dsig,javax.xml.crypto.dsig.dom,javax.xml.crypto.dsig.keyinfo,javax.xml.crypto.dsig.spec,javax.xml.datatype,javax.xml.namespace,javax.xml.parsers,javax.xml.soap,javax.xml.stream,javax.xml.stream.events,javax.xml.stream.util,javax.xml.transform,javax.xml.transform.dom,javax.xml.transform.sax,javax.xml.transform.stax,javax.xml.transform.stream,javax.xml.validation,javax.xml.ws,javax.xml.ws.handler,javax.xml.ws.handler.soap,javax.xml.ws.http,javax.xml.ws.soap,javax.xml.ws.spi,javax.xml.ws.spi.http,javax.xml.ws.wsaddressing,javax.xml.xpath,org.ietf.jgss,org.omg.CORBA,org.omg.CORBA_2_3,org.omg.CORBA_2_3.portable,org.omg.CORBA.DynAnyPackage,org.omg.CORBA.ORBPackage,org.omg.CORBA.portable,org.omg.CORBA.TypeCodePackage,org.omg.CosNaming,org.omg.CosNaming.NamingContextExtPackage,org.omg.CosNaming.NamingContextPackage,org.omg.Dynamic,org.omg.DynamicAny,org.omg.DynamicAny.DynAnyFactoryPackage,org.omg.DynamicAny.DynAnyPackage,org.omg.IOP,org.omg.IOP.CodecFactoryPackage,org.omg.IOP.CodecPackage,org.omg.Messaging,org.omg.PortableInterceptor,org.omg.PortableInterceptor.ORBInitInfoPackage,org.omg.PortableServer,org.omg.PortableServer.CurrentPackage,org.omg.PortableServer.POAManagerPackage,org.omg.PortableServer.POAPackage,org.omg.PortableServer.portable,org.omg.PortableServer.ServantLocatorPackage,org.omg.SendingContext,org.omg.stub.java.rmi,org.w3c.dom,org.w3c.dom.bootstrap,org.w3c.dom.css,org.w3c.dom.events,org.w3c.dom.html,org.w3c.dom.ls,org.w3c.dom.ranges,org.w3c.dom.stylesheets,org.w3c.dom.traversal,org.w3c.dom.views,org.w3c.dom.xpath,org.xml.sax,org.xml.sax.ext,org.xml.sax.helpers
org.osgi.framework.uuid=f9004d1f-d8df-4049-9e69-c75fce4bd4f7
org.osgi.framework.vendor=Eclipse
org.osgi.framework.version=1.8.0
org.osgi.supports.framework.extension=true
org.osgi.supports.framework.fragment=true
org.osgi.supports.framework.requirebundle=true
os.arch=x86_64
os.name=Mac OS X
os.version=10.11.6
osgi.arch=x86_64
osgi.bundles=reference:file:org.eclipse.osgi.compatibility.state_1.0.200.v20160504-1419.jar,reference:file:org.eclipse.wst.jsdt.nashorn.extension_1.0.2.v201610280128.jar,reference:file:org.eclipse.equinox.simpleconfigurator_1.1.200.v20160504-1450.jar@1:start
osgi.bundles.defaultStartLevel=4
osgi.compatibility.bootdelegation=true
osgi.compatibility.bootdelegation.default=true
osgi.configuration.area=file:/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/Eclipse/configuration/
osgi.configuration.cascaded=false
osgi.framework=file:/Users/m134910/.p2/pool/plugins/org.eclipse.osgi_3.11.3.v20170209-1843.jar
osgi.framework.extensions=reference:file:org.eclipse.osgi.compatibility.state_1.0.200.v20160504-1419.jar,reference:file:org.eclipse.wst.jsdt.nashorn.extension_1.0.2.v201610280128.jar
osgi.framework.shape=jar
osgi.framework.useSystemProperties=true
osgi.frameworkClassPath=., file:/Users/m134910/.p2/pool/plugins/org.eclipse.osgi.compatibility.state_1.0.200.v20160504-1419.jar, file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.nashorn.extension_1.0.2.v201610280128.jar
osgi.install.area=file:/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/Eclipse/
osgi.instance.area=file:/Users/m134910/Documents/workspace/nlp/
osgi.instance.area.default=file:/Users/m134910/Documents/workspace/
osgi.logfile=/Users/m134910/Documents/workspace/nlp/.metadata/.log
osgi.nl=en_US
osgi.os=macosx
osgi.requiredJavaVersion=1.8
osgi.splashLocation=/Users/m134910/.p2/pool/plugins/org.eclipse.platform_4.6.3.v20170301-0400/splash.bmp
osgi.splashPath=file:/Users/m134910/.p2/pool/plugins/org.eclipse.platform_4.6.3.v20170301-0400
osgi.syspath=/Users/m134910/.p2/pool/plugins
osgi.tracefile=/Users/m134910/Documents/workspace/nlp/.metadata/trace.log
osgi.user.area=file:/Users/m134910/user/
osgi.ws=cocoa
path.separator=:
socksNonProxyHosts=local|*.local|169.254/16|*.169.254/16
sun.arch.data.model=64
sun.boot.class.path=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/resources.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/rt.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/sunrsasign.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/jsse.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/jce.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/charsets.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/jfr.jar:/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/classes
sun.boot.library.path=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib
sun.cpu.endian=little
sun.cpu.isalist=
sun.io.unicode.encoding=UnicodeBig
sun.jnu.encoding=UTF-8
sun.management.compiler=HotSpot 64-Bit Tiered Compilers
sun.os.patch.level=unknown
user.country=US
user.dir=/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/MacOS
user.home=/Users/m134910
user.language=en
user.name=m134910
user.timezone=America/Chicago

*** Features:
org.eclipse.aether.maven.feature (3.1.0.20140706-2237) "Maven Aether Provider Bundle"
org.eclipse.cft.server.core.feature (1.2.1.v201703012110) "Cloud Foundry Tools"
org.eclipse.cft.server.ui.feature (1.0.8.v201703012110) "Cloud Foundry Tools"
org.eclipse.datatools.common.doc.user (1.13.0.201603142002) "Data Tools Platform User Documentation"
org.eclipse.datatools.connectivity.doc.user (1.13.0.201603142002) "Data Tools Platform Connectivity User Documentation"
org.eclipse.datatools.connectivity.feature (1.13.0.201603142002) "Data Tools Platform Connectivity Plug-in"
org.eclipse.datatools.connectivity.oda.designer.core.feature (1.13.0.201603142002) "DTP ODA Designer UI Framework Plug-in"
org.eclipse.datatools.connectivity.oda.designer.feature (1.13.0.201603142002) "DTP ODA Designer UI Framework Plug-in"
org.eclipse.datatools.connectivity.oda.feature (1.13.0.201603142002) "DTP Open Data Access"
org.eclipse.datatools.doc.user (1.13.0.201603142002) "Data Tool Platform User Documentation"
org.eclipse.datatools.enablement.apache.derby.feature (1.13.0.201603142002) "High-level Sybase Enablement Plug-in"
org.eclipse.datatools.enablement.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.hsqldb.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.ibm.feature (1.13.0.201603142002) "pluginName"
org.eclipse.datatools.enablement.ingres.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.jdbc.feature (1.13.0.201603142002) "High-level Sybase Enablement Plug-in"
org.eclipse.datatools.enablement.jdt.feature (1.13.0.201603142002) "Data Tools Platform Connectivity JDT Extension Plug-in"
org.eclipse.datatools.enablement.msft.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.mysql.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.oda.designer.feature (1.13.0.201603142002) "Eclipse Data Tools Platform XML ODA Designer"
org.eclipse.datatools.enablement.oda.feature (1.13.0.201603142002) "Eclipse Data Tools Platform XML ODA Runtime Driver"
org.eclipse.datatools.enablement.oracle.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.postgresql.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.sap.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.sqlite.feature (1.13.0.201603142002) "Eclipse Data Tools Platform Enablement"
org.eclipse.datatools.enablement.sybase.feature (1.13.0.201603142002) "High-level Sybase Enablement Plug-in"
org.eclipse.datatools.intro (1.13.0.201603142002) "Eclipse Data Tools Platform Intro Plug-in"
org.eclipse.datatools.modelbase.feature (1.13.0.201603142002) "Eclipse Data Tools Platform SQLModel Plug-in"
org.eclipse.datatools.sqldevtools.ddlgen.feature (1.13.0.201603142002) "Eclipse Data Tools Platform FE UI Plug-in"
org.eclipse.datatools.sqldevtools.feature (1.13.0.201603142002) "Eclipse Data Tools Platform SQL Tools Common UI Plug-in"
org.eclipse.datatools.sqldevtools.parsers.feature (1.13.0.201603142002) "Eclipse Data Tools Platform SQL Parser Plugin"
org.eclipse.datatools.sqltools.doc.user (1.13.0.201603142002) "Data Tools Platform SQL Tools User Documentation"
org.eclipse.draw2d (3.10.100.201606061308) "Draw2d"
org.eclipse.egit (4.6.1.201703071140-r) "Git integration for Eclipse"
org.eclipse.egit.mylyn (4.6.1.201703071140-r) "Git integration for Eclipse"
org.eclipse.emf (2.12.0.v20160526-0356) "EMF - Eclipse Modeling Framework Runtime and Tools"
org.eclipse.emf.codegen (2.11.0.v20160526-0356) "EMF Code Generation"
org.eclipse.emf.codegen.ecore (2.12.0.v20160526-0356) "EMF Ecore Code Generator"
org.eclipse.emf.codegen.ecore.ui (2.12.0.v20160526-0356) "EMF Ecore Code Generator UI"
org.eclipse.emf.codegen.ui (2.8.0.v20160526-0356) "EMF Code Generation UI"
org.eclipse.emf.common (2.12.0.v20160420-0247) "EMF Common"
org.eclipse.emf.common.ui (2.11.0.v20160526-0356) "EMF Common UI"
org.eclipse.emf.converter (2.11.0.v20160526-0356) "EMF Model Converter"
org.eclipse.emf.databinding (1.4.0.v20160526-0356) "EMF Data Binding"
org.eclipse.emf.databinding.edit (1.4.0.v20160526-0356) "EMF Edit Data Binding"
org.eclipse.emf.ecore (2.12.0.v20160420-0247) "EMF Ecore"
org.eclipse.emf.ecore.edit (2.9.0.v20160526-0356) "EMF Ecore Edit"
org.eclipse.emf.ecore.editor (2.12.0.v20160526-0356) "EMF Sample Ecore Editor"
org.eclipse.emf.edit (2.12.0.v20160526-0356) "EMF Edit"
org.eclipse.emf.edit.ui (2.12.0.v20160526-0356) "EMF Edit UI"
org.eclipse.emf.mapping (2.9.0.v20160526-0356) "EMF Mapping"
org.eclipse.emf.mapping.ecore (2.9.0.v20160526-0356) "EMF Ecore Mapping"
org.eclipse.emf.mapping.ecore.editor (2.10.0.v20160526-0356) "EMF Ecore Mapping Editor"
org.eclipse.emf.mapping.ui (2.9.0.v20160526-0356) "EMF Mapping UI"
org.eclipse.epp.mpc (1.5.4.v20170222-1941) "Marketplace Client"
org.eclipse.epp.package.jee.feature (4.6.3.20170314-1500) "Bundle-Name"
org.eclipse.gef (3.11.0.201606061308) "GEF (MVC)"
org.eclipse.help (2.2.2.v20170301-0400) "Help System Base"
org.eclipse.jdt (3.12.3.v20170301-0400) "Eclipse Java Development Tools"
org.eclipse.jgit (4.6.1.201703071140-r) "JGit Core"
org.eclipse.jpt.common.eclipselink.feature (1.3.200.v201603180253) "Dali Java Persistence Tools - EclipseLink Common"
org.eclipse.jpt.common.feature (1.5.0.v201607281951) "Dali Java Persistence Tools - Common"
org.eclipse.jpt.dbws.eclipselink.feature (1.2.200.v201603180253) "Dali Java Persistence Tools - EclipseLink DBWS Support"
org.eclipse.jpt.jaxb.eclipselink.feature (1.4.200.v201603180253) "Dali Java Persistence Tools - EclipseLink MOXy (JAXB) Support"
org.eclipse.jpt.jaxb.feature (1.5.100.v201603180253) "Dali Java Persistence Tools - JAXB Support"
org.eclipse.jpt.jpa.eclipselink.feature (3.4.100.v201603180253) "Dali Java Persistence Tools - EclipseLink JPA Support"
org.eclipse.jpt.jpa.feature (3.5.0.v201607131827) "Dali Java Persistence Tools - JPA Support"
org.eclipse.jst.common.fproj.enablement.jdt (3.8.0.v201603091933) "Eclipse Faceted Project Framework JDT Enablement"
org.eclipse.jst.enterprise_ui.feature (3.8.0.v201701262139) "Eclipse Java EE Developer Tools"
org.eclipse.jst.ws.axis2tools.feature (1.1.301.v201410160332) "Axis2 Tools"
org.eclipse.jst.ws.cxf.feature (1.1.300.v201701262158) "CXF Web Services Core"
org.eclipse.jst.ws.jaxws.feature (1.2.300.v201701262158) "JAX-WS Tools Core"
org.eclipse.m2e.feature (1.7.0.20160603-1933) "Maven Integration for Eclipse"
org.eclipse.m2e.logback.feature (1.7.0.20160603-1933) "m2e logback configuration"
org.eclipse.m2e.wtp.feature (1.3.1.20160831-1005) "Maven Integration for Eclipse WTP"
org.eclipse.m2e.wtp.jaxrs.feature (1.3.1.20160831-1005) "Maven JAX-RS Configurator"
org.eclipse.m2e.wtp.jpa.feature (1.3.1.20160831-1005) "Maven JPA Configurator"
org.eclipse.m2e.wtp.jsf.feature (1.3.1.20160831-1005) "Maven JSF Configurator"
org.eclipse.mylyn_feature (3.21.0.v20160914-0252) "Mylyn Tasks Core"
org.eclipse.mylyn.bugzilla_feature (3.21.0.v20160909-1813) "Mylyn Tasks Core"
org.eclipse.mylyn.commons (3.21.0.v20160707-1856) "Mylyn Commons"
org.eclipse.mylyn.commons.identity (1.13.0.v20160630-1702) "Mylyn Commons"
org.eclipse.mylyn.commons.notifications (1.13.0.v20160721-2347) "Mylyn Commons"
org.eclipse.mylyn.commons.repositories (1.13.0.v20160630-1702) "Mylyn Commons"
org.eclipse.mylyn.context_feature (3.21.0.v20160815-2336) "Mylyn Context"
org.eclipse.mylyn.discovery (3.21.0.v20160729-1739) "Mylyn Commons"
org.eclipse.mylyn.ide_feature (3.21.0.v20160912-1820) "Mylyn Context"
org.eclipse.mylyn.java_feature (3.21.0.v20160701-1337) "Mylyn Context"
org.eclipse.mylyn.monitor (3.21.0.v20160630-1702) "Mylyn Commons"
org.eclipse.mylyn.tasks.ide (3.21.0.v20160929-1805) "Mylyn Tasks Core"
org.eclipse.mylyn.team_feature (3.21.0.v20160701-1337) "Mylyn Context"
org.eclipse.mylyn.wikitext_feature (2.10.1.v20161129-1925) "Mylyn WikiText"
org.eclipse.oomph.p2 (1.7.0.v20170228-1751) "Oomph P2 Management"
org.eclipse.oomph.setup (1.7.0.v20170305-1123) "Oomph Setup"
org.eclipse.oomph.setup.core (1.7.0.v20170301-0747) "Oomph Setup Core"
org.eclipse.pde (3.12.3.v20170301-0400) "PDE"
org.eclipse.platform (4.6.3.v20170301-0400) "Eclipse Platform"
org.eclipse.rcp (4.6.3.v20170301-0400) "Eclipse RCP"
org.eclipse.recommenders.mylyn.rcp.feature (2.4.6.v20170307-1041) "Code Recommenders Mylyn Completion UI"
org.eclipse.recommenders.rcp.feature (2.4.6.v20170307-1041) "Code Recommenders UI"
org.eclipse.rse (3.7.2.201610260947) "Remote System Explorer End-User Runtime"
org.eclipse.rse.core (3.7.2.201610260947) "RSE Core"
org.eclipse.rse.dstore (3.7.0.201610260947) "RSE DStore Services"
org.eclipse.rse.ftp (3.7.1.201610260947) "RSE FTP Service"
org.eclipse.rse.local (3.7.0.201610260947) "RSE Local Services"
org.eclipse.rse.ssh (3.7.0.201610260947) "RSE SSH Services"
org.eclipse.rse.telnet (3.7.0.201610260947) "RSE Telnet Service"
org.eclipse.rse.useractions (3.7.0.201610260947) "Remote System Explorer User Actions"
org.eclipse.tm.terminal.control.feature (4.2.0.201611281915) "Terminal Control (Embeddable Widget)"
org.eclipse.tm.terminal.feature (4.2.0.201611281915) "Terminal View Core"
org.eclipse.tm.terminal.view.feature (4.2.0.201611281915) "Terminal View Core"
org.eclipse.wst.common.fproj (3.7.0.v201505072140) "Eclipse Faceted Project Framework"
org.eclipse.wst.jsdt.chromium.debug.feature (0.5.200.v201701261810) "Chromium JavaScript Remote Debugger"
org.eclipse.wst.jsdt.feature (2.0.200.v201612211424) "Eclipse JavaScript Development Tools"
org.eclipse.wst.json_ui.feature (1.0.2.v201612232230) "Eclipse JSON Editors and Tools"
org.eclipse.wst.web_ui.feature (3.8.2.v201702270442) "Eclipse Web Developer Tools"
org.eclipse.wst.xml_ui.feature (3.8.2.v201702270442) "Eclipse XML Editors and Tools"
org.eclipse.wst.xml.xpath2.processor.feature (2.0.301.v201409111854) "Eclipse XPath 2 Developers Tools"
org.eclipse.wst.xsl.feature (1.3.401.v201509231858) "Eclipse XSL Developer Tools"
org.sonatype.m2e.mavenarchiver.feature (0.17.2.201606141937-signed-20160830073346) "m2e connector for the mavenarchiver and pom properties"
org.springframework.ide.eclipse.aeri.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.aop.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.autowire.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.batch.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.boot.dash.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.data.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.integration.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.maven.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.security.feature (3.8.4.201703310634-RELEASE) "Spring IDE"
org.springframework.ide.eclipse.webflow.feature (3.8.4.201703310634-RELEASE) "Spring IDE"

*** Plug-in Registry:
ch.qos.logback.classic (1.0.7.v20121108-1250) "Logback Classic Module" [Resolved]
ch.qos.logback.core (1.0.7.v20121108-1250) "Logback Core Module" [Resolved]
ch.qos.logback.slf4j (1.0.7.v201505121915) "Logback Native SLF4J Logger" [Resolved]
com.fasterxml.jackson.core.jackson-annotations (2.6.2.v20161117-2150) "Jackson-annotations" [Resolved]
com.fasterxml.jackson.core.jackson-core (2.6.2.v20161117-2150) "Jackson-core" [Resolved]
com.fasterxml.jackson.core.jackson-databind (2.6.2.v20161117-2150) "jackson-databind" [Resolved]
com.github.eclipsecolortheme (1.0.0.201410260308) "Eclipse Color Theme" [Starting]
com.google.gson (2.2.4.v201311231704) "Google GSON" [Resolved]
com.google.guava (15.0.0.v201403281430) "Guava: Google Core Libraries for Java" [Resolved]
com.google.inject (3.0.0.v201605172100) "Google Guice (No AOP)" [Resolved]
com.google.inject.multibindings (3.0.0.v201605172100) "Google Guice (No AOP)" [Resolved]
com.google.protobuf (2.4.0.v201105131100) "Protocol Buffers" [Starting]
com.ibm.icu (56.1.0.v201601250100) "International Components for Unicode for Java (ICU4J)" [Active]
com.jcraft.jsch (0.1.54.v20170116-1932) "JSch" [Resolved]
com.sun.el (2.2.0.v201303151357) "Javax Expression Language Reference Implementation Bundle" [Resolved]
io.projectreactor.reactor-core (3.0.5.201703211214-RELEASE) "io.projectreactor.reactor-core" [Resolved]
java_cup.runtime (0.10.0.v201005080400) "Java Cup" [Resolved]
javaewah (1.1.6.v20160919-1400) "javaewah" [Resolved]
javax.activation (1.1.0.v201211130549) "Apache Geronimo Activation Plug-in" [Resolved]
javax.annotation (1.2.0.v201602091430) "javax.annotation Bundle" [Resolved]
javax.el (2.2.0.v201303151357) "Javax Expression Language Bundle" [Resolved]
javax.inject (1.0.0.v20091030) "Atinject Dependency Injection Annotations" [Resolved]
javax.jms (1.1.0.v201205091237) "JMS API" [Resolved]
javax.jws (2.0.0.v201005080400) "Web Services Metadata" [Resolved]
javax.mail (1.4.0.v201005080615) "Javax Mail Plug-in" [Resolved]
javax.persistence (2.1.0.v201304241213) "Java Persistence API 2.1" [Resolved]
javax.servlet (3.1.0.v201410161800) "Servlet API Bundle" [Resolved]
javax.servlet.jsp (2.2.0.v201112011158) "JSP API Bundle" [Resolved]
javax.validation (1.0.0.GA_v201205091237) "Java Bean Validation API" [Resolved]
javax.wsdl (1.6.2.v201012040545) "WSDL4J" [Resolved]
javax.wsdl (1.5.1.v201012040544) "WSDL4J" [Resolved]
javax.xml (1.3.4.v201005080400) "JAXP XML" [Resolved]
javax.xml.rpc (1.1.0.v201209140446) "JAX-RPC" [Resolved]
javax.xml.soap (1.2.0.v201005080501) "SAAJ" [Resolved]
javax.xml.stream (1.0.1.v201004272200) "Java XML Streaming API" [Resolved]
javax.xml.ws (2.1.0.v200902101523) "Java API for XML Web Services (JAX-WS)" [Resolved]
net.sourceforge.lpg.lpgjavaruntime (1.1.0.v201004271650) "SourceForge LPG" [Resolved]
org.aopalliance (1.0.0.v201105210816) "Aopalliance Plug-in" [Resolved]
org.apache.ant (1.9.6.v201510161327) "Apache Ant" [Resolved]
org.apache.axis (1.4.0.v201411182030) "Apache Web Services" [Resolved]
org.apache.batik.css (1.7.0.v201011041433) "Apache Batik CSS" [Resolved]
org.apache.batik.util (1.7.0.v201011041433) "Apache Batik Utilities" [Resolved]
org.apache.batik.util.gui (1.7.0.v200903091627) "Apache Batik GUI Utilities" [Resolved]
org.apache.bcel (5.2.0.v201005080400) "Apache BCEL" [Resolved]
org.apache.commons.codec (1.6.0.v201305230611) "Apache Commons Codec Plug-in" [Resolved]
org.apache.commons.collections (3.2.2.v201511171945) "Apache Commons Collections" [Resolved]
org.apache.commons.compress (1.6.0.v201310281400) "Apache Commons Compress" [Resolved]
org.apache.commons.discovery (0.2.0.v201004190315) "Jakarta-Commons Discovery" [Resolved]
org.apache.commons.httpclient (3.1.0.v201012070820) "Apache Commons Httpclient" [Resolved]
org.apache.commons.io (2.2.0.v201405211200) "Apache Commons IO" [Resolved]
org.apache.commons.jxpath (1.3.0.v200911051830) "Apache Commons JXPath" [Resolved]
org.apache.commons.lang (2.6.0.v201404270220) "Apache Commons Lang" [Resolved]
org.apache.commons.lang3 (3.1.0.v201403281430) "Apache Commons Lang" [Resolved]
org.apache.commons.logging (1.1.1.v201101211721) "Apache Commons Logging Plug-in" [Resolved]
org.apache.commons.logging (1.0.4.v201101211617) "Apache Commons Logging Plug-in" [Resolved]
org.apache.commons.math (2.1.0.v201105210652) "Apache Commons Math" [Resolved]
org.apache.commons.net (3.2.0.v201305141515) "Apache Commons Net" [Resolved]
org.apache.commons.pool (1.6.0.v201204271246) "Apache Commons Pool" [Resolved]
org.apache.felix.gogo.command (0.10.0.v201209301215) "Apache Felix Gogo Command" [Active]
org.apache.felix.gogo.runtime (0.10.0.v201209301036) "Apache Felix Gogo Runtime" [Active]
org.apache.felix.gogo.shell (0.10.0.v201212101605) "Apache Felix Gogo Shell" [Active]
org.apache.httpcomponents.httpclient (4.3.6.v201511171540) "Apache HttpComponents HttpClient" [Resolved]
org.apache.httpcomponents.httpcore (4.3.3.v201411290715) "Apache HttpComponents Httpcore" [Resolved]
org.apache.jasper.glassfish (2.2.2.v201501141630) "JSP 2.2 implementation from Glassfish" [Resolved]
org.apache.log4j (1.2.15.v201012070815) "Apache Jakarta log4j Plug-in" [Resolved]
org.apache.lucene.analysis (3.5.0.v20120725-1805) "Apache Lucene Analysis" [Resolved]
org.apache.lucene.core (3.5.0.v20120725-1805) "Apache Lucene Core" [Resolved]
org.apache.solr.client.solrj (3.5.0.v20150506-0844) "Apache Solr Java Client" [Resolved]
org.apache.velocity (1.5.0.v200905192330) "Apache Velocity Plug-in" [Resolved]
org.apache.ws.commons.util (1.0.1.v20100518-1140) "WS Commons Util Plug-in" [Resolved]
org.apache.wsil4j (1.0.0.v200901211807) "WSIL4J" [Resolved]
org.apache.xalan (2.7.1.v201005080400) "Xalan-Java" [Resolved]
org.apache.xerces (2.9.0.v201101211617) "Apache Xerces-J" [Resolved]
org.apache.xml.resolver (1.2.0.v201005080400) "Apache XmlResolver" [Resolved]
org.apache.xml.serializer (2.7.1.v201005080400) "Apache XML Commons Serializer" [Resolved]
org.apache.xmlrpc (3.0.0.v20100427-1100) "Apache XML-RPC Plug-in" [Resolved]
org.aspectj.runtime (1.8.10.201703272045) "AspectJ Runtime" [Resolved]
org.aspectj.weaver (1.8.10.201703272045) "AspectJ Weaver" [Resolved]
org.codehaus.jackson.core (1.6.0.v20101005-0925) "Jackson JSON processor" [Resolved]
org.codehaus.jackson.mapper (1.6.0.v20101005-0925) "Data mapper for Jackson JSON processor" [Resolved]
org.dadacoalition.yedit (1.0.18.201602092025-RELEASE-SIGNED) "YEdit YAML editor" [Starting]
org.eclipse.aether.api (1.0.1.v20141111) "Aether API" [Resolved]
org.eclipse.aether.connector.basic (1.0.1.v20141111) "Aether Connector Basic" [Resolved]
org.eclipse.aether.impl (1.0.1.v20141111) "Aether Implementation" [Resolved]
org.eclipse.aether.maven (3.1.0.v20140706-2237) "Maven Aether Provider Bundle" [Resolved]
org.eclipse.aether.spi (1.0.1.v20141111) "Aether SPI" [Resolved]
org.eclipse.aether.transport.file (1.0.1.v20141111) "Aether Transport File" [Resolved]
org.eclipse.aether.transport.http (1.0.1.v20141111) "Aether Transport HTTP" [Resolved]
org.eclipse.aether.util (1.0.1.v20141111) "Aether Utilities" [Resolved]
org.eclipse.ant.core (3.4.100.v20160505-0642) "Ant Build Tool Core" [Starting]
org.eclipse.ant.launching (1.1.201.v20161115-1135) "Ant Launching Support" [Starting]
org.eclipse.ant.ui (3.6.201.v20161115-1135) "Ant UI" [Starting]
org.eclipse.cdt.core.macosx (5.3.0.201703062208) "C/C++ Development Tools Core Native Utilities for MacOS X" [Resolved]
org.eclipse.cdt.core.native (5.10.0.201703062208) "C/C++ Development Tools Core Native Utilities" [Starting]
org.eclipse.cft.server.branding.core (1.0.2.v201703012110) "Cloud Foundry Tools" [Starting]
org.eclipse.cft.server.branding.ui (1.0.2.v201703012110) "Cloud Foundry Tools" [Starting]
org.eclipse.cft.server.core (1.2.1.v201703012110) "Cloud Foundry Tools (Core)" [Starting]
org.eclipse.cft.server.rse (1.0.1.v201703012110) "Cloud Foundry Tools (RSE)" [Starting]
org.eclipse.cft.server.standalone.core (1.0.4.v201703012110) "Cloud Foundry Tools (Standalone Core)" [Starting]
org.eclipse.cft.server.standalone.ui (1.0.4.v201703012110) "Cloud Foundry Tools (Standalone UI)" [Starting]
org.eclipse.cft.server.ui (1.0.108.v201703012110) "Cloud Foundry Tools (UI)" [Starting]
org.eclipse.cft.server.verify.ui (1.0.1.v201703012110) "Cloud Foundry Tools (Verify UI)" [Active]
org.eclipse.compare (3.7.1.v20170103-1805) "Compare Support" [Active]
org.eclipse.compare.core (3.6.0.v20160418-1534) "Core Compare Support" [Active]
org.eclipse.core.commands (3.8.1.v20161221-1651) "Commands" [Resolved]
org.eclipse.core.contenttype (3.5.100.v20160418-1621) "Eclipse Content Mechanism" [Active]
org.eclipse.core.databinding (1.6.0.v20160412-0910) "JFace Data Binding" [Starting]
org.eclipse.core.databinding.beans (1.3.100.v20160509-1025) "JFace Data Binding for JavaBeans" [Resolved]
org.eclipse.core.databinding.observable (1.6.0.v20160511-1747) "JFace Data Binding Observables" [Resolved]
org.eclipse.core.databinding.property (1.6.0.v20160427-0852) "JFace Data Binding Properties" [Starting]
org.eclipse.core.expressions (3.5.100.v20160418-1621) "Expression Language" [Active]
org.eclipse.core.externaltools (1.0.400.v20160509-1057) "External Tools Headless Support" [Starting]
org.eclipse.core.filebuffers (3.6.0.v20160503-1849) "File Buffers" [Active]
org.eclipse.core.filesystem (1.6.1.v20161113-2349) "Core File Systems" [Active]
org.eclipse.core.filesystem.macosx (1.3.0.v20140124-1940) "Core File System for Macintosh" [Resolved]
org.eclipse.core.jobs (3.8.0.v20160509-0411) "Eclipse Jobs Mechanism" [Active]
org.eclipse.core.net (1.3.0.v20160418-1534) "Internet Connection Management" [Active]
org.eclipse.core.resources (3.11.1.v20161107-2032) "Core Resource Management" [Active]
org.eclipse.core.runtime (3.12.0.v20160606-1342) "Core Runtime" [Active]
org.eclipse.core.variables (3.3.0.v20160419-1720) "Core Variables" [Starting]
org.eclipse.datatools.common.doc.user (1.7.0.20090521092446) "Data Tools Platform User Documentation" [Starting]
org.eclipse.datatools.connectivity (1.13.0.201603142002) "Data Tools Platform Connectivity Plug-in" [Starting]
org.eclipse.datatools.connectivity.apache.derby (1.1.0.201603142002) "Eclipse Data Tools Platform Derby Plug-in" [Starting]
org.eclipse.datatools.connectivity.apache.derby.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform Apache Derby Database Definition" [Starting]
org.eclipse.datatools.connectivity.apache.derby.ui (1.1.0.201603142002) "Eclipse Data Tools Platform Apache Derby UI Plug-in" [Starting]
org.eclipse.datatools.connectivity.console.profile (1.1.0.201603142002) "DTP Connection Profiles Storage File Editor Plug-in" [Starting]
org.eclipse.datatools.connectivity.db.generic (1.1.0.201603142002) "Eclipse Data Tools Platform Generic DB Connectivity Plug-in" [Starting]
org.eclipse.datatools.connectivity.db.generic.ui (1.1.0.201603142002) "Eclipse Data Tools Platform Generic DB UI Plug-in" [Starting]
org.eclipse.datatools.connectivity.dbdefinition.genericJDBC (1.1.0.201603142002) "Eclipse Data Tools Platform DBDefinition Generic JDBC Plug-in" [Starting]
org.eclipse.datatools.connectivity.doc.user (1.7.0.20090521092446) "Data Tools Platform Connectivity User Documentation" [Starting]
org.eclipse.datatools.connectivity.doc.user.contexts (1.7.0.20090521092446) "Data Tools Platform Connectivity User Documentation for context-sensitive help" [Starting]
org.eclipse.datatools.connectivity.oda (3.5.0.201603142002) "DTP Open Data Access" [Starting]
org.eclipse.datatools.connectivity.oda.consumer (3.3.0.201603142002) "DTP ODA Consumer Helper Component Plug-in" [Starting]
org.eclipse.datatools.connectivity.oda.design (3.4.0.201603142002) "DTP ODA Design Session Model" [Starting]
org.eclipse.datatools.connectivity.oda.design.ui (3.3.0.201603142002) "DTP ODA Designer UI Framework Plug-in" [Starting]
org.eclipse.datatools.connectivity.oda.flatfile (3.2.0.201603142002) "Eclipse Data Tools Platform Flat File ODA Runtime Driver" [Starting]
org.eclipse.datatools.connectivity.oda.flatfile.ui (3.2.0.201603142002) "Eclipse Data Tools Platform Flat File ODA Designer" [Starting]
org.eclipse.datatools.connectivity.oda.profile (3.3.0.201603142002) "DTP ODA Connection Profile Framework Plug-in" [Starting]
org.eclipse.datatools.connectivity.oda.template.ui (3.3.0.201603142002) "DTP ODA New Plug-in Template Wizard" [Starting]
org.eclipse.datatools.connectivity.sqm.core (1.3.0.201603142002) "Eclipse Data Tools Platform SQM Core Plug-in" [Starting]
org.eclipse.datatools.connectivity.sqm.core.ui (1.3.0.201603142002) "Eclipse Data Tools Platform SQM UI Plug-in" [Starting]
org.eclipse.datatools.connectivity.sqm.server.ui (1.2.0.201603142002) "Eclipse Data Tools Platform Server UI Plug-in" [Starting]
org.eclipse.datatools.connectivity.ui (1.3.0.201603142002) "Data Tools Platform Connectivity UI Plug-in" [Starting]
org.eclipse.datatools.connectivity.ui.dse (1.2.0.201603142002) "Eclipse Data Tools Platform Data Source Explorer Plug-in" [Starting]
org.eclipse.datatools.doc.user (1.7.0.20090521092446) "Data Tool Platform User Documentation" [Starting]
org.eclipse.datatools.enablement.finfo (1.6.0.201603142002) "Eclipse Data Tools Platform Enablement" [Starting]
org.eclipse.datatools.enablement.hsqldb (1.1.0.201603142002) "Eclipse Data Tools Platform HSQLDB Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.hsqldb.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform HSQLDB Database Definition Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.hsqldb.ui (1.1.0.201603142002) "Eclipse Data Tools Platform HSQLDB UI Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm (1.1.0.201603142002) "pluginName" [Starting]
org.eclipse.datatools.enablement.ibm.db2 (1.1.0.201603142002) "pluginName" [Starting]
org.eclipse.datatools.enablement.ibm.db2.iseries (1.1.0.201603142002) "Eclipse Data Tools Platform IBM DB2 UDB iSeries Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.iseries.dbdefinition (1.1.0.201603142002) "DB2 UDB iSeries Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.iseries.ui (1.1.0.201603142002) "Eclipse Data Tools Platform IBM DB2 UDB UI iSeries Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.luw (1.1.0.201603142002) "Eclipse Data Tools Platform IBM DB2 UDB LUW Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.luw.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform DB2 UDB Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.luw.ui (1.1.0.201603142002) "Eclipse Data Tools Platform IBM DB2 UDB LUW UI Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.zseries (1.1.0.201603142002) "Eclipse Data Tools Platform IBM DB2 UDB zSeries Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.zseries.dbdefinition (1.1.0.201603142002) "DB2 UDB Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.db2.zseries.ui (1.1.0.201603142002) "Eclipse Data Tools Platform IBM DB2 UDB zSeries UI Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.informix (1.1.0.201603142002) "Eclipse Data Tools Platform Informix Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.informix.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform Informix Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.informix.ui (1.1.0.201603142002) "Eclipse Data Tools Platform Informix UI Plug-in" [Starting]
org.eclipse.datatools.enablement.ibm.ui (1.1.0.201603142002) "Eclipse Data Tools Platform IBM UI Plug-in" [Starting]
org.eclipse.datatools.enablement.ingres (1.1.0.201603142002) "Ingres DTP Plug-in" [Starting]
org.eclipse.datatools.enablement.ingres.dbdefinition (1.1.0.201603142002) "Ingres DTP Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.ingres.ui (1.1.0.201603142002) "Ingres DTP UI Plug-in" [Starting]
org.eclipse.datatools.enablement.jdt.classpath (1.1.0.201603142002) "Data Tools Platform Connectivity JDT Extension Plug-in" [Starting]
org.eclipse.datatools.enablement.msft.sqlserver (1.1.0.201603142002) "Eclipse Data Tools Platform Microsoft SQL Server Plug-in" [Starting]
org.eclipse.datatools.enablement.msft.sqlserver.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Server Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.msft.sqlserver.ui (1.1.0.201603142002) "Eclipse Data Tools Platform Microsoft SQL Server UI Plug-in" [Starting]
org.eclipse.datatools.enablement.mysql (1.1.0.201603142002) "Eclipse Data Tools Platform MySQL Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.mysql.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform MySQL Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.mysql.ui (1.1.0.201603142002) "Eclipse Data Tools Platform MySQL UI Plug-in" [Starting]
org.eclipse.datatools.enablement.oda.ws (1.3.0.201603142002) "Eclipse Data Tools Platform Web Services ODA Runtime Driver" [Starting]
org.eclipse.datatools.enablement.oda.ws.ui (1.3.0.201603142002) "Eclipse Data Tools Platform Web Services ODA Designer" [Starting]
org.eclipse.datatools.enablement.oda.xml (1.3.0.201603142002) "Eclipse Data Tools Platform XML ODA Runtime Driver" [Starting]
org.eclipse.datatools.enablement.oda.xml.ui (1.3.0.201603142002) "Eclipse Data Tools Platform XML ODA Designer" [Starting]
org.eclipse.datatools.enablement.oracle (1.1.0.201603142002) "Eclipse Data Tools Platform Oracle Plug-in" [Starting]
org.eclipse.datatools.enablement.oracle.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform Oracle Database Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.oracle.ui (1.1.0.201603142002) "Eclipse Data Tools Platform Oracle UI Plug-in" [Starting]
org.eclipse.datatools.enablement.postgresql (1.2.0.201603142002) "PostgreSQL Connection Profile and Driver Template Plug-in" [Starting]
org.eclipse.datatools.enablement.postgresql.dbdefinition (1.1.0.201603142002) "PostgreSQL DB Definition" [Starting]
org.eclipse.datatools.enablement.postgresql.ui (1.1.0.201603142002) "PostgreSQL Connection Profile and Driver Template UI Plug-in" [Starting]
org.eclipse.datatools.enablement.sap.maxdb (1.1.0.201603142002) "Eclipse Data Tools Platform MaxDB Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.sap.maxdb.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform MaxDB Definition Plug-in" [Starting]
org.eclipse.datatools.enablement.sap.maxdb.ui (1.1.0.201603142002) "Eclipse Data Tools Platform MaxDB UI Plug-in" [Starting]
org.eclipse.datatools.enablement.sqlite (1.1.0.201603142002) "Eclipse Data Tools Platform SQLite Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.sqlite.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform SQLite Database Definition Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.sqlite.ui (1.1.0.201603142002) "Eclipse Data Tools Platform SQLite UI Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase (1.1.0.201603142002) "High-level Sybase Enablement Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase.asa (1.1.0.201603142002) "Sybase ASA Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase.asa.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform Sybase ASA Database Definition" [Starting]
org.eclipse.datatools.enablement.sybase.asa.models (1.1.0.201603142002) "Sybase ASA SQL Model" [Starting]
org.eclipse.datatools.enablement.sybase.asa.schemaobjecteditor.examples (2.6.0.200810071) "Sybase ASA Schema Object Editor" [Starting]
org.eclipse.datatools.enablement.sybase.asa.ui (1.1.0.201603142002) "Sybase ASA Connection Profile UI Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase.ase (1.1.0.201603142002) "JDBC/Sybase ASE Connection Profile Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase.ase.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform Sybase ASE Database Definition" [Starting]
org.eclipse.datatools.enablement.sybase.ase.models (1.1.0.201603142002) "Sybase ASE Model Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase.ase.ui (1.1.0.201603142002) "ASE Enablement UI Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase.models (1.1.0.201603142002) "Sybase Model Plug-in" [Starting]
org.eclipse.datatools.enablement.sybase.ui (1.1.0.201603142002) "Sybase UI Plug-in" [Starting]
org.eclipse.datatools.help (1.6.0.201603142002) "Data Tools Platform Help Utilities" [Resolved]
org.eclipse.datatools.intro (1.7.0.v201005281800) "Eclipse Data Tools Platform Intro Plug-in" [Resolved]
org.eclipse.datatools.modelbase.dbdefinition (1.1.0.201603142002) "Eclipse Data Tools Platform DBDefinition Model" [Starting]
org.eclipse.datatools.modelbase.derby (1.1.0.201603142002) "Eclipse Data Tools Platform Derby Model Plug-in" [Starting]
org.eclipse.datatools.modelbase.sql (1.1.0.201603142002) "Eclipse Data Tools Platform SQLModel Plug-in" [Starting]
org.eclipse.datatools.modelbase.sql.edit (1.1.0.201603142002) "Eclipse Data Tools Platform SQLModel Edit Plug-in" [Starting]
org.eclipse.datatools.modelbase.sql.query (1.2.0.201603142002) "Eclipse Data Tools Platform SQL Query Model Plugin" [Starting]
org.eclipse.datatools.modelbase.sql.query.edit (1.1.0.201603142002) "SQL Query Edit Support Plugin" [Starting]
org.eclipse.datatools.modelbase.sql.xml.query (1.1.0.201603142002) "Eclipse Data Tools Platform SQL XML Query Model Plugin" [Starting]
org.eclipse.datatools.oda.cshelp (1.2.0.201603142002) "DTP ODA Context-sensitive Help" [Starting]
org.eclipse.datatools.sqltools.common.ui (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Tools Common UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.data.core (1.3.0.201603142002) "Data Core Plugin" [Starting]
org.eclipse.datatools.sqltools.data.ui (1.3.0.201603142002) "Data UI Plugin" [Starting]
org.eclipse.datatools.sqltools.db.derby (1.1.0.201603142002) "Eclipse Data Tools Platform Derby SQL Tools Plug-in" [Starting]
org.eclipse.datatools.sqltools.db.derby.ui (1.1.0.201603142002) "Eclipse Data Tools Platform Derby SQL Tools UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.db.generic (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Tools Generic Database Plug-in" [Starting]
org.eclipse.datatools.sqltools.db.generic.ui (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Tools Generic Database UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.ddlgen.ui (1.1.0.201603142002) "Eclipse Data Tools Platform FE UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.debugger.core (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Debugger Framework" [Starting]
org.eclipse.datatools.sqltools.debugger.core.ui (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Debugger UI Framework" [Starting]
org.eclipse.datatools.sqltools.doc.user (1.7.0.20090521092446) "Data Tools Platform SQL Tools User Documentation" [Starting]
org.eclipse.datatools.sqltools.doc.user.contexts (1.7.0.20090521092446) "Data Tools Platform SQL Tools User Documentation for context-sensitive help" [Starting]
org.eclipse.datatools.sqltools.editor.core (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Editor Core Plug-in" [Starting]
org.eclipse.datatools.sqltools.editor.core.ui (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Editor Core UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.parsers.sql (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Parser Plugin" [Starting]
org.eclipse.datatools.sqltools.parsers.sql.lexer (1.1.0.201603142002) "Eclipse Data Tools Platform Lexer Plug-in" [Starting]
org.eclipse.datatools.sqltools.parsers.sql.query (1.3.0.201603142002) "Eclipse Data Tools Platform SQL Query Parser Plugin" [Starting]
org.eclipse.datatools.sqltools.parsers.sql.xml.query (1.1.0.201603142002) "Eclipse Data Tools Platform SQL XML Query Parser Plugin" [Starting]
org.eclipse.datatools.sqltools.plan (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Execution Plan View Plug-in" [Starting]
org.eclipse.datatools.sqltools.result (1.2.0.201603142002) "Eclipse Data Tools Platform SQL Results View Plug-ins" [Starting]
org.eclipse.datatools.sqltools.result.ui (1.2.0.201603142002) "Eclipse Data Tools Platform SQL Results View UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.routineeditor (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Tools Routine Editor Plug-in" [Starting]
org.eclipse.datatools.sqltools.routineeditor.ui (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Tools Routine Editor UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.schemaobjecteditor (1.2.0.201603142002) "Schema Object Editor Plug-in" [Starting]
org.eclipse.datatools.sqltools.schemaobjecteditor.ui (1.2.0.200810071) "Schema Object Editor Framework" [Starting]
org.eclipse.datatools.sqltools.schemaobjecteditor.ui.pages (1.2.0.200810071) "Schema Object Editor Pages Plug-in" [Starting]
org.eclipse.datatools.sqltools.sql (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Core Plug-in" [Starting]
org.eclipse.datatools.sqltools.sql.ui (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Core UI Plug-in" [Starting]
org.eclipse.datatools.sqltools.sqlbuilder (1.1.0.201603142002) "SQL Builder" [Starting]
org.eclipse.datatools.sqltools.sqleditor (1.1.0.201603142002) "Eclipse Data Tools Platform SQL Editor" [Starting]
org.eclipse.datatools.sqltools.sqlscrapbook (1.1.0.201603142002) "Eclipse Data Tools Platform Sqlscrapbook Plug-in" [Starting]
org.eclipse.datatools.sqltools.tabledataeditor (1.1.0.201603142002) "Eclipse Data Tools Platform Table Data Editor Plug-in" [Starting]
org.eclipse.debug.core (3.10.100.v20160419-1720) "Debug Core" [Active]
org.eclipse.debug.ui (3.11.202.v20161114-0338) "Debug UI" [Starting]
org.eclipse.draw2d (3.10.100.201606061308) "Draw2d" [Starting]
org.eclipse.dstore.core (3.4.0.201501311530) "RSE DStore Core" [Starting]
org.eclipse.dstore.extra (2.1.400.201403100950) "RSE DStore Platform Support" [Starting]
org.eclipse.e4.core.commands (0.11.100.v20160506-0804) "Eclipse e4 core commands" [Resolved]
org.eclipse.e4.core.contexts (1.5.1.v20170203-1100) "Eclipse Contexts" [Active]
org.eclipse.e4.core.di (1.6.1.v20160712-0927) "Eclipse Dependency Injection" [Active]
org.eclipse.e4.core.di.annotations (1.5.0.v20151127-1241) "Eclipse Dependency Injection Annotations" [Resolved]
org.eclipse.e4.core.di.extensions (0.14.0.v20160211-1614) "Eclipse Dependency Injection Extensions" [Active]
org.eclipse.e4.core.services (2.0.100.v20160509-1032) "Eclipse Application Services" [Active]
org.eclipse.e4.emf.xpath (0.1.200.v20160506-0804) "Eclipse Model Xpath" [Resolved]
org.eclipse.e4.ui.bindings (0.11.100.v20160509-1025) "Eclipse Bindings Support" [Active]
org.eclipse.e4.ui.css.core (0.12.1.v20161114-0210) "Eclipse CSS Core Support" [Resolved]
org.eclipse.e4.ui.css.swt (0.12.100.v20160517-1505) "Eclipse CSS SWT Support" [Active]
org.eclipse.e4.ui.css.swt.theme (0.10.100.v20160523-0836) "Eclipse CSS SWT Theme Support" [Active]
org.eclipse.e4.ui.di (1.1.100.v20160506-0759) "Eclipse UI Dependency Injection" [Active]
org.eclipse.e4.ui.dialogs (1.1.0.v20151127-1218) "Eclipse e4 dialogs" [Resolved]
org.eclipse.e4.ui.model.workbench (1.2.0.v20160229-1459) "Eclipse Workbench Model" [Active]
org.eclipse.e4.ui.services (1.2.100.v20160506-0759) "Eclipse UI Application Services" [Active]
org.eclipse.e4.ui.widgets (1.1.100.v20160506-0759) "Eclipse UI Custom widgets" [Resolved]
org.eclipse.e4.ui.workbench (1.4.0.v20160517-1624) "Eclipse e4 Workbench" [Active]
org.eclipse.e4.ui.workbench.addons.swt (1.2.101.v20170206-1129) "Eclipse e4 Workbench Add-ons" [Active]
org.eclipse.e4.ui.workbench.renderers.swt (0.14.1.v20170117-1415) "Eclipse e4 Workbench SWT Renderer" [Active]
org.eclipse.e4.ui.workbench.renderers.swt.cocoa (0.11.300.v20160330-1418) "Eclipse UI MacOS X Enhancements" [Resolved]
org.eclipse.e4.ui.workbench.swt (0.14.1.v20160829-0832) "Eclipse e4 Workbench SWT" [Active]
org.eclipse.e4.ui.workbench3 (0.13.100.v20160506-0759) "Bundle for Workbench APIs available in e4" [Resolved]
org.eclipse.ecf (3.8.0.v20160823-2221) "ECF Core API" [Active]
org.eclipse.ecf.filetransfer (5.0.0.v20160823-2221) "ECF Filetransfer API" [Active]
org.eclipse.ecf.identity (3.7.0.v20160823-2221) "ECF Identity Core API" [Active]
org.eclipse.ecf.provider.filetransfer (3.2.200.v20160823-2221) "ECF Filetransfer Provider" [Active]
org.eclipse.ecf.provider.filetransfer.httpclient4 (1.1.100.v20160823-2221) "ECF HttpComponents Filetransfer Provider" [Active]
org.eclipse.ecf.provider.filetransfer.httpclient4.ssl (1.1.0.v20160823-2221) "ECF HttpComponents Filetransfer Provider" [Resolved]
org.eclipse.ecf.provider.filetransfer.ssl (1.0.0.v20160823-2221) "ECF Filetransfer Provider" [Resolved]
org.eclipse.ecf.ssl (1.2.0.v20160823-2221) "ECF Core API" [Resolved]
org.eclipse.egit (4.6.1.201703071140-r) "Git integration for Eclipse" [Starting]
org.eclipse.egit.core (4.6.1.201703071140-r) "Git integration for Eclipse - Core" [Active]
org.eclipse.egit.doc (4.6.1.201703071140-r) "Git integration for Eclipse - Documentation" [Starting]
org.eclipse.egit.mylyn.ui (4.6.1.201703071140-r) "EGit Mylyn UI" [Starting]
org.eclipse.egit.ui (4.6.1.201703071140-r) "Git integration for Eclipse - UI" [Active]
org.eclipse.emf (2.6.0.v20160526-0356) "EMF - Eclipse Modeling Framework Runtime and Tools" [Starting]
org.eclipse.emf.ant (2.8.0.v20160526-0356) "EMF Ant Tasks" [Starting]
org.eclipse.emf.codegen (2.11.0.v20160526-0356) "EMF Code Generation" [Starting]
org.eclipse.emf.codegen.ecore (2.12.0.v20160526-0356) "EMF Ecore Code Generator" [Starting]
org.eclipse.emf.codegen.ecore.ui (2.12.0.v20160526-0356) "EMF Ecore Code Generator UI" [Starting]
org.eclipse.emf.codegen.ui (2.6.0.v20160526-0356) "EMF Code Generation UI" [Starting]
org.eclipse.emf.common (2.12.0.v20160420-0247) "EMF Common" [Active]
org.eclipse.emf.common.ui (2.11.0.v20160526-0356) "EMF Common UI" [Active]
org.eclipse.emf.converter (2.7.0.v20160526-0356) "EMF Model Converter" [Starting]
org.eclipse.emf.databinding (1.3.0.v20160526-0356) "EMF Data Binding" [Starting]
org.eclipse.emf.databinding.edit (1.3.0.v20160526-0356) "EMF Edit Data Binding" [Starting]
org.eclipse.emf.ecore (2.12.0.v20160420-0247) "EMF Ecore" [Active]
org.eclipse.emf.ecore.change (2.11.0.v20160420-0247) "EMF Change Model" [Starting]
org.eclipse.emf.ecore.change.edit (2.6.0.v20160526-0356) "EMF Change Edit" [Starting]
org.eclipse.emf.ecore.edit (2.9.0.v20160526-0356) "EMF Ecore Edit" [Starting]
org.eclipse.emf.ecore.editor (2.12.0.v20160526-0356) "EMF Sample Ecore Editor" [Starting]
org.eclipse.emf.ecore.xmi (2.12.0.v20160420-0247) "EMF XML/XMI Persistence" [Active]
org.eclipse.emf.edit (2.12.0.v20160526-0356) "EMF Edit" [Active]
org.eclipse.emf.edit.ui (2.12.0.v20160526-0356) "EMF Edit UI" [Active]
org.eclipse.emf.exporter (2.7.0.v20160526-0356) "EMF Model Exporter" [Starting]
org.eclipse.emf.importer (2.9.0.v20160526-0356) "EMF Model Importer" [Starting]
org.eclipse.emf.importer.ecore (2.8.0.v20160526-0356) "EMF Ecore Importer" [Starting]
org.eclipse.emf.importer.java (2.7.0.v20160526-0356) "EMF Annotated Java Importer" [Starting]
org.eclipse.emf.importer.rose (2.8.0.v20160526-0356) "EMF Rose Importer" [Starting]
org.eclipse.emf.mapping (2.9.0.v20160526-0356) "EMF Mapping" [Starting]
org.eclipse.emf.mapping.ecore (2.6.0.v20160526-0356) "EMF Ecore Mapping" [Starting]
org.eclipse.emf.mapping.ecore.editor (2.6.0.v20160526-0356) "EMF Ecore Mapping Editor" [Starting]
org.eclipse.emf.mapping.ecore2ecore (2.9.0.v20160526-0356) "EMF Ecore to Ecore Mapping" [Starting]
org.eclipse.emf.mapping.ecore2ecore.editor (2.7.0.v20160526-0356) "EMF Ecore to Ecore Mapping Editor" [Starting]
org.eclipse.emf.mapping.ecore2xml (2.9.0.v20160526-0356) "EMF Ecore to XML Mapping" [Starting]
org.eclipse.emf.mapping.ecore2xml.ui (2.8.0.v20160526-0356) "EMF Ecore to XML Mapping Editor" [Starting]
org.eclipse.emf.mapping.ui (2.7.0.v20160526-0356) "EMF Mapping UI" [Starting]
org.eclipse.epp.logging.aeri.core (2.0.4.v20170307-1435) "Eclipse Automated Error Reporting" [Active]
org.eclipse.epp.logging.aeri.ide (2.0.4.v20170307-1435) "Eclipse Automated Error Reporting" [Resolved]
org.eclipse.epp.mpc.core (1.5.4.v20170222-1921) "Marketplace Client Core" [Active]
org.eclipse.epp.mpc.help.ui (1.5.4.v20170201-1845) "Marketplace Client Help" [Resolved]
org.eclipse.epp.mpc.ui (1.5.4.v20170222-1941) "Marketplace Client" [Active]
org.eclipse.epp.package.jee (4.6.3.20170314-1500) "Bundle-Name" [Resolved]
org.eclipse.equinox.app (1.3.400.v20150715-1528) "Equinox Application Container" [Active]
org.eclipse.equinox.bidi (1.0.0.v20160307-1318) "Bidirectional Text Support" [Starting]
org.eclipse.equinox.common (3.8.0.v20160509-1230) "Common Eclipse Runtime" [Active]
org.eclipse.equinox.concurrent (1.1.0.v20130327-1442) "Equinox Concurrent API" [Starting]
org.eclipse.equinox.console (1.1.200.v20150929-1405) "Console plug-in" [Active]
org.eclipse.equinox.ds (1.4.400.v20160226-2036) "Declarative Services" [Active]
org.eclipse.equinox.event (1.3.200.v20160324-1850) "Event Admin" [Active]
org.eclipse.equinox.frameworkadmin (2.0.300.v20160504-1450) "Equinox Framework Admin" [Starting]
org.eclipse.equinox.frameworkadmin.equinox (1.0.700.v20160102-2223) "Equinox Framework Admin for Equinox" [Starting]
org.eclipse.equinox.http.jetty (3.3.0.v20160324-1850) "Jetty Http Service" [Starting]
org.eclipse.equinox.http.registry (1.1.400.v20150715-1528) "Http Service Registry Extensions" [Resolved]
org.eclipse.equinox.http.servlet (1.3.1.v20160808-1329) "Http Services Servlet" [Starting]
org.eclipse.equinox.jsp.jasper (1.0.500.v20150119-1358) "Jasper Jsp Support Bundle" [Starting]
org.eclipse.equinox.jsp.jasper.registry (1.0.300.v20130327-1442) "Jasper Jsp Registry Support Plug-in" [Starting]
org.eclipse.equinox.launcher (1.3.201.v20161025-1711) "Equinox Launcher" [Resolved]
org.eclipse.equinox.launcher.cocoa.macosx.x86_64 (1.1.401.v20161122-1740) "Equinox Launcher MacOSX Cocoa Fragment" [Resolved]
org.eclipse.equinox.p2.artifact.repository (1.1.500.v20160419-0834) "Equinox Provisioning Artifact Repository Support" [Active]
org.eclipse.equinox.p2.console (1.0.500.v20160504-1450) "Equinox Provisioning Console" [Starting]
org.eclipse.equinox.p2.core (2.4.100.v20160419-0834) "Equinox Provisioning Core" [Active]
org.eclipse.equinox.p2.director (2.3.300.v20160504-1450) "Equinox Provisioning Director" [Active]
org.eclipse.equinox.p2.director.app (1.0.500.v20160419-0834) "Equinox Provisioning Director Application" [Starting]
org.eclipse.equinox.p2.directorywatcher (1.1.100.v20150423-1455) "Equinox Provisioning Directory Watcher" [Active]
org.eclipse.equinox.p2.discovery (1.0.400.v20160504-1450) "Equinox Provisioning Discovery" [Resolved]
org.eclipse.equinox.p2.discovery.compatibility (1.0.200.v20131211-1531) "Equinox Provisioning Discovery" [Starting]
org.eclipse.equinox.p2.engine (2.4.100.v20160419-0834) "Equinox Provisioning Engine" [Active]
org.eclipse.equinox.p2.extensionlocation (1.2.300.v20160419-0834) "Equinox Provisioning Extension Location Repository Support" [Active]
org.eclipse.equinox.p2.garbagecollector (1.0.300.v20160504-1450) "Equinox Provisioning Garbage Collector" [Starting]
org.eclipse.equinox.p2.jarprocessor (1.0.500.v20160504-1450) "Equinox Provisioning JAR Processor" [Resolved]
org.eclipse.equinox.p2.metadata (2.3.100.v20160427-2220) "Equinox Provisioning Metadata" [Active]
org.eclipse.equinox.p2.metadata.repository (1.2.300.v20160419-0834) "Equinox Provisioning Metadata Repository" [Active]
org.eclipse.equinox.p2.operations (2.4.200.v20160504-1450) "Equinox Provisioning Operations API" [Active]
org.eclipse.equinox.p2.publisher (1.4.100.v20160504-1450) "Equinox Provisioning Publisher Infrastructure" [Active]
org.eclipse.equinox.p2.publisher.eclipse (1.2.100.v20160504-1450) "Equinox Provisioning Publisher for Eclipse" [Starting]
org.eclipse.equinox.p2.reconciler.dropins (1.1.400.v20160504-1450) "Equinox Provisioning Drop-in" [Active]
org.eclipse.equinox.p2.repository (2.3.200.v20160421-0324) "Equinox Provisioning Repository" [Active]
org.eclipse.equinox.p2.repository.tools (2.1.300.v20160421-0324) "Equinox Provisioning Repository Tools" [Starting]
org.eclipse.equinox.p2.touchpoint.eclipse (2.1.400.v20160419-0834) "Equinox Provisioning Eclipse Touchpoint" [Active]
org.eclipse.equinox.p2.touchpoint.natives (1.2.100.v20160419-0834) "Equinox Provisioning Native Touchpoint" [Starting]
org.eclipse.equinox.p2.transport.ecf (1.1.201.v20161115-1927) "Equinox Provisioning ECF based Transport" [Active]
org.eclipse.equinox.p2.ui (2.4.100.v20160419-0834) "Equinox Provisioning UI Support" [Active]
org.eclipse.equinox.p2.ui.discovery (1.0.201.v20160901-1335) "Equinox Provisioning Discovery UI" [Resolved]
org.eclipse.equinox.p2.ui.importexport (1.1.200.v20160521-1138) "Equinox Provisioning Import and Export" [Starting]
org.eclipse.equinox.p2.ui.sdk (1.0.400.v20150423-1455) "Equinox Provisioning Platform Update Support" [Active]
org.eclipse.equinox.p2.ui.sdk.scheduler (1.3.0.v20161124-1529) "Equinox Provisioning Platform Automatic Update Support" [Active]
org.eclipse.equinox.p2.updatechecker (1.1.300.v20161124-1529) "Equinox Provisioning Update Checker" [Active]
org.eclipse.equinox.p2.updatesite (1.0.600.v20160504-1450) "Equinox Provisioning Legacy Update Site Support" [Starting]
org.eclipse.equinox.preferences (3.6.1.v20160815-1406) "Eclipse Preferences Mechanism" [Active]
org.eclipse.equinox.registry (3.6.100.v20160223-2218) "Extension Registry Support" [Active]
org.eclipse.equinox.security (1.2.200.v20150715-1528) "Equinox Java Authentication and Authorization Service (JAAS)" [Active]
org.eclipse.equinox.security.macosx (1.100.200.v20130327-1442) "OS X Keystore service integration" [Resolved]
org.eclipse.equinox.security.ui (1.1.300.v20150803-1225) "Equinox Security Default UI" [Starting]
org.eclipse.equinox.simpleconfigurator (1.1.200.v20160504-1450) "Simple Configurator" [Active]
org.eclipse.equinox.simpleconfigurator.manipulator (2.0.200.v20160504-1450) "Simple Configurator Manipulator" [Starting]
org.eclipse.equinox.util (1.0.500.v20130404-1337) "Equinox Util Bundle" [Active]
org.eclipse.gef (3.11.0.201606061308) "GEF (MVC)" [Starting]
org.eclipse.help (3.7.0.v20160602-1307) "Help System Core" [Active]
org.eclipse.help.base (4.1.2.v20170301-0400) "Help System Base" [Starting]
org.eclipse.help.ui (4.0.200.v20160510-0758) "Help System UI" [Starting]
org.eclipse.help.webapp (3.8.0.v20160504-0839) "Help System Webapp" [Starting]
org.eclipse.jdt (3.12.3.v20170301-0400) "Eclipse Java Development Tools" [Resolved]
org.eclipse.jdt.annotation (2.1.0.v20160418-1457) "JDT Annotations for Enhanced Null Analysis" [Resolved]
org.eclipse.jdt.annotation (1.1.100.v20160418-1457) "JDT Annotations for Enhanced Null Analysis" [Resolved]
org.eclipse.jdt.apt.core (3.4.100.v20160525-0952) "Java Annotation Processing Core" [Active]
org.eclipse.jdt.apt.pluggable.core (1.1.100.v20160418-1457) "Java Compiler Apt IDE" [Active]
org.eclipse.jdt.apt.ui (3.4.100.v20160418-1457) "Java Annotation Processing UI" [Starting]
org.eclipse.jdt.compiler.apt (1.2.100.v20160418-1457) "Java Compiler Apt" [Resolved]
org.eclipse.jdt.compiler.tool (1.1.100.v20160418-1457) "Java Compiler Tool Support" [Resolved]
org.eclipse.jdt.core (3.12.3.v20170228-1205) "Java Development Tools Core" [Active]
org.eclipse.jdt.core.manipulation (1.7.0.v20160419-0705) "Java Code Manipulation Functionality" [Active]
org.eclipse.jdt.debug (3.10.1.v20160811-0441) "JDI Debug Model" [Starting]
org.eclipse.jdt.debug.ui (3.7.201.v20160811-0450) "JDI Debug UI" [Starting]
org.eclipse.jdt.doc.user (3.12.1.v20160727-2009) "Eclipse Java development user guide" [Resolved]
org.eclipse.jdt.junit (3.9.0.v20160421-1701) "Java Development Tools JUnit support" [Starting]
org.eclipse.jdt.junit.core (3.8.0.v20160421-1701) "Java Development Tools JUnit core support" [Starting]
org.eclipse.jdt.junit.runtime (3.4.600.v20160505-0715) "Java Development Tools JUnit Runtime Support" [Resolved]
org.eclipse.jdt.junit4.runtime (1.1.600.v20160505-0715) "Java Development Tools JUnit4 Runtime Support" [Resolved]
org.eclipse.jdt.launching (3.8.101.v20161111-2014) "Java Development Tools Launching Support" [Active]
org.eclipse.jdt.launching.macosx (3.3.0.v20160418-1524) "Mac OS X Launcher" [Active]
org.eclipse.jdt.launching.ui.macosx (1.1.0.v20160418-1524) "Mac OS X UI Launching Support" [Starting]
org.eclipse.jdt.ui (3.12.2.v20160929-0804) "Java Development Tools UI" [Active]
org.eclipse.jem (2.0.600.v201302011850) "Java EMF Model" [Active]
org.eclipse.jem.beaninfo (2.0.300.v201302011850) "Java EMF Model BeanInfo (Introspection) Support" [Starting]
org.eclipse.jem.beaninfo.vm (2.0.300.v201302011850) "JEM Beaninfo VM Jar" [Resolved]
org.eclipse.jem.beaninfo.vm.common (2.0.300.v201302011850) "JEM Beaninfo Common Jar" [Resolved]
org.eclipse.jem.proxy (2.0.500.v201504161518) "Java EMF Model Proxy Support" [Starting]
org.eclipse.jem.util (2.1.200.v201404021757) "Java EMF Model Utilities" [Active]
org.eclipse.jem.workbench (2.0.400.v201302011850) "Java EMF Model Workbench Support" [Starting]
org.eclipse.jetty.continuation (9.3.9.v20160517) "Jetty :: Continuation" [Resolved]
org.eclipse.jetty.http (9.3.9.v20160517) "Jetty :: Http Utility" [Resolved]
org.eclipse.jetty.io (9.3.9.v20160517) "Jetty :: IO Utility" [Resolved]
org.eclipse.jetty.security (9.3.9.v20160517) "Jetty :: Security" [Resolved]
org.eclipse.jetty.server (9.3.9.v20160517) "Jetty :: Server Core" [Resolved]
org.eclipse.jetty.servlet (9.3.9.v20160517) "Jetty :: Servlet Handling" [Resolved]
org.eclipse.jetty.util (9.3.9.v20160517) "Jetty :: Utilities" [Resolved]
org.eclipse.jetty.webapp (9.3.9.v20160517) "Jetty :: Webapp Application Support" [Resolved]
org.eclipse.jetty.xml (9.3.9.v20160517) "Jetty :: XML utilities" [Resolved]
org.eclipse.jface (3.12.2.v20170113-2113) "JFace" [Resolved]
org.eclipse.jface.databinding (1.8.1.v20161026-1531) "JFace Data Binding for SWT and JFace" [Resolved]
org.eclipse.jface.text (3.11.2.v20170220-1911) "JFace Text" [Resolved]
org.eclipse.jgit (4.6.1.201703071140-r) "JGit Core" [Active]
org.eclipse.jgit.archive (4.6.1.201703071140-r) "JGit Archive Formats" [Starting]
org.eclipse.jpt.common.branding (1.4.0.v201309202144) "Dali Java Persistence Tools - Common" [Resolved]
org.eclipse.jpt.common.core (1.5.0.v201603181811) "Dali Java Persistence Tools - Common Core" [Starting]
org.eclipse.jpt.common.eclipselink.branding (1.3.100.v201309202144) "Dali Java Persistence Tools - EclipseLink Common" [Resolved]
org.eclipse.jpt.common.eclipselink.core (1.3.200.v201603180253) "Dali Java Persistence Tools - Common EclipseLink Core" [Starting]
org.eclipse.jpt.common.ui (1.4.100.v201607281951) "Dali Java Persistence Tools - Common UI" [Starting]
org.eclipse.jpt.common.utility (2.4.0.v201603181811) "Dali Java Persistence Tools - Common Utility" [Starting]
org.eclipse.jpt.dbws.eclipselink.branding (1.2.100.v201309202144) "Dali Java Persistence Tools - EclipseLink DBWS Support" [Resolved]
org.eclipse.jpt.dbws.eclipselink.core.gen (1.1.200.v201603180253) "Dali Java Persistence Tools - DBWS Support - Web Services Generation" [Starting]
org.eclipse.jpt.dbws.eclipselink.ui (1.1.200.v201603180253) "Dali Java Persistence Tools - DBWS UI" [Starting]
org.eclipse.jpt.doc.user (3.2.100.v201308231650) "Dali Java Persistence Tools - Documentation" [Resolved]
org.eclipse.jpt.jaxb.branding (1.4.0.v201309202144) "Dali Java Persistence Tools - JAXB Support" [Resolved]
org.eclipse.jpt.jaxb.core (1.4.100.v201603180253) "Dali Java Persistence Tools - JAXB Core" [Starting]
org.eclipse.jpt.jaxb.core.schemagen (1.1.200.v201603180253) "Dali Java Persistence Tools - JAXB Support - Schema Generation" [Starting]
org.eclipse.jpt.jaxb.eclipselink.branding (1.4.100.v201309202144) "Dali Java Persistence Tools - EclipseLink MOXy (JAXB) Support" [Resolved]
org.eclipse.jpt.jaxb.eclipselink.core (1.3.200.v201603180253) "Dali Java Persistence Tools - EclipseLink JAXB Support - Core" [Starting]
org.eclipse.jpt.jaxb.eclipselink.core.schemagen (1.2.200.v201603180253) "Dali Java Persistence Tools - EclipseLink JAXB Support - Schema Generation" [Starting]
org.eclipse.jpt.jaxb.eclipselink.ui (1.4.200.v201603180253) "Dali Java Persistence Tools - EclipseLink MOXy Support - UI" [Starting]
org.eclipse.jpt.jaxb.ui (1.5.100.v201603180253) "Dali Java Persistence Tools - JAXB UI" [Starting]
org.eclipse.jpt.jpa.annotate (1.0.100.v201309261652) "Dali Java Persistence Tools - Annotate" [Starting]
org.eclipse.jpt.jpa.branding (3.4.0.v201309202144) "Dali Java Persistence Tools - JPA Support" [Resolved]
org.eclipse.jpt.jpa.core (3.5.0.v201603181811) "Dali Java Persistence Tools - JPA Core" [Starting]
org.eclipse.jpt.jpa.db (2.2.200.v201603180253) "Dali Java Persistence Tools - JPA DB" [Starting]
org.eclipse.jpt.jpa.db.ui (2.1.200.v201603180253) "Dali Java Persistence Tools - JPA DB UI" [Starting]
org.eclipse.jpt.jpa.eclipselink.branding (3.4.0.v201309202144) "Dali Java Persistence Tools - EclipseLink JPA Support" [Resolved]
org.eclipse.jpt.jpa.eclipselink.core (2.4.100.v201603180253) "Dali Java Persistence Tools - JPA EclipseLink Support - Core" [Starting]
org.eclipse.jpt.jpa.eclipselink.core.ddlgen (2.2.200.v201603180253) "Dali Java Persistence Tools - Jpa EclipseLink Support - DDL Generation" [Starting]
org.eclipse.jpt.jpa.eclipselink.ui (2.4.100.v201603180253) "Dali Java Persistence Tools - EclipseLink Support - UI" [Starting]
org.eclipse.jpt.jpa.gen (2.3.200.v201512212242) "Dali Java Persistence Tools - Entity Gen" [Starting]
org.eclipse.jpt.jpa.ui (3.4.100.v201607131827) "Dali Java Persistence Tools - JPA UI" [Starting]
org.eclipse.jsch.core (1.3.0.v20160422-1917) "JSch Core" [Active]
org.eclipse.jsch.ui (1.3.0.v20160323-1650) "JSch UI" [Starting]
org.eclipse.jsf.branding (3.5.0.v201309172308) "JSF Tools" [Resolved]
org.eclipse.json (1.0.1.v201612232230) "Structured Source JSON Model" [Starting]
org.eclipse.jst.common.annotations.controller (1.1.300.v201302011850) "Annotation Controller Plug-in" [Resolved]
org.eclipse.jst.common.annotations.core (1.1.300.v201302011850) "Annotation Core Plug-in" [Resolved]
org.eclipse.jst.common.annotations.ui (1.1.300.v201302011850) "Annotations UI Plug-in" [Starting]
org.eclipse.jst.common.frameworks (1.1.701.v201509021802) "Integration Plug-in" [Active]
org.eclipse.jst.common.project.facet.core (1.4.500.v201508121553) "Eclipse Faceted Project Framework JDT Enablement" [Active]
org.eclipse.jst.common.project.facet.ui (1.4.510.v201501141810) "Eclipse Faceted Project Framework JDT Enablement UI" [Starting]
org.eclipse.jst.common.ui (1.0.300.v201603172133) "Common JST UI Plug-in" [Starting]
org.eclipse.jst.ejb.doc.user (1.1.301.v201105130955) "EJB docs" [Starting]
org.eclipse.jst.ejb.ui (1.1.910.v201701262130) "WTP EJB UI Plug-in" [Starting]
org.eclipse.jst.ejb.ui.infopop (1.0.300.v201002231012) "EJB infopop" [Starting]
org.eclipse.jst.j2ee (1.1.901.v201701192236) "Java EE Component" [Active]
org.eclipse.jst.j2ee.core (1.3.200.v201505041449) "J2EE Core Component" [Active]
org.eclipse.jst.j2ee.doc.user (1.1.400.v201008122207) "J2EE tools documentation" [Resolved]
org.eclipse.jst.j2ee.ejb (1.1.900.v201701262105) "EJB component Plug-in" [Starting]
org.eclipse.jst.j2ee.ejb.annotation.model (1.1.400.v201701262105) "EJB Annotation Model Plug-in" [Starting]
org.eclipse.jst.j2ee.ejb.annotations.emitter (1.1.300.v201701262105) "EJB Emitter Plug-in" [Starting]
org.eclipse.jst.j2ee.ejb.annotations.ui (1.1.300.v201701262105) "EJB Annotations Ui Plug-in" [Starting]
org.eclipse.jst.j2ee.ejb.annotations.xdoclet (1.2.300.v201701262105) "Xdoclet Annotations Plug-in" [Starting]
org.eclipse.jst.j2ee.infopop (1.0.300.v201309091923) "J2EE tools infopops" [Resolved]
org.eclipse.jst.j2ee.jca (1.1.800.v201602161345) "JCA Plug-in" [Starting]
org.eclipse.jst.j2ee.jca.ui (1.1.500.v201304231803) "WTP JCA UI Plug-in" [Starting]
org.eclipse.jst.j2ee.navigator.ui (1.1.600.v201302011850) "J2EE Extensions to Common Navigator" [Active]
org.eclipse.jst.j2ee.ui (1.1.900.v201602161345) "WTP J2EE UI Plug-in" [Active]
org.eclipse.jst.j2ee.web (1.1.851.v201608191717) "Web Plug-in" [Active]
org.eclipse.jst.j2ee.webservice (1.1.400.v201302011850) "Web Service Plug-in" [Active]
org.eclipse.jst.j2ee.webservice.ui (1.1.500.v201302011850) "WTP Webservice UI Plug-in" [Active]
org.eclipse.jst.j2ee.xdoclet.runtime (1.1.300.v201004280609) "XDocletRuntime Plug-in" [Starting]
org.eclipse.jst.jee (1.0.700.v201404092004) "Java EE common Plug-in" [Starting]
org.eclipse.jst.jee.ejb (1.0.500.v201701262105) "Java EE Ejb Plug-in" [Starting]
org.eclipse.jst.jee.ui (1.0.701.v201408251535) "Eclipse Java EE Developer Tools" [Active]
org.eclipse.jst.jee.web (1.0.500.v201404021628) "Java EE Web Plug-in" [Starting]
org.eclipse.jst.jsf.apache.trinidad.tagsupport (1.4.0.v201309172102) "JSF Tools - Tag Library Metadata (Apache Trinidad)" [Starting]
org.eclipse.jst.jsf.common (1.5.101.v201504022146) "JSF Tools - Common" [Starting]
org.eclipse.jst.jsf.common.runtime (1.4.0.v201309172102) "JSF Tools - Common Runtime" [Starting]
org.eclipse.jst.jsf.common.ui (1.5.0.v201309172102) "JSF Tools - Common UI" [Starting]
org.eclipse.jst.jsf.core (1.7.111.v201603050214) "JSF Tools - Core" [Starting]
org.eclipse.jst.jsf.doc.user (1.5.0.v201309172352) "JSF Tools - User Guide" [Starting]
org.eclipse.jst.jsf.facelet.core (1.3.110.v201603071844) "JSF Tools - Facelets Core" [Starting]
org.eclipse.jst.jsf.facelet.ui (1.3.110.v201603071844) "JSF Tools - Facelets UI" [Starting]
org.eclipse.jst.jsf.facesconfig (1.5.0.v201309172102) "JSF Tools - FacesConfig Model" [Starting]
org.eclipse.jst.jsf.facesconfig.ui (1.5.0.v201309172102) "JSF Tools - FacesConfig UI" [Starting]
org.eclipse.jst.jsf.standard.tagsupport (1.5.0.v201309172102) "JSF Tools - Tag Library Metadata (Standard)" [Starting]
org.eclipse.jst.jsf.ui (1.6.0.v201309172102) "JSF Tools - UI" [Starting]
org.eclipse.jst.jsp.core (1.2.901.v201608060346) "Structured Source JSP Model" [Starting]
org.eclipse.jst.jsp.ui (1.1.1100.v201605092203) "SSE JSP Source Editor" [Starting]
org.eclipse.jst.jsp.ui.infopop (1.0.200.v201309112106) "JSP tools infopops" [Resolved]
org.eclipse.jst.pagedesigner (1.7.110.v201603071844) "JSF Tools - Web Page Editor" [Starting]
org.eclipse.jst.pagedesigner.jsf.ui (1.5.0.v201309172102) "JSF Tools - Web Page Editor (JSF UI)" [Starting]
org.eclipse.jst.pagedesigner.jsp.core (1.5.100.v201603071844) "JSF Tools - Web Page Editor (JSP Core)" [Starting]
org.eclipse.jst.server.core (1.2.500.v201603031514) "Java Server Support" [Starting]
org.eclipse.jst.server.generic.core (1.0.900.v201606081655) "Generic Server Plugin" [Starting]
org.eclipse.jst.server.generic.jonas (1.5.500.v201405151744) "JOnAS Generic Server definitions" [Starting]
org.eclipse.jst.server.generic.ui (1.0.600.v201402262303) "Generic Server Plugin UI" [Starting]
org.eclipse.jst.server.preview.adapter (1.1.300.v201606081655) "JEE Preview Server Support" [Starting]
org.eclipse.jst.server.tomcat.core (1.1.801.v201609071751) "Apache Tomcat Support" [Starting]
org.eclipse.jst.server.tomcat.ui (1.1.501.v201609071751) "Apache Tomcat UI Support" [Starting]
org.eclipse.jst.server.ui (1.1.300.v201309182039) "Java Server UI Support" [Starting]
org.eclipse.jst.server.ui.doc.user (1.0.600.v201309182117) "Server Tools documentation for J2EE Standard Tools" [Starting]
org.eclipse.jst.server.ui.infopop (1.0.500.v201309182117) "Server Tools infopops for J2EE Standard Tools" [Resolved]
org.eclipse.jst.servlet.ui (1.1.900.v201605251556) "WTP Servlet UI Plug-in" [Starting]
org.eclipse.jst.servlet.ui.infopop (1.0.500.v201105121947) "Servlet infopop" [Starting]
org.eclipse.jst.standard.schemas (1.2.201.v201501151629) "Java EE Related Schemas" [Resolved]
org.eclipse.jst.ws (1.0.800.v201701262139) "Web Services" [Starting]
org.eclipse.jst.ws.annotations.core (1.2.200.v201311102023) "Annotations Core" [Starting]
org.eclipse.jst.ws.axis.consumption.core (1.0.550.v201505131719) "Web service Axis Consumption Core" [Starting]
org.eclipse.jst.ws.axis.consumption.ui (1.0.900.v201701262139) "Webservice Axis Consumption UI" [Starting]
org.eclipse.jst.ws.axis.creation.ui (1.0.900.v201701262139) "Webservice Axis Creation UI" [Starting]
org.eclipse.jst.ws.axis.infopop (1.0.400.v201309242123) "Web services Axis context sensitive help" [Starting]
org.eclipse.jst.ws.axis.ui.doc.user (1.1.200.v201309242123) "Axis Web services documentation" [Resolved]
org.eclipse.jst.ws.axis2.consumption.core (1.0.200.v201309242118) "Webservice Axis2 Consumption Core Plug-in" [Starting]
org.eclipse.jst.ws.axis2.consumption.ui (1.0.200.v201309242118) "Webservice Axis2 Consumption UI Plug-in" [Starting]
org.eclipse.jst.ws.axis2.core (1.0.300.v201309242118) "Webservice Axis2 Core Plug-in" [Starting]
org.eclipse.jst.ws.axis2.creation.core (1.0.200.v201309242118) "Webservice Axis2 Creation Core Plug-in" [Starting]
org.eclipse.jst.ws.axis2.creation.ui (1.0.200.v201309242118) "Webservice Axis2 Creation UI Plug-in" [Starting]
org.eclipse.jst.ws.axis2.ui (1.0.400.v201309242118) "Axis2 Tools" [Starting]
org.eclipse.jst.ws.axis2.ui.doc.user (1.0.200.v201309242118) "Axis2 Web services documentation" [Resolved]
org.eclipse.jst.ws.consumption (1.0.950.v201701262139) "Web Services Consumption" [Starting]
org.eclipse.jst.ws.consumption.infopop (1.0.400.v201309242123) "Web services UI" [Resolved]
org.eclipse.jst.ws.consumption.ui (1.1.850.v201701262139) "Web Services Consumption Graphical User Interface" [Starting]
org.eclipse.jst.ws.consumption.ui.doc.user (1.0.700.v201309242123) "Web service consumption documentation" [Starting]
org.eclipse.jst.ws.creation.ejb.ui (1.0.250.v201309242123) "Web Services Creation EJB Graphical User Interface" [Resolved]
org.eclipse.jst.ws.creation.ui (1.0.950.v201701262139) "Web Services Creation Graphical User Interface" [Starting]
org.eclipse.jst.ws.cxf.consumption.core (1.0.400.v201701262158) "CXF Web Services Consumption Core" [Starting]
org.eclipse.jst.ws.cxf.consumption.ui (1.0.400.v201701262158) "CXF Web Services Consumption UI" [Starting]
org.eclipse.jst.ws.cxf.core (1.1.300.v201701262158) "CXF Web Services Core" [Starting]
org.eclipse.jst.ws.cxf.creation.core (1.0.500.v201701262158) "CXF Web Services Creation Core" [Starting]
org.eclipse.jst.ws.cxf.creation.ui (1.0.300.v201403242125) "CXF Web Services Creation UI" [Starting]
org.eclipse.jst.ws.cxf.doc.user (1.0.300.v201309232209) "CXF Web services User Guide" [Resolved]
org.eclipse.jst.ws.cxf.ui (1.0.300.v201309232152) "CXF Web Services UI" [Starting]
org.eclipse.jst.ws.doc.user (1.0.700.v201612121628) "Web Services UI" [Resolved]
org.eclipse.jst.ws.infopop (1.0.400.v201309242123) "Web services UI" [Resolved]
org.eclipse.jst.ws.jaxb.core (1.0.200.v201309232152) "JAXB Tools Core" [Starting]
org.eclipse.jst.ws.jaxrs.core (1.0.700.v201701262139) "JAX-RS Tools - Core" [Active]
org.eclipse.jst.ws.jaxrs.ui (1.0.700.v201505131719) "JAX-RS Tools - UI" [Starting]
org.eclipse.jst.ws.jaxws.core (1.0.500.v201701262158) "JAX-WS Tools Core" [Starting]
org.eclipse.jst.ws.jaxws.doc.user (1.0.400.v201309232209) "JAX-WS Tools User Guide" [Resolved]
org.eclipse.jst.ws.jaxws.dom.integration (1.0.300.v201308151836) "JAX-WS DOM Integration" [Starting]
org.eclipse.jst.ws.jaxws.dom.runtime (1.0.300.v201308151836) "JAX-WS DOM Runtime" [Resolved]
org.eclipse.jst.ws.jaxws.dom.ui (1.0.100.v201308151836) "JAX-WS DOM UI" [Starting]
org.eclipse.jst.ws.jaxws.ui (1.0.401.v201504291921) "JAX-WS Tools UI" [Starting]
org.eclipse.jst.ws.jaxws.utils (1.0.301.v201504272154) "JAX-WS Utils" [Starting]
org.eclipse.jst.ws.uddiregistry (1.0.600.v201505131719) "Web Services Universal Description Discovery and Integration Registry" [Starting]
org.eclipse.jst.ws.ui (1.0.600.v201701262139) "Web Services Graphical User Interface" [Starting]
org.eclipse.ltk.core.refactoring (3.7.0.v20160419-0705) "Refactoring Core" [Active]
org.eclipse.ltk.ui.refactoring (3.8.0.v20160518-1817) "Refactoring UI" [Active]
org.eclipse.m2e.archetype.common (1.7.0.20160603-1931) "Maven Archetype Common Bundle" [Resolved]
org.eclipse.m2e.core (1.7.0.20160603-1933) "Maven Integration for Eclipse" [Active]
org.eclipse.m2e.core.ui (1.7.0.20160603-1933) "Maven Integration for Eclipse" [Starting]
org.eclipse.m2e.discovery (1.7.0.20160603-1933) "m2e Marketplace" [Starting]
org.eclipse.m2e.editor (1.7.0.20160603-1933) "Maven Integration for Eclipse (Editors)" [Starting]
org.eclipse.m2e.editor.xml (1.7.0.20160603-1933) "Maven POM XML Editor" [Starting]
org.eclipse.m2e.importer (1.7.0.20160603-1933) "m2e extension for import framework" [Starting]
org.eclipse.m2e.jdt (1.7.0.20160603-1933) "Maven Integration for Eclipse JDT" [Active]
org.eclipse.m2e.jdt.ui (1.7.0.20160603-1933) "Maven Integration for Eclipse JDT UI" [Resolved]
org.eclipse.m2e.launching (1.7.0.20160603-1933) "Maven Integration for Eclipse Launching" [Starting]
org.eclipse.m2e.lifecyclemapping.defaults (1.7.0.20160603-1933) "Default Build Lifecycle Mapping Metadata" [Resolved]
org.eclipse.m2e.logback.appender (1.7.0.20160603-1933) "m2e logback appender" [Resolved]
org.eclipse.m2e.logback.configuration (1.7.0.20160603-1933) "m2e logback configuration" [Active]
org.eclipse.m2e.maven.indexer (1.7.0.20160603-1931) "Maven / Nexus Indexer Bundle" [Resolved]
org.eclipse.m2e.maven.runtime (1.7.0.20160603-1931) "Embedded Maven Runtime Bundle (includes Incubating components)" [Resolved]
org.eclipse.m2e.maven.runtime.slf4j.simple (1.7.0.20160603-1931) "slf4j-simple for use in m2e embedded maven runtime" [Resolved]
org.eclipse.m2e.model.edit (1.7.0.20160603-1933) "Maven Project Model Edit Bundle" [Starting]
org.eclipse.m2e.profiles.core (1.7.0.20160603-1933) "Maven Profiles Management" [Starting]
org.eclipse.m2e.profiles.ui (1.7.0.20160603-1933) "Maven Profiles Management UI" [Starting]
org.eclipse.m2e.refactoring (1.7.0.20160603-1933) "Maven Integration for Eclipse Refactoring" [Starting]
org.eclipse.m2e.scm (1.7.0.20160603-1933) "SCM Maven Integration for Eclipse" [Resolved]
org.eclipse.m2e.workspace.cli (0.3.1) "m2e-workspace" [Resolved]
org.eclipse.m2e.wtp (1.3.1.20160831-1005) "Maven Integration for Eclipse WTP" [Active]
org.eclipse.m2e.wtp.jaxrs (1.3.1.20160831-1005) "Maven JAX-RS Configurator" [Active]
org.eclipse.m2e.wtp.jpa (1.3.1.20160831-1005) "Maven JPA Configurator" [Active]
org.eclipse.m2e.wtp.jsf (1.3.1.20160831-1005) "Maven JSF Configurator" [Active]
org.eclipse.m2e.wtp.overlay (1.3.1.20160831-1005) "Overlay support for Eclipse WTP" [Starting]
org.eclipse.m2e.wtp.overlay.ui (1.3.1.20160831-1005) "Overlay support for Eclipse WTP - UI" [Starting]
org.eclipse.mylyn.bugzilla.core (3.21.0.v20160909-1813) "Mylyn Bugzilla Connector Core" [Active]
org.eclipse.mylyn.bugzilla.ide (3.21.0.v20160912-1820) "Mylyn Bugzilla IDE Extensions" [Resolved]
org.eclipse.mylyn.bugzilla.ui (3.21.0.v20160909-1813) "Mylyn Bugzilla Connector UI" [Active]
org.eclipse.mylyn.commons.core (3.21.0.v20160707-1856) "Mylyn Commons" [Active]
org.eclipse.mylyn.commons.identity.core (1.13.0.v20160630-1702) "Mylyn SCM Framework" [Starting]
org.eclipse.mylyn.commons.net (3.21.0.v20160630-1702) "Mylyn Commons Net" [Active]
org.eclipse.mylyn.commons.notifications.core (1.13.0.v20160630-1702) "Mylyn Commons" [Active]
org.eclipse.mylyn.commons.notifications.feed (1.13.0.v20160721-2347) "Mylyn Commons" [Active]
org.eclipse.mylyn.commons.notifications.ui (1.13.0.v20160630-1702) "Mylyn Commons" [Active]
org.eclipse.mylyn.commons.repositories.core (1.13.0.v20160630-1702) "Mylyn Commons" [Resolved]
org.eclipse.mylyn.commons.repositories.ui (1.13.0.v20160630-1702) "Mylyn Commons" [Active]
org.eclipse.mylyn.commons.screenshots (3.21.0.v20160630-1702) "Mylyn Commons" [Resolved]
org.eclipse.mylyn.commons.ui (3.21.0.v20160630-1702) "Mylyn Commons UI" [Active]
org.eclipse.mylyn.commons.workbench (3.21.0.v20160630-1702) "Mylyn Commons UI" [Active]
org.eclipse.mylyn.commons.xmlrpc (3.21.0.v20160630-1702) "Mylyn XML-RPC Support" [Starting]
org.eclipse.mylyn.context.core (3.21.0.v20160701-1337) "Mylyn Context" [Active]
org.eclipse.mylyn.context.tasks.ui (3.21.0.v20160815-2336) "Mylyn Context Tasks UI" [Active]
org.eclipse.mylyn.context.ui (3.21.0.v20160701-1337) "Mylyn Context UI" [Starting]
org.eclipse.mylyn.debug.ui (3.21.0.v20160701-1337) "Mylyn Context" [Starting]
org.eclipse.mylyn.discovery.core (3.21.0.v20160729-1739) "Mylyn Connector Discovery Core" [Resolved]
org.eclipse.mylyn.discovery.ui (3.21.0.v20160630-1702) "Mylyn Connector Discovery UI" [Resolved]
org.eclipse.mylyn.help.ui (3.21.0.v20160913-2013) "Mylyn Help" [Starting]
org.eclipse.mylyn.ide.ant (3.21.0.v20160701-1337) "Mylyn Ant Bridge" [Starting]
org.eclipse.mylyn.ide.ui (3.21.0.v20160701-1337) "Mylyn IDE UI" [Starting]
org.eclipse.mylyn.java.tasks (3.21.0.v20160701-1337) "Mylyn Java Tasks" [Starting]
org.eclipse.mylyn.java.ui (3.21.0.v20160701-1337) "Mylyn Java Bridge" [Starting]
org.eclipse.mylyn.monitor.core (3.21.0.v20160630-1702) "Mylyn Monitor Core" [Resolved]
org.eclipse.mylyn.monitor.ui (3.21.0.v20160630-1702) "Mylyn Monitor UI" [Active]
org.eclipse.mylyn.resources.ui (3.21.0.v20160701-1337) "Mylyn Resources UI" [Starting]
org.eclipse.mylyn.tasks.bugs (3.21.0.v20160929-1805) "Mylyn Bug Reporting" [Starting]
org.eclipse.mylyn.tasks.core (3.21.0.v20160914-0252) "Mylyn Tasks Core" [Resolved]
org.eclipse.mylyn.tasks.index.core (3.21.0.v20160630-2019) "Mylyn Tasks Index Core" [Starting]
org.eclipse.mylyn.tasks.index.ui (3.21.0.v20160630-2019) "Mylyn Tasks Index UI" [Resolved]
org.eclipse.mylyn.tasks.search (3.21.0.v20160630-2019) "Mylyn Tasks Search" [Resolved]
org.eclipse.mylyn.tasks.ui (3.21.0.v20160913-2131) "Mylyn Tasks UI" [Active]
org.eclipse.mylyn.team.ui (3.21.0.v20160701-1337) "Mylyn Team UI" [Active]
org.eclipse.mylyn.wikitext.asciidoc.core (2.10.1.v20161129-1925) "Mylyn WikiText AsciiDoc" [Resolved]
org.eclipse.mylyn.wikitext.asciidoc.ui (2.10.1.v20161129-1925) "Mylyn WikiText AsciiDoc UI" [Resolved]
org.eclipse.mylyn.wikitext.confluence.core (2.10.1.v20161129-1925) "Mylyn WikiText Confluence" [Resolved]
org.eclipse.mylyn.wikitext.confluence.ui (2.10.1.v20161129-1925) "Mylyn WikiText Confluence UI" [Resolved]
org.eclipse.mylyn.wikitext.context.ui (2.10.1.v20161129-1925) "Mylyn WikiText Context UI" [Starting]
org.eclipse.mylyn.wikitext.core (2.10.1.v20161129-1925) "Mylyn WikiText" [Resolved]
org.eclipse.mylyn.wikitext.core.ant (2.10.1.v20161129-1925) "Mylyn WikiText Ant Plug-in" [Starting]
org.eclipse.mylyn.wikitext.core.osgi (2.10.1.v20161129-1925) "Mylyn WikiText OSGi Plug-in" [Starting]
org.eclipse.mylyn.wikitext.help.ui (2.10.1.v20161129-1925) "Mylyn WikiText Help UI" [Resolved]
org.eclipse.mylyn.wikitext.html.core (2.10.1.v20161129-1925) "Mylyn WikiText HTML" [Resolved]
org.eclipse.mylyn.wikitext.markdown.core (2.10.1.v20161129-1925) "Mylyn WikiText Markdown" [Resolved]
org.eclipse.mylyn.wikitext.markdown.ui (2.10.1.v20161129-1925) "Mylyn WikiText Markdown UI" [Resolved]
org.eclipse.mylyn.wikitext.mediawiki.core (2.10.1.v20161129-1925) "Mylyn WikiText MediaWiki" [Resolved]
org.eclipse.mylyn.wikitext.mediawiki.core.ant (2.10.1.v20161129-1925) "Mylyn WikiText MediaWiki Ant Plug-in" [Resolved]
org.eclipse.mylyn.wikitext.mediawiki.ui (2.10.1.v20161129-1925) "Mylyn WikiText MediaWiki UI" [Resolved]
org.eclipse.mylyn.wikitext.tasks.ui (2.10.1.v20161129-1925) "Mylyn WikiText Tasks UI" [Starting]
org.eclipse.mylyn.wikitext.textile.core (2.10.1.v20161129-1925) "Mylyn WikiText Textile" [Resolved]
org.eclipse.mylyn.wikitext.textile.ui (2.10.1.v20161129-1925) "Mylyn WikiText Textile UI" [Resolved]
org.eclipse.mylyn.wikitext.tracwiki.core (2.10.1.v20161129-1925) "Mylyn WikiText TracWiki" [Resolved]
org.eclipse.mylyn.wikitext.tracwiki.ui (2.10.1.v20161129-1925) "Mylyn WikiText TracWiki UI" [Resolved]
org.eclipse.mylyn.wikitext.twiki.core (2.10.1.v20161129-1925) "Mylyn WikiText Twiki" [Resolved]
org.eclipse.mylyn.wikitext.twiki.ui (2.10.1.v20161129-1925) "Mylyn WikiText Twiki UI" [Resolved]
org.eclipse.mylyn.wikitext.ui (2.10.1.v20161129-1925) "Mylyn WikiText UI" [Starting]
org.eclipse.nebula.widgets.tablecombo (1.0.0.201702281340) "Nebula TableCombo Plugin" [Resolved]
org.eclipse.oomph.base (1.7.0.v20170201-1645) "Oomph Base Model" [Active]
org.eclipse.oomph.base.edit (1.7.0.v20170104-1401) "Oomph Base Edit Support" [Active]
org.eclipse.oomph.extractor.lib (1.3.0.v20161116-0647) "Oomph Extractor Library" [Resolved]
org.eclipse.oomph.jreinfo (1.7.0.v20170201-1645) "Oomph JRE Info" [Starting]
org.eclipse.oomph.jreinfo.ui (1.7.0.v20161220-1444) "Oomph JRE Info UI" [Active]
org.eclipse.oomph.p2 (1.7.0.v20170104-1401) "Oomph P2 Management" [Active]
org.eclipse.oomph.p2.core (1.7.0.v20170228-1751) "Oomph P2 Management Core" [Active]
org.eclipse.oomph.p2.doc (1.7.0.v20170104-1401) "Oomph P2 Management Documentation" [Resolved]
org.eclipse.oomph.p2.edit (1.7.0.v20170104-1401) "Oomph P2 Management Edit Support" [Active]
org.eclipse.oomph.p2.ui (1.7.0.v20161231-0937) "Oomph P2 Management UI" [Active]
org.eclipse.oomph.predicates (1.7.0.v20170104-1401) "Oomph Predicates Model" [Active]
org.eclipse.oomph.predicates.edit (1.7.0.v20170104-1401) "Oomph Predicates Edit Support" [Active]
org.eclipse.oomph.preferences (1.7.0.v20170104-1401) "Oomph Preference Management" [Active]
org.eclipse.oomph.resources (1.7.0.v20170217-1028) "Oomph Resources Model" [Active]
org.eclipse.oomph.resources.edit (1.7.0.v20170103-0924) "Oomph Resources Edit Support" [Starting]
org.eclipse.oomph.setup (1.7.0.v20170224-1311) "Oomph Setup" [Active]
org.eclipse.oomph.setup.core (1.7.0.v20170301-0747) "Oomph Setup Core" [Active]
org.eclipse.oomph.setup.doc (1.7.0.v20170104-1401) "Oomph Setup Documentation" [Resolved]
org.eclipse.oomph.setup.edit (1.7.0.v20170104-1401) "Oomph Setup Edit Support" [Active]
org.eclipse.oomph.setup.editor (1.7.0.v20170104-1401) "Oomph Setup Editor" [Starting]
org.eclipse.oomph.setup.p2 (1.7.0.v20170217-1051) "Oomph Setup P2" [Active]
org.eclipse.oomph.setup.p2.edit (1.7.0.v20161230-1057) "Oomph Setup P2 Edit Support" [Active]
org.eclipse.oomph.setup.sync (1.7.0.v20170201-1631) "Oomph Setup Synchronizer" [Active]
org.eclipse.oomph.setup.ui (1.7.0.v20170305-1123) "Oomph Setup UI" [Active]
org.eclipse.oomph.setup.ui.questionnaire (1.7.0.v20170104-1401) "Oomph Setup UI Questionnaire" [Starting]
org.eclipse.oomph.ui (1.7.0.v20170222-1350) "Oomph Common UI" [Active]
org.eclipse.oomph.util (1.7.0.v20170303-0927) "Oomph Common Utilities" [Active]
org.eclipse.oomph.workingsets (1.7.0.v20170104-1401) "Oomph Dynamic Working Sets" [Active]
org.eclipse.oomph.workingsets.edit (1.7.0.v20170104-1401) "Oomph Dynamic Working Sets Edit Support" [Starting]
org.eclipse.oomph.workingsets.editor (1.7.0.v20161230-1057) "Oomph Dynamic Working Sets Editor" [Active]
org.eclipse.osgi (3.11.3.v20170209-1843) "OSGi System Bundle" [Active]
org.eclipse.osgi.compatibility.state (1.0.200.v20160504-1419) "Equinox State and Resolver Compatibility Fragment" [Resolved]
org.eclipse.osgi.services (3.5.100.v20160504-1419) "OSGi Release 4.2.0 Services" [Resolved]
org.eclipse.osgi.util (3.3.100.v20150423-1351) "OSGi Release 4.2.0 Utility Classes" [Resolved]
org.eclipse.pde (3.12.3.v20170301-0400) "PDE" [Resolved]
org.eclipse.pde.api.tools (1.1.2.v20161115-0549) "API Tools" [Starting]
org.eclipse.pde.api.tools.annotations (1.0.100.v20160418-1724) "PDE API Tools Annotations" [Resolved]
org.eclipse.pde.api.tools.ui (1.1.0.v20160519-0701) "API Tools UI" [Starting]
org.eclipse.pde.build (3.9.200.v20160204-0642) "Plug-in Development Environment Build Support" [Starting]
org.eclipse.pde.core (3.11.1.v20161115-1951) "PDE Core" [Active]
org.eclipse.pde.doc.user (3.12.2.v20170221-1001) "PDE User Guide" [Resolved]
org.eclipse.pde.ds.annotations (1.0.0.v20160525-1437) "Declarative Services Annotations Support" [Active]
org.eclipse.pde.ds.core (1.1.0.v20151201-1325) "PDE DS Core" [Starting]
org.eclipse.pde.ds.ui (1.1.0.v20160518-1843) "PDE DS UI" [Starting]
org.eclipse.pde.junit.runtime (3.5.0.v20151013-0625) "PDE JUnit Runtime Support" [Starting]
org.eclipse.pde.launching (3.6.401.v20161115-0549) "PDE Launching Support" [Active]
org.eclipse.pde.runtime (3.5.0.v20160418-1724) "PDE Runtime" [Starting]
org.eclipse.pde.ua.core (1.0.500.v20160204-0642) "PDE UA Core" [Starting]
org.eclipse.pde.ua.ui (1.1.0.v20160518-1843) "PDE UA UI" [Starting]
org.eclipse.pde.ui (3.9.100.v20161102-0517) "PDE UI" [Active]
org.eclipse.pde.ui.templates (3.6.0.v20160424-1948) "PDE Templates" [Starting]
org.eclipse.persistence.antlr (3.2.0.v201302191141) "EclipseLink ANTLR" [Resolved]
org.eclipse.persistence.asm (5.0.1.v201405080102) "EclipseLink ASM" [Resolved]
org.eclipse.persistence.core (2.6.0.v20140809-296a69f) "EclipseLink Core" [Resolved]
org.eclipse.persistence.dbws (2.6.0.v20140809-296a69f) "EclipseLink DBWS" [Resolved]
org.eclipse.persistence.dbws.builder (2.6.0.v20140809-296a69f) "EclipseLink DBWS Builder" [Resolved]
org.eclipse.persistence.jpa (2.6.0.v20140809-296a69f) "EclipseLink JPA" [Resolved]
org.eclipse.persistence.jpa.jpql (2.6.0.v20140809-296a69f) "EclipseLink Hermes Parser" [Resolved]
org.eclipse.persistence.moxy (2.6.0.v20130815-a4708b6) "EclipseLink MOXy" [Resolved]
org.eclipse.platform (4.6.3.v20170301-0400) "Eclipse Platform" [Resolved]
org.eclipse.platform.doc.user (4.6.1.v20160727-2009) "Eclipse Workbench User Guide" [Resolved]
org.eclipse.rcp (4.6.3.v20170301-0400) "Eclipse RCP" [Starting]
org.eclipse.recommenders.apidocs (2.4.6.v20170307-1041) "Code Recommenders API‐Docs Runtime" [Resolved]
org.eclipse.recommenders.apidocs.rcp (2.4.6.v20170307-1041) "Code Recommenders API‐Docs UI" [Starting]
org.eclipse.recommenders.calls (2.4.6.v20170307-1041) "Code Recommenders Call‐Completion Runtime" [Resolved]
org.eclipse.recommenders.calls.rcp (2.4.6.v20170307-1041) "Code Recommenders Call‐Completion UI" [Resolved]
org.eclipse.recommenders.chain.rcp (2.4.6.v20170307-1041) "Code Recommenders Chain‐Completion UI" [Starting]
org.eclipse.recommenders.completion.rcp (2.4.6.v20170307-1041) "Code Recommenders Code‐Completion UI" [Starting]
org.eclipse.recommenders.constructors (2.4.6.v20170307-1041) "Code Recommenders Constructor‐Completion Runtime" [Resolved]
org.eclipse.recommenders.constructors.rcp (2.4.6.v20170307-1041) "Code Recommenders Constructor‐Completion UI" [Resolved]
org.eclipse.recommenders.coordinates (2.4.6.v20170307-1041) "Code Recommenders Dependency Identification Runtime" [Starting]
org.eclipse.recommenders.coordinates.rcp (2.4.6.v20170307-1041) "Code Recommenders Dependency Identification UI" [Starting]
org.eclipse.recommenders.injection (2.4.6.v20170307-1041) "Code Recommenders Injection Runtime" [Starting]
org.eclipse.recommenders.jayes (2.4.6.v20170307-1041) "Code Recommenders Jayes Bayesian‐Network Library" [Resolved]
org.eclipse.recommenders.jayes.io (2.4.6.v20170307-1041) "Code Recommenders Jayes I/O Library" [Resolved]
org.eclipse.recommenders.jdt (2.4.6.v20170307-1041) "Code Recommenders JDT Utilities" [Resolved]
org.eclipse.recommenders.models (2.4.6.v20170307-1041) "Code Recommenders Models Runtime" [Starting]
org.eclipse.recommenders.models.rcp (2.4.6.v20170307-1041) "Code Recommenders Models UI" [Resolved]
org.eclipse.recommenders.mylyn.rcp (2.4.6.v20170307-1041) "Code Recommenders Mylyn Completion UI" [Resolved]
org.eclipse.recommenders.net (2.4.6.v20170307-1041) "Code Recommenders Network Utilities" [Resolved]
org.eclipse.recommenders.overrides (2.4.6.v20170307-1041) "Code Recommenders Overrides‐Completion Runtime" [Resolved]
org.eclipse.recommenders.overrides.rcp (2.4.6.v20170307-1041) "Code Recommenders Overrides‐Completion UI" [Resolved]
org.eclipse.recommenders.rcp (2.4.6.v20170307-1041) "Code Recommenders UI" [Starting]
org.eclipse.recommenders.subwords.rcp (2.4.6.v20170307-1041) "Code Recommenders Subwords‐Completion UI" [Resolved]
org.eclipse.recommenders.types.rcp (2.4.6.v20170307-1041) "Code Recommenders Types‐Completion UI" [Resolved]
org.eclipse.recommenders.utils (2.4.6.v20170307-1041) "Code Recommenders Utilities" [Resolved]
org.eclipse.recommenders.utils.rcp (2.4.6.v20170307-1041) "Code Recommenders RCP Utilities" [Starting]
org.eclipse.rse (3.5.0.201403100950) "Remote System Explorer End-User Runtime" [Resolved]
org.eclipse.rse.connectorservice.dstore (3.1.301.201403100950) "RSE DStore Connector Service" [Starting]
org.eclipse.rse.connectorservice.local (2.1.400.201403100950) "RSE Local Connector Service" [Active]
org.eclipse.rse.connectorservice.ssh (2.1.300.201505220524) "RSE SSH Connector Service" [Starting]
org.eclipse.rse.connectorservice.telnet (1.2.300.201505220524) "RSE Telnet Connector Service" [Starting]
org.eclipse.rse.core (3.3.100.201603151753) "RSE Core" [Active]
org.eclipse.rse.doc.user (3.4.100.201403101646) "RSE User Guide" [Resolved]
org.eclipse.rse.dstore.security (3.0.400.201403100950) "RSE DStore SSL Support" [Starting]
org.eclipse.rse.efs (2.1.401.201507172212) "RSE Eclipse Filesystem (EFS) Provider" [Starting]
org.eclipse.rse.efs.ui (2.1.400.201403100950) "RSE Eclipse Filesystem (EFS) Provider UI Support" [Resolved]
org.eclipse.rse.files.ui (3.2.200.201507172213) "RSE Files UI" [Active]
org.eclipse.rse.importexport (1.2.300.201403100950) "RSE Import/Export" [Starting]
org.eclipse.rse.processes.ui (3.0.400.201403100950) "RSE Processes UI" [Starting]
org.eclipse.rse.services (3.3.0.201506120731) "RSE Services Framework" [Active]
org.eclipse.rse.services.dstore (3.3.0.201406041609) "RSE DStore Services" [Starting]
org.eclipse.rse.services.files.ftp (3.0.500.201403100950) "RSE FTP Service" [Starting]
org.eclipse.rse.services.local (2.2.1.201507180454) "RSE Local Services" [Active]
org.eclipse.rse.services.ssh (3.2.100.201403281521) "RSE SSH Services" [Starting]
org.eclipse.rse.services.telnet (2.0.400.201403100950) "RSE Telnet Service" [Starting]
org.eclipse.rse.shells.ui (3.0.500.201403271554) "RSE Shells UI" [Starting]
org.eclipse.rse.subsystems.files.core (3.3.1.201403100950) "RSE Files Core" [Active]
org.eclipse.rse.subsystems.files.dstore (2.1.300.201403100950) "RSE DStore Files" [Starting]
org.eclipse.rse.subsystems.files.ftp (2.2.100.201601281414) "RSE FTP Files" [Starting]
org.eclipse.rse.subsystems.files.local (2.1.300.201403251512) "RSE Local Files" [Active]
org.eclipse.rse.subsystems.files.ssh (2.1.300.201403100950) "RSE SSH Files" [Starting]
org.eclipse.rse.subsystems.processes.core (3.1.300.201403100950) "RSE Processes Core" [Starting]
org.eclipse.rse.subsystems.processes.dstore (2.1.400.201403100950) "RSE DStore Processes" [Starting]
org.eclipse.rse.subsystems.processes.local (2.1.400.201403100950) "RSE Local Processes" [Starting]
org.eclipse.rse.subsystems.processes.shell.linux (1.1.400.201403100950) "RSE Linux Shell Processes" [Starting]
org.eclipse.rse.subsystems.shells.core (3.1.300.201403271554) "RSE Shells Core" [Active]
org.eclipse.rse.subsystems.shells.dstore (2.1.400.201403100950) "RSE DStore Shells" [Starting]
org.eclipse.rse.subsystems.shells.local (2.1.400.201403100950) "RSE Local Shells" [Active]
org.eclipse.rse.subsystems.shells.ssh (2.1.400.201403100950) "RSE SSH Shells" [Starting]
org.eclipse.rse.subsystems.shells.telnet (1.2.300.201403100950) "RSE Telnet Shells" [Starting]
org.eclipse.rse.ui (3.3.300.201610252046) "RSE UI" [Active]
org.eclipse.rse.useractions (1.1.500.201403100950) "Remote System Explorer User Actions" [Starting]
org.eclipse.search (3.11.1.v20161113-1700) "Search Support" [Starting]
org.eclipse.swt (3.105.3.v20170228-0512) "Standard Widget Toolkit" [Resolved]
org.eclipse.swt.cocoa.macosx.x86_64 (3.105.3.v20170228-0512) "Standard Widget Toolkit for Mac OS X (Cocoa)" [Resolved]
org.eclipse.team.core (3.8.0.v20160418-1534) "Team Support Core" [Active]
org.eclipse.team.ui (3.8.0.v20160518-1906) "Team Support UI" [Active]
org.eclipse.text (3.6.0.v20160503-1849) "Text" [Resolved]
org.eclipse.tm.terminal.connector.local (4.2.0.201609191434) "Terminal Local Connector" [Starting]
org.eclipse.tm.terminal.connector.process (4.2.0.201609191434) "Terminal Process Connector" [Starting]
org.eclipse.tm.terminal.connector.serial (4.2.0.201609191434) "Terminal Serial Connector" [Starting]
org.eclipse.tm.terminal.connector.ssh (4.2.0.201609191434) "Terminal SSH Connector" [Starting]
org.eclipse.tm.terminal.connector.telnet (4.2.0.201609191434) "Terminal Telnet Connector" [Starting]
org.eclipse.tm.terminal.control (4.2.0.201609191434) "Terminal Control (Embeddable Widget)" [Starting]
org.eclipse.tm.terminal.view.core (4.2.0.201609191434) "Terminal View Core" [Starting]
org.eclipse.tm.terminal.view.ui (4.2.0.201609191434) "Terminal View" [Active]
org.eclipse.ui (3.108.1.v20160929-1045) "Eclipse UI" [Active]
org.eclipse.ui.browser (3.5.2.v20161114-0210) "Browser Support" [Starting]
org.eclipse.ui.cheatsheets (3.5.0.v20160504-0839) "Cheat Sheets" [Starting]
org.eclipse.ui.cocoa (1.1.100.v20151202-1450) "Eclipse UI MacOS X Enhancements" [Resolved]
org.eclipse.ui.console (3.6.201.v20161107-0337) "Console" [Active]
org.eclipse.ui.editors (3.10.1.v20161106-1856) "Default Text Editor" [Active]
org.eclipse.ui.externaltools (3.3.100.v20160518-1858) "External Tools" [Starting]
org.eclipse.ui.forms (3.7.1.v20161220-1635) "Eclipse Forms" [Resolved]
org.eclipse.ui.ide (3.12.3.v20170119-0935) "Eclipse IDE UI" [Active]
org.eclipse.ui.ide.application (1.1.101.v20160829-0827) "Eclipse IDE UI Application" [Active]
org.eclipse.ui.intro (3.5.2.v20161116-1147) "Welcome Framework" [Starting]
org.eclipse.ui.intro.quicklinks (1.0.0.v20160515-0255) "Quicklinks for the Welcome Framework" [Starting]
org.eclipse.ui.intro.universal (3.3.1.v20160829-1558) "Universal Welcome" [Starting]
org.eclipse.ui.monitoring (1.1.2.v20170203-1115) "UI Responsiveness Monitoring" [Active]
org.eclipse.ui.navigator (3.6.101.v20161006-1120) "Common Navigator View" [Active]
org.eclipse.ui.navigator.resources (3.5.101.v20161006-0640) "Navigator Workbench Components" [Active]
org.eclipse.ui.net (1.3.0.v20160426-1633) "Internet Connection Management UI" [Active]
org.eclipse.ui.themes (1.1.300.v20161107-1827) "Eclipse SDK Themes" [Active]
org.eclipse.ui.trace (1.0.400.v20160509-1055) "Equinox Dynamic Tracing Enablement UI" [Active]
org.eclipse.ui.views (3.8.102.v20170111-0801) "Views" [Resolved]
org.eclipse.ui.views.log (1.2.1.v20160829-0826) "Log View" [Active]
org.eclipse.ui.views.properties.tabbed (3.7.0.v20160310-0903) "Tabbed Properties View" [Starting]
org.eclipse.ui.workbench (3.108.3.v20170216-1539) "Eclipse Workbench" [Active]
org.eclipse.ui.workbench.texteditor (3.10.1.v20160818-1626) "Text Editor Framework" [Active]
org.eclipse.update.configurator (3.3.400.v20160506-0750) "Install/Update Configurator" [Active]
org.eclipse.userstorage (1.0.1.v20170201-1648) "Eclipse User Storage" [Active]
org.eclipse.userstorage.ui (1.0.1.v20170201-1648) "Eclipse User Storage UI" [Active]
org.eclipse.wst.command.env (1.0.500.v201505131719) "Environment Command Framework (headless)" [Starting]
org.eclipse.wst.command.env.core (1.0.300.v201505131719) "Environment Command Framework (core)" [Resolved]
org.eclipse.wst.command.env.doc.user (1.5.400.v201309242123) "Web services Axis Ant task documentation" [Starting]
org.eclipse.wst.command.env.infopop (1.0.200.v201309242123) "Web services UI" [Starting]
org.eclipse.wst.command.env.ui (1.1.200.v201503231435) "Environment Command Framework (GUI)" [Starting]
org.eclipse.wst.common.core (1.2.0.v200908251833) "WST Common Core Plug-in" [Active]
org.eclipse.wst.common.emf (1.2.500.v201701191735) "EMF Utilities" [Active]
org.eclipse.wst.common.emfworkbench.integration (1.2.101.v201107081800) "EMF Workbench Edit Plug-in" [Active]
org.eclipse.wst.common.environment (1.0.400.v200912181831) "Environment Plug-in" [Starting]
org.eclipse.wst.common.frameworks (1.2.200.v201304241450) "Common Frameworks" [Active]
org.eclipse.wst.common.frameworks.ui (1.2.400.v201504292002) "WTP UI Plug-in" [Active]
org.eclipse.wst.common.infopop (1.0.300.v201309101952) "Common WST infopops" [Starting]
org.eclipse.wst.common.modulecore (1.2.500.v201701032135) "Modulecore Plug-in" [Active]
org.eclipse.wst.common.modulecore.ui (1.0.300.v201505072128) "Modulecore UI Plug-in" [Starting]
org.eclipse.wst.common.project.facet.core (1.4.300.v201111030423) "Eclipse Faceted Project Framework" [Active]
org.eclipse.wst.common.project.facet.ui (1.4.600.v201505072140) "Eclipse Faceted Project Framework UI" [Starting]
org.eclipse.wst.common.snippets (1.2.300.v201602270217) "Snippets View" [Starting]
org.eclipse.wst.common.ui (1.1.500.v200911182011) "Eclipse Base UI extensions" [Starting]
org.eclipse.wst.common.uriresolver (1.2.200.v201505132009) "Common URI Resolver Framework" [Starting]
org.eclipse.wst.css.core (1.1.900.v201603171933) "Structured Source CSS Model" [Starting]
org.eclipse.wst.css.ui (1.0.1001.v201608060346) "SSE CSS Source Editor" [Starting]
org.eclipse.wst.doc.user (1.2.0.v201309112106) "Master User Doc TOC" [Starting]
org.eclipse.wst.dtd.core (1.1.700.v201211012112) "Structured Source DTD Core" [Starting]
org.eclipse.wst.dtd.ui (1.0.801.v201308100602) "SSE DTD Source Editor" [Starting]
org.eclipse.wst.dtd.ui.infopop (1.0.400.v201309112106) "DTD Editor infopops" [Resolved]
org.eclipse.wst.dtdeditor.doc.user (1.0.700.v201208081537) "DTD Editor documentation" [Resolved]
org.eclipse.wst.html.core (1.2.1.v201608061844) "Structured Source HTML Model" [Starting]
org.eclipse.wst.html.ui (1.0.1101.v201608060430) "HTML UI Source Editor" [Starting]
org.eclipse.wst.html.ui.infopop (1.0.201.v201409111852) "HTML editor infopops" [Resolved]
org.eclipse.wst.internet.cache (1.0.701.v201510130022) "Cache URI Resolver Plug-in" [Starting]
org.eclipse.wst.internet.monitor.core (1.0.600.v201309182039) "Monitor" [Starting]
org.eclipse.wst.internet.monitor.ui (1.0.700.v201309182039) "TCP/IP Monitor" [Starting]
org.eclipse.wst.jsdt.chromium (0.5.200.v201610211901) "Chromium Developer Tools SDK" [Resolved]
org.eclipse.wst.jsdt.chromium.debug (0.4.0.v201605131737) "Chromium JavaScript Remote Debugger" [Resolved]
org.eclipse.wst.jsdt.chromium.debug.core (0.5.200.v201701261810) "Chromium JavaScript Remote Debugger Core" [Starting]
org.eclipse.wst.jsdt.chromium.debug.js (0.1.200.v201610211901) "Chromium JavaScript front-end Debugger" [Starting]
org.eclipse.wst.jsdt.chromium.debug.jsdtbridge (0.5.200.v201610211901) "Chromium JavaScript Remote Debugger JSDT Formatter Bridge" [Resolved]
org.eclipse.wst.jsdt.chromium.debug.ui (0.6.200.v201701261810) "Chromium JavaScript Remote Debugger UI" [Starting]
org.eclipse.wst.jsdt.chromium.wip.eclipse (0.5.200.v201610212001) "Chromium Developer Tools SDK WIP Backend registry" [Resolved]
org.eclipse.wst.jsdt.chromium.wipbackend.dev (0.5.200.v201610212001) "Chromium Developer Tools SDK WIP backend (current development)" [Resolved]
org.eclipse.wst.jsdt.chromium.wipbackend.protocol_1_0 (0.5.200.v201610212001) "Chromium Developer Tools SDK WIP backend Protocol v. 1.0" [Resolved]
org.eclipse.wst.jsdt.core (2.0.200.v201612211424) "JavaScript Development Tools Core" [Starting]
org.eclipse.wst.jsdt.debug.core (3.2.200.v201610211901) "JavaScript Debug Core" [Starting]
org.eclipse.wst.jsdt.debug.crossfire (1.0.500.v201505071819) "Crossfire JavaScript Debug" [Starting]
org.eclipse.wst.jsdt.debug.rhino (1.0.500.v201605251607) "Rhino JavaScript Debug" [Starting]
org.eclipse.wst.jsdt.debug.rhino.debugger (1.0.600.v201604292217) "Rhino Debugger" [Resolved]
org.eclipse.wst.jsdt.debug.rhino.ui (1.0.500.v201604292217) "Rhino Debug UI" [Starting]
org.eclipse.wst.jsdt.debug.transport (1.0.300.v201502261613) "Debug Transport" [Resolved]
org.eclipse.wst.jsdt.debug.ui (1.0.600.v201605311817) "JavaScript Debug UI" [Starting]
org.eclipse.wst.jsdt.doc (2.0.200.v201610220243) "JavaScript Development Tools Documentation" [Resolved]
org.eclipse.wst.jsdt.js.bower (1.0.200.v201610220243) "Bower Tools" [Starting]
org.eclipse.wst.jsdt.js.cli (1.0.0.v201605192332) "CLI Launcher" [Starting]
org.eclipse.wst.jsdt.js.common (1.0.200.v201610211901) "Common Node Tools API" [Starting]
org.eclipse.wst.jsdt.js.grunt (1.0.200.v201610211901) "Eclipse Grunt Tools" [Starting]
org.eclipse.wst.jsdt.js.gulp (1.0.200.v201610211901) "Eclipse Gulp Tools" [Starting]
org.eclipse.wst.jsdt.js.node (1.0.200.v201610211901) "Node" [Starting]
org.eclipse.wst.jsdt.js.node.common (1.0.0.v201605131737) "Common Node.js Utilities" [Starting]
org.eclipse.wst.jsdt.js.npm (1.0.200.v201610211901) "npm Tools" [Starting]
org.eclipse.wst.jsdt.manipulation (1.0.601.v201602241911) "JavaScript Code Manipulation Functionality" [Starting]
org.eclipse.wst.jsdt.nashorn.extension (1.0.2.v201610280128) "Nashorn Classloader" [Resolved]
org.eclipse.wst.jsdt.support.firefox (1.0.501.v201602241911) "JSDT support for Mozilla FireFox" [Starting]
org.eclipse.wst.jsdt.support.ie (1.0.601.v201602241911) "JSDT support for Microsoft Internet Explorer" [Resolved]
org.eclipse.wst.jsdt.ui (2.0.200.v201612151739) "Eclipse JavaScript Development Tools" [Starting]
org.eclipse.wst.jsdt.web.core (1.0.801.v201602241914) "JSDT Web Support Core" [Starting]
org.eclipse.wst.jsdt.web.support.jsp (1.0.600.v201307151913) "JSDT support for JSP Plug-in" [Starting]
org.eclipse.wst.jsdt.web.ui (1.0.801.v201602241914) "JSDT Web Support UI" [Starting]
org.eclipse.wst.json.bower.core (1.0.0.v201605150457) "Bower Core" [Starting]
org.eclipse.wst.json.bower.ui (1.0.0.v201605201503) "Eclipse Bower Editors and Tools" [Starting]
org.eclipse.wst.json.core (1.0.2.v201612232230) "Structured Source JSON Model" [Starting]
org.eclipse.wst.json.eslint.core (1.0.0.v201605150457) "ESLint Core" [Starting]
org.eclipse.wst.json.eslint.ui (1.0.0.v201605201503) "Eclipse ESlint Editors and Tools" [Starting]
org.eclipse.wst.json.jshint.core (1.0.0.v201605150457) "JSHint Core" [Starting]
org.eclipse.wst.json.jshint.ui (1.0.0.v201605201503) "Eclipse JSHint Editors and Tools" [Starting]
org.eclipse.wst.json.npm.core (1.0.0.v201605150457) "NPM Core" [Starting]
org.eclipse.wst.json.npm.ui (1.0.0.v201605201503) "Eclipse NPM Editors and Tools" [Starting]
org.eclipse.wst.json.schemaprocessor (1.0.100.v201612232230) "JSON Schema Processor" [Starting]
org.eclipse.wst.json.ui (1.0.1.v201612232230) "Eclipse JSON Editors and Tools" [Starting]
org.eclipse.wst.server.core (1.9.0.v201610211907) "Server Core" [Starting]
org.eclipse.wst.server.discovery (1.3.0.v201606030549) "Plug-in Discovery Plug-in" [Starting]
org.eclipse.wst.server.http.core (1.0.300.v201606081655) "HTTP Server Support" [Starting]
org.eclipse.wst.server.http.ui (1.0.400.v201309182039) "HTTP Server UI Support" [Starting]
org.eclipse.wst.server.preview (1.1.400.v201703062119) "Preview Server Support" [Starting]
org.eclipse.wst.server.preview.adapter (1.1.300.v201606081655) "HTTP Preview Support" [Starting]
org.eclipse.wst.server.ui (1.5.307.v201611072017) "Server UI" [Starting]
org.eclipse.wst.server.ui.doc.user (1.1.600.v201309182117) "Server Tools documentation for Web Standard Tools" [Starting]
org.eclipse.wst.server.ui.infopop (1.1.200.v201309182117) "Server Tools infopops for Web Standard Tools" [Resolved]
org.eclipse.wst.sse.core (1.1.1000.v201608061842) "Structured Source Model" [Active]
org.eclipse.wst.sse.doc.user (1.1.100.v201208081537) "Structured text editor and snippets documentation" [Resolved]
org.eclipse.wst.sse.ui (1.3.500.v201605120129) "Structured Source Editor" [Starting]
org.eclipse.wst.sse.ui.infopop (1.0.300.v201309112106) "SSE infopops" [Resolved]
org.eclipse.wst.standard.schemas (1.0.700.v201304171715) "Standard Schemas and DTDs" [Resolved]
org.eclipse.wst.validation (1.2.700.v201508251749) "Validation Framework" [Active]
org.eclipse.wst.validation.infopop (1.0.300.v201309101952) "WST validation infopop plug-in" [Resolved]
org.eclipse.wst.validation.ui (1.2.500.v201310231452) "Validation Framework UI" [Starting]
org.eclipse.wst.web (1.1.800.v201312041437) "Simple Web Plug-in" [Active]
org.eclipse.wst.web.ui (1.1.601.v201602221748) "Eclipse Web Developer Tools" [Starting]
org.eclipse.wst.web.ui.infopop (1.0.300.v200805140206) "Static Web infopop" [Starting]
org.eclipse.wst.webtools.doc.user (1.0.500.v201208081537) "Web tools documentation" [Starting]
org.eclipse.wst.ws (1.1.400.v201503231435) "Web Services" [Starting]
org.eclipse.wst.ws.explorer (1.0.900.v201612121628) "Web Services Explorer" [Starting]
org.eclipse.wst.ws.infopop (1.0.400.v201309242123) "Web Services UI" [Starting]
org.eclipse.wst.ws.parser (1.0.600.v201505131719) "Web Services Description Parser" [Starting]
org.eclipse.wst.ws.service.policy (1.0.450.v201505131719) "Service Policy - Core" [Starting]
org.eclipse.wst.ws.service.policy.ui (1.0.500.v201505131719) "Service Policy - UI" [Starting]
org.eclipse.wst.ws.ui (1.1.300.v201503231435) "Web Services UI" [Starting]
org.eclipse.wst.wsdl (1.2.400.v201505131719) "WSDL Model" [Starting]
org.eclipse.wst.wsdl.ui (1.2.800.v201510282151) "WSDL UI" [Starting]
org.eclipse.wst.wsdl.ui.doc.user (1.0.850.v201309242123) "WSDL Editor Documentation" [Starting]
org.eclipse.wst.wsdl.validation (1.1.700.v201505131719) "WSDL Validator" [Starting]
org.eclipse.wst.wsi (1.0.600.v201505131719) "WSI Conformance Tools" [Starting]
org.eclipse.wst.wsi.ui (1.0.600.v201505131719) "Soap Monitor" [Starting]
org.eclipse.wst.wsi.ui.doc.user (1.0.750.v201309242123) "WS-I Validation Documentation" [Resolved]
org.eclipse.wst.xml.core (1.1.1001.v201702270442) "Structured Source XML Model" [Active]
org.eclipse.wst.xml.ui (1.1.700.v201604272318) "Eclipse XML Editors and Tools" [Starting]
org.eclipse.wst.xml.ui.infopop (1.0.400.v201309112106) "XML infopops" [Resolved]
org.eclipse.wst.xml.xpath.core (1.3.1.v201509231858) "XPath Core" [Starting]
org.eclipse.wst.xml.xpath.ui (1.1.102.v201509231858) "XPath UI" [Starting]
org.eclipse.wst.xml.xpath2 (1.1.0.v201309251557) "Eclipse XPath 2 Developers Tools" [Resolved]
org.eclipse.wst.xml.xpath2.processor (2.1.101.v201409111854) "PsychoPath XPath 2.0 Processor" [Resolved]
org.eclipse.wst.xml.xpath2.processor.doc.user (2.0.0.v201209212251) "XPath 2.0 (PsychoPath) User Documentation" [Resolved]
org.eclipse.wst.xml.xpath2.wtptypes (2.0.0.v201208081543) "XPath2 WTP ContentModel TypeModel Bridge" [Starting]
org.eclipse.wst.xmleditor.doc.user (1.0.700.v201208081537) "XML editor" [Resolved]
org.eclipse.wst.xsd.core (1.1.900.v201401141857) "XSD Core Plugin" [Starting]
org.eclipse.wst.xsd.ui (1.2.600.v201511240159) "XML Schema Editor" [Starting]
org.eclipse.wst.xsdeditor.doc.user (1.0.800.v201208081537) "XML schema editor" [Resolved]
org.eclipse.wst.xsl (1.2.0.v201309251559) "Eclipse XSL Developer Tools" [Resolved]
org.eclipse.wst.xsl.core (1.1.301.v201405151730) "XSL Core" [Starting]
org.eclipse.wst.xsl.debug.ui (1.0.302.v201304240928) "XSL Debugger UI" [Starting]
org.eclipse.wst.xsl.doc (1.0.100.v201309251559) "XSL User Documentation (Incubating)" [Resolved]
org.eclipse.wst.xsl.exslt.core (1.0.0.v201005240422) "EXSLT UI Extensions" [Starting]
org.eclipse.wst.xsl.exslt.ui (1.0.0.v201006012004) "EXSLT Core Extensions" [Starting]
org.eclipse.wst.xsl.jaxp.debug (1.0.300.v201304102131) "XSL JAXP Debugger" [Resolved]
org.eclipse.wst.xsl.jaxp.debug.ui (1.0.200.v201103081755) "XSL JAXP Debug UI" [Starting]
org.eclipse.wst.xsl.jaxp.launching (1.0.300.v201304102131) "XSL JAXP Launching" [Starting]
org.eclipse.wst.xsl.launching (1.1.0.v201304240928) "XSL Transform Launching" [Starting]
org.eclipse.wst.xsl.saxon (1.0.200.v201103081755) "XSL Saxon Support" [Resolved]
org.eclipse.wst.xsl.ui (1.1.301.v201304222136) "XSL Editor and Validation" [Starting]
org.eclipse.wst.xsl.xalan (1.0.100.v201208081544) "XSL Xalan Support" [Resolved]
org.eclipse.wtp.epp.package.capabilities (1.3.0.v201005102000) "Eclipse IDE for Java EE Capabilities" [Resolved]
org.eclipse.wtp.epp.package.jee.intro (1.3.0.v201006142040) "Eclipse IDE for Java EE Introduction" [Starting]
org.eclipse.wtp.javascript.capabilities (1.0.100.v201005102000) "JavaScript Capabilities" [Resolved]
org.eclipse.wtp.jee.capabilities (1.0.100.v201005102000) "Java EE Capabilities" [Resolved]
org.eclipse.wtp.web.capabilities (1.0.100.v201005102000) "Web Capabilities" [Resolved]
org.eclipse.wtp.xml.capabilities (1.0.100.v201005102000) "XML Capabilities" [Resolved]
org.eclipse.xsd (2.12.0.v20160526-0356) "XSD Model" [Starting]
org.eclipse.xsd.edit (2.8.0.v20160526-0356) "XSD Edit" [Starting]
org.eclipse.zest.core (1.5.300.201606061308) "Zest Core" [Resolved]
org.eclipse.zest.layouts (1.1.300.201606061308) "Zest Layouts" [Resolved]
org.hamcrest.core (1.3.0.v201303031735) "Hamcrest Core Library of Matchers" [Starting]
org.jdom (1.1.1.v201101151400) "JDOM" [Resolved]
org.json (1.0.0.v201011060100) "JSON Implementation for Java" [Resolved]
org.jsoup (1.7.2.v201411291515) "jsoup: Java HTML Parser" [Resolved]
org.junit (4.12.0.v201504281640) "JUnit Testing Framework" [Resolved]
org.mozilla.javascript (1.7.5.v201504281450) "Mozilla Rhino" [Resolved]
org.objectweb.asm (5.0.1.v201404251740) "ASM" [Resolved]
org.objectweb.asm.tree (5.0.1.v201404251740) "ASM Tree class visitor" [Resolved]
org.reactivestreams.reactive-streams (1.0.0.release) "reactive-streams" [Resolved]
org.sat4j.core (2.3.5.v201308161310) "SAT4J Core" [Resolved]
org.sat4j.pb (2.3.5.v201404071733) "SAT4J Pseudo" [Resolved]
org.slf4j.api (1.7.2.v20121108-1250) "SLF4J API" [Resolved]
org.slf4j.impl.log4j12 (1.7.2.v20131105-2200) "SLF4J LOG4J-12 Binding" [Resolved]
org.sonatype.m2e.mavenarchiver (0.17.2.201606141937-signed-20160830073346) "m2e connector for the mavenarchiver and pom properties" [Resolved]
org.springframework.aop (4.3.0.20160611-RELEASE) "Spring AOP" [Resolved]
org.springframework.beans (4.3.0.20160611-RELEASE) "Spring Beans" [Resolved]
org.springframework.context (4.3.0.20160611-RELEASE) "Spring Context" [Resolved]
org.springframework.context.support (4.3.0.20160611-RELEASE) "Spring Context Support" [Resolved]
org.springframework.core (4.3.0.20160611-RELEASE) "Spring Core" [Resolved]
org.springframework.data.core (1.11.4.20160223-RELEASE) "spring-data-commons" [Resolved]
org.springframework.expression (4.3.0.20160611-RELEASE) "Spring Expression Language" [Resolved]
org.springframework.ide.eclipse (3.8.4.201703310634-RELEASE) "Spring IDE" [Resolved]
org.springframework.ide.eclipse.aeri (3.8.4.201703310634-RELEASE) "Spring IDE Automated Error Reporting" [Resolved]
org.springframework.ide.eclipse.aop.core (3.8.4.201703310634-RELEASE) "Spring IDE AOP Core" [Active]
org.springframework.ide.eclipse.aop.ui (3.8.4.201703310634-RELEASE) "Spring IDE AOP UI" [Active]
org.springframework.ide.eclipse.aop.ui.matcher (3.8.4.201703310634-RELEASE) "Spring IDE AOP Pointcut Matcher" [Starting]
org.springframework.ide.eclipse.batch (3.8.4.201703310634-RELEASE) "Spring IDE Support for Spring Batch" [Starting]
org.springframework.ide.eclipse.beans.core (3.8.4.201703310634-RELEASE) "Spring IDE Beans Core" [Active]
org.springframework.ide.eclipse.beans.core.autowire (3.8.4.201703310634-RELEASE) "Spring IDE Autowiring Support (Core)" [Starting]
org.springframework.ide.eclipse.beans.core.metadata (3.8.4.201703310634-RELEASE) "Spring IDE Metadata Support (Core)" [Active]
org.springframework.ide.eclipse.beans.mylyn (3.8.4.201703310634-RELEASE) "Spring IDE Beans Mylyn Integration" [Starting]
org.springframework.ide.eclipse.beans.ui (3.8.4.201703310634-RELEASE) "Spring IDE Beans UI" [Active]
org.springframework.ide.eclipse.beans.ui.autowire (3.8.4.201703310634-RELEASE) "Spring IDE Autowiring Support (UI)" [Starting]
org.springframework.ide.eclipse.beans.ui.editor (3.8.4.201703310634-RELEASE) "Spring IDE Beans Config Editor" [Starting]
org.springframework.ide.eclipse.beans.ui.graph (3.8.4.201703310634-RELEASE) "Spring IDE Bean Dependency Graph" [Starting]
org.springframework.ide.eclipse.beans.ui.livegraph (3.8.4.201703310634-RELEASE) "Spring IDE Live Beans Graph" [Starting]
org.springframework.ide.eclipse.beans.ui.refactoring (3.8.4.201703310634-RELEASE) "Spring IDE Refactoring Support" [Starting]
org.springframework.ide.eclipse.beans.ui.search (3.8.4.201703310634-RELEASE) "Spring IDE Beans UI Search" [Starting]
org.springframework.ide.eclipse.bestpractices (3.8.4.201703310634-RELEASE) "Spring IDE Best Practices" [Starting]
org.springframework.ide.eclipse.boot (3.8.4.201703310634-RELEASE) "Boot" [Active]
org.springframework.ide.eclipse.boot.dash (3.8.4.201703310634-RELEASE) "Spring Boot Dashboard View" [Starting]
org.springframework.ide.eclipse.boot.launch (3.8.4.201703310634-RELEASE) "Boot Launch" [Starting]
org.springframework.ide.eclipse.boot.properties.editor (3.8.4.201703310634-RELEASE) "pluginName" [Active]
org.springframework.ide.eclipse.boot.properties.editor.yaml (3.8.4.201703310634-RELEASE) "Spring Boot Yaml" [Starting]
org.springframework.ide.eclipse.boot.templates (3.8.4.201703310634-RELEASE) "Templates" [Resolved]
org.springframework.ide.eclipse.boot.wizard (3.8.4.201703310634-RELEASE) "Boot UI Support" [Starting]
org.springframework.ide.eclipse.buildship (3.8.4.201703310634-RELEASE) "Spring IDE Buildship Integration" [Starting]
org.springframework.ide.eclipse.buildship20 (3.8.4.201703310634-RELEASE) "Spring IDE Buildship Integration" [Starting]
org.springframework.ide.eclipse.cloudfoundry.manifest.editor (3.8.4.201703310634-RELEASE) "Editor" [Starting]
org.springframework.ide.eclipse.config.core (3.8.4.201703310634-RELEASE) "Spring IDE Spring Configuration Editor (Core)" [Starting]
org.springframework.ide.eclipse.config.graph (3.8.4.201703310634-RELEASE) "Spring IDE Configuration Graphical Editing" [Starting]
org.springframework.ide.eclipse.config.ui (3.8.4.201703310634-RELEASE) "Spring IDE Spring Configuration Editor (UI)" [Active]
org.springframework.ide.eclipse.core (3.8.4.201703310634-RELEASE) "Spring IDE Core" [Active]
org.springframework.ide.eclipse.data.core (3.8.4.201703310634-RELEASE) "Spring IDE Spring Data Support" [Active]
org.springframework.ide.eclipse.doc (3.8.4.201703310634-RELEASE) "Spring Framework Reference Documentations" [Resolved]
org.springframework.ide.eclipse.editor.support (3.8.4.201703310634-RELEASE) "Editor" [Starting]
org.springframework.ide.eclipse.gradle (3.8.4.201703310634-RELEASE) "Spring IDE Gradle Integration" [Starting]
org.springframework.ide.eclipse.imports (3.8.4.201703310634-RELEASE) "Spring IDE Imports" [Active]
org.springframework.ide.eclipse.integration (3.8.4.201703310634-RELEASE) "Spring IDE Support for Spring Integration" [Starting]
org.springframework.ide.eclipse.maven (3.8.4.201703310634-RELEASE) "Spring IDE Maven Integration" [Active]
org.springframework.ide.eclipse.metadata (3.8.4.201703310634-RELEASE) "Spring IDE Spring Meta Data Extension" [Active]
org.springframework.ide.eclipse.mylyn (3.8.4.201703310634-RELEASE) "Spring IDE Mylyn Integration" [Starting]
org.springframework.ide.eclipse.quickfix (3.8.4.201703310634-RELEASE) "Spring IDE Quick Fixes" [Active]
org.springframework.ide.eclipse.security (3.8.4.201703310634-RELEASE) "Spring IDE Core Support for Spring Security" [Starting]
org.springframework.ide.eclipse.ui (3.8.4.201703310634-RELEASE) "Spring IDE UI" [Active]
org.springframework.ide.eclipse.webflow.core (3.8.4.201703310634-RELEASE) "Spring IDE Web Flow Core" [Active]
org.springframework.ide.eclipse.webflow.ui (3.8.4.201703310634-RELEASE) "Spring IDE Web Flow UI" [Starting]
org.springframework.ide.eclipse.webflow.ui.editor (3.8.4.201703310634-RELEASE) "Spring IDE Web Flow Config Editor" [Starting]
org.springframework.ide.eclipse.webflow.ui.graph (3.8.4.201703310634-RELEASE) "Spring IDE Web Flow UI Editor" [Starting]
org.springframework.ide.eclipse.wizard (3.8.4.201703310634-RELEASE) "Spring IDE Template Project Wizards" [Starting]
org.springframework.jdbc (4.3.0.20160611-RELEASE) "Spring JDBC" [Resolved]
org.springframework.jms (4.3.0.20160611-RELEASE) "Spring JMS" [Resolved]
org.springframework.orm (4.3.0.20160611-RELEASE) "Spring ORM" [Resolved]
org.springframework.oxm (4.3.0.20160611-RELEASE) "Spring Object/XML Mapping" [Resolved]
org.springframework.transaction (4.3.0.20160611-RELEASE) "Spring Transaction" [Resolved]
org.springframework.web (4.3.0.20160611-RELEASE) "Spring Web" [Resolved]
org.springframework.web.servlet (4.3.0.20160611-RELEASE) "Spring Web Servlet" [Resolved]
org.springsource.ide.eclipse.commons.cloudfoundry.client (3.8.4.201703310458-RELEASE) "Spring IDE Cloud Foundry Client" [Resolved]
org.springsource.ide.eclipse.commons.cloudfoundry.client.v2 (3.8.4.201703310634-RELEASE) "org.springsource.ide.eclipse.commons.cloudfoundry.client.v2" [Resolved]
org.springsource.ide.eclipse.commons.completions (3.8.4.201703310458-RELEASE) "Completions" [Starting]
org.springsource.ide.eclipse.commons.configurator (3.8.4.201703310458-RELEASE) "SpringSource Tool Suite Workspace Configuration" [Active]
org.springsource.ide.eclipse.commons.content.core (3.8.4.201703310458-RELEASE) "SpringSource Tool Suite Content (Core)" [Starting]
org.springsource.ide.eclipse.commons.core (3.8.4.201703310458-RELEASE) "SpringSource Tool Suite (Core)" [Active]
org.springsource.ide.eclipse.commons.frameworks.core (3.8.4.201703310458-RELEASE) "SpringSource Tool Suite Framework Support Core" [Active]
org.springsource.ide.eclipse.commons.frameworks.ui (3.8.4.201703310458-RELEASE) "SpringSource Tool Suite Framework Support (UI)" [Active]
org.springsource.ide.eclipse.commons.livexp (3.8.4.201703310458-RELEASE) "Eclipse Integration Commands - Livexp" [Active]
org.springsource.ide.eclipse.commons.ui (3.8.4.201703310458-RELEASE) "Spring Tool Suite Common UI Components" [Active]
org.tukaani.xz (1.3.0.v201308270617) "XZ data compression" [Resolved]
org.uddi4j (2.0.5.v200805270300) "UDDI4J" [Resolved]
org.w3c.css.sac (1.3.1.v200903091627) "W3C CSS SAC" [Resolved]
org.w3c.dom.events (3.0.0.draft20060413_v201105210656) "W3C DOM Level 3 Events" [Resolved]
org.w3c.dom.smil (1.0.1.v200903091627) "W3C SMIL DOM" [Resolved]
org.w3c.dom.svg (1.1.0.v201011041433) "W3C SVG DOM" [Resolved]
org.yaml.snakeyaml (1.14.0.v201604211500) "SnakeYAML" [Resolved]

*** User Preferences:
#Tue May 02 08:13:48 CDT 2017
\!/=
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.AddedLinesRegex=
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.CappingDisable=false
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.HighlightTokenChanges=true
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.IgnoreWhitespace=false
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.InitiallyShowAncestorPane=false
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.NavigationEndAction=prompt
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.NavigationEndActionLocal=loop
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.OpenStructureCompare=true
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.PathFilter=
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.RemovedLinesRegex=
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.SaveAllEditors=false
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.ShowPseudoConflicts=false
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.Swapped=false
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.SynchronizeScrolling=true
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.UseOutlineView=false
/bundle_defaults/org.eclipse.compare/org.eclipse.compare.UseSingleLine=true
/bundle_defaults/org.eclipse.core.net/nonProxiedHosts=localhost|127.0.0.1
/bundle_defaults/org.eclipse.core.net/proxiesEnabled=true
/bundle_defaults/org.eclipse.core.net/proxyData/HTTP/hasAuth=false
/bundle_defaults/org.eclipse.core.net/proxyData/HTTP/port=-1
/bundle_defaults/org.eclipse.core.net/proxyData/HTTPS/hasAuth=false
/bundle_defaults/org.eclipse.core.net/proxyData/HTTPS/port=-1
/bundle_defaults/org.eclipse.core.net/proxyData/SOCKS/hasAuth=false
/bundle_defaults/org.eclipse.core.net/proxyData/SOCKS/port=-1
/bundle_defaults/org.eclipse.core.net/systemProxiesEnabled=true
/bundle_defaults/org.eclipse.core.resources/delta.expiration=2592000000
/bundle_defaults/org.eclipse.core.resources/description.applyfilestatepolicy=true
/bundle_defaults/org.eclipse.core.resources/description.autobuilding=true
/bundle_defaults/org.eclipse.core.resources/description.buildorder=
/bundle_defaults/org.eclipse.core.resources/description.defaultbuildorder=true
/bundle_defaults/org.eclipse.core.resources/description.disableLinking=false
/bundle_defaults/org.eclipse.core.resources/description.filestatelongevity=604800000
/bundle_defaults/org.eclipse.core.resources/description.maxbuilditerations=10
/bundle_defaults/org.eclipse.core.resources/description.maxfilestates=50
/bundle_defaults/org.eclipse.core.resources/description.maxfilestatesize=1048576
/bundle_defaults/org.eclipse.core.resources/description.snapshotinterval=300000
/bundle_defaults/org.eclipse.core.resources/encoding=
/bundle_defaults/org.eclipse.core.resources/refresh.enabled=false
/bundle_defaults/org.eclipse.core.resources/refresh.lightweight.enabled=false
/bundle_defaults/org.eclipse.core.resources/snapshots.operations=100
/bundle_defaults/org.eclipse.egit.core/core_autoIgnoreDerivedResources=true
/bundle_defaults/org.eclipse.egit.core/core_autoShareProjects=true
/bundle_defaults/org.eclipse.egit.core/core_auto_stage_deletion=false
/bundle_defaults/org.eclipse.egit.core/core_auto_stage_moves=true
/bundle_defaults/org.eclipse.egit.core/core_defaultRepositoryDir=/Users/m134910/git
/bundle_defaults/org.eclipse.egit.core/core_deltaBaseCacheLimit=10485760
/bundle_defaults/org.eclipse.egit.core/core_packedGitLimit=10485760
/bundle_defaults/org.eclipse.egit.core/core_packedGitMMAP=false
/bundle_defaults/org.eclipse.egit.core/core_packedGitWindowSize=8192
/bundle_defaults/org.eclipse.egit.core/core_streamFileThreshold=52428800
/bundle_defaults/org.eclipse.egit.ui/Blame_IgnoreWhitespace=false
/bundle_defaults/org.eclipse.egit.ui/CloneWizard_ShowDetailedFailureDialog=true
/bundle_defaults/org.eclipse.egit.ui/CloneWizard_StoreInSecureStore=false
/bundle_defaults/org.eclipse.egit.ui/HistoryView_MaxBranchLength=18
/bundle_defaults/org.eclipse.egit.ui/HistoryView_MaxDiffLines=1000
/bundle_defaults/org.eclipse.egit.ui/HistoryView_MaxNumberOfCommmits=10000
/bundle_defaults/org.eclipse.egit.ui/HistoryView_MaxTagLength=18
/bundle_defaults/org.eclipse.egit.ui/HistoryView_ShowBranchSequence=true
/bundle_defaults/org.eclipse.egit.ui/HistoryView_ShowTagSequence=false
/bundle_defaults/org.eclipse.egit.ui/RebaseInteractive_SyncWithSelection=true
/bundle_defaults/org.eclipse.egit.ui/StagingView_CompareMode=true
/bundle_defaults/org.eclipse.egit.ui/StagingView_FileNameMode=true
/bundle_defaults/org.eclipse.egit.ui/StagingView_MaxLimitListMode=10000
/bundle_defaults/org.eclipse.egit.ui/StagingView_Presentation=LIST
/bundle_defaults/org.eclipse.egit.ui/StagingView_Presentation_Changed=false
/bundle_defaults/org.eclipse.egit.ui/always_use_staging_view=true
/bundle_defaults/org.eclipse.egit.ui/auto_stage_on_commit=true
/bundle_defaults/org.eclipse.egit.ui/blockCommit=false
/bundle_defaults/org.eclipse.egit.ui/blockCommitCombo=2
/bundle_defaults/org.eclipse.egit.ui/checkBeforeCommitting=false
/bundle_defaults/org.eclipse.egit.ui/commit_dialog_hard_wrap_message=true
/bundle_defaults/org.eclipse.egit.ui/commit_dialog_history_size=10
/bundle_defaults/org.eclipse.egit.ui/commit_dialog_signed_off_by=false
/bundle_defaults/org.eclipse.egit.ui/commit_dialog_warn_about_message_second_line=true
/bundle_defaults/org.eclipse.egit.ui/date_format=yyyy-MM-dd HH\:mm\:ss
/bundle_defaults/org.eclipse.egit.ui/date_format_choice=CUSTOM
/bundle_defaults/org.eclipse.egit.ui/decorator_filetext_decoration={dirty\:>} {name}
/bundle_defaults/org.eclipse.egit.ui/decorator_foldertext_decoration={dirty\:>} {name}
/bundle_defaults/org.eclipse.egit.ui/decorator_projecttext_decoration={dirty\:>} {name} [{repository }{branch}{ branch_status}]
/bundle_defaults/org.eclipse.egit.ui/decorator_recompute_ancestors=true
/bundle_defaults/org.eclipse.egit.ui/decorator_show_assume_valid_icon=true
/bundle_defaults/org.eclipse.egit.ui/decorator_show_conflicts_icon=true
/bundle_defaults/org.eclipse.egit.ui/decorator_show_dirty_icon=false
/bundle_defaults/org.eclipse.egit.ui/decorator_show_staged_icon=true
/bundle_defaults/org.eclipse.egit.ui/decorator_show_tracked_icon=true
/bundle_defaults/org.eclipse.egit.ui/decorator_show_untracked_icon=true
/bundle_defaults/org.eclipse.egit.ui/decorator_submoduletext_decoration={dirty\:>} {name} [{branch}{ branch_status}]{ short_message}
/bundle_defaults/org.eclipse.egit.ui/enable_logical_model=true
/bundle_defaults/org.eclipse.egit.ui/findtoolbar_find_in=0
/bundle_defaults/org.eclipse.egit.ui/findtoolbar_ignore_case=true
/bundle_defaults/org.eclipse.egit.ui/merge_mode=2
/bundle_defaults/org.eclipse.egit.ui/refesh_on_index_change=true
/bundle_defaults/org.eclipse.egit.ui/refesh_only_when_active=true
/bundle_defaults/org.eclipse.egit.ui/remote_connection_timeout=30
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_compare_mode=false
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_follow_renames=true
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_graph_split=500,500
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_rev_split=700,300
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_additionalrefs=false
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_all_branches=false
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_comment_wrap=true
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_email_addresses=false
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_notes=false
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_relative_date=true
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_rev_comment=true
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_rev_detail=true
/bundle_defaults/org.eclipse.egit.ui/resourcehistory_show_tooltips=false
/bundle_defaults/org.eclipse.egit.ui/restore_projects_on_checkout=true
/bundle_defaults/org.eclipse.egit.ui/show_checkout_confirmation=true
/bundle_defaults/org.eclipse.egit.ui/show_detached_head_warning=true
/bundle_defaults/org.eclipse.egit.ui/show_home_drive_warning=true
/bundle_defaults/org.eclipse.egit.ui/show_initial_config_dialog=true
/bundle_defaults/org.eclipse.egit.ui/show_rebase_confirm=true
/bundle_defaults/org.eclipse.egit.ui/show_running_launch_on_checkout_warning=true
/bundle_defaults/org.eclipse.egit.ui/sync_view_changeset_pattern=[{author}] ({date}) {short_message}
/bundle_defaults/org.eclipse.egit.ui/sync_view_fetch_before_launch=true
/bundle_defaults/org.eclipse.egit.ui/sync_view_show_changeset_model=false
/bundle_defaults/org.eclipse.egit.ui/warnBeforeCommitting=2
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk.scheduler/download=false
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk.scheduler/enabled=false
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk.scheduler/remindElapsedTime=30 minutes
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk.scheduler/remindOnSchedule=false
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk.scheduler/schedule=on-startup
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk.scheduler/showUpdateWizard=false
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk/allowNonOKPlan=prompt
/bundle_defaults/org.eclipse.equinox.p2.ui.sdk/showLatestVersion=true
/bundle_defaults/org.eclipse.jdt.apt.core/org.eclipse.jdt.apt.aptEnabled=false
/bundle_defaults/org.eclipse.jdt.apt.core/org.eclipse.jdt.apt.genSrcDir=.apt_generated
/bundle_defaults/org.eclipse.jdt.apt.core/org.eclipse.jdt.apt.processorOptions=
/bundle_defaults/org.eclipse.jdt.apt.core/org.eclipse.jdt.apt.reconcileEnabled=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.builder.cleanOutputFolder=clean
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.builder.duplicateResourceTask=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.builder.invalidClasspath=abort
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.builder.recreateModifiedClassFileInOutputFolder=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.builder.resourceCopyExclusionFilter=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.circularClasspath=error
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.classpath.exclusionPatterns=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.classpath.multipleOutputLocations=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.classpath.outputOverlappingAnotherSource=error
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.argumentPrefixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.argumentSuffixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.camelCaseMatch=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.deprecationCheck=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.discouragedReferenceCheck=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.fieldPrefixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.fieldSuffixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.forbiddenReferenceCheck=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.forceImplicitQualification=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.localPrefixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.localSuffixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.staticFieldPrefixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.staticFieldSuffixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.staticFinalFieldPrefixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.staticFinalFieldSuffixes=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.substringMatch=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.suggestStaticImports=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.visibilityCheck=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.inheritNullAnnotations=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.missingNonNullByDefaultAnnotation=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.nonnull=org.eclipse.jdt.annotation.NonNull
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.nonnull.secondary=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.nonnullbydefault=org.eclipse.jdt.annotation.NonNullByDefault
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.nonnullbydefault.secondary=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.nullable=org.eclipse.jdt.annotation.Nullable
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.nullable.secondary=
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.annotation.nullanalysis=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.inlineJsrBytecode=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.lambda.genericSignature=do not generate
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.methodParameters=do not generate
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.shareCommonFinallyBlocks=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.targetPlatform=1.2
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.unusedLocal=preserve
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.compliance=1.4
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.debug.lineNumber=generate
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.debug.localVariable=generate
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.debug.sourceFile=generate
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.doc.comment.support=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.emulateJavacBug8031744=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.generateClassFiles=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.maxProblemPerUnit=100
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.annotationSuperInterface=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.assertIdentifier=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.autoboxing=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.comparingIdentical=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.deadCode=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.deadCodeInTrivialIfStatement=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.deprecation=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.deprecationInDeprecatedCode=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.deprecationWhenOverridingDeprecatedMethod=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.discouragedReference=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.emptyStatement=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.enumIdentifier=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.explicitlyClosedAutoCloseable=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.fallthroughCase=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.fatalOptionalError=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.fieldHiding=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.finalParameterBound=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.finallyBlockNotCompletingNormally=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.forbiddenReference=error
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.hiddenCatchBlock=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.includeNullInfoFromAsserts=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.incompatibleNonInheritedInterfaceMethod=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.incompleteEnumSwitch=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.indirectStaticAccess=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.invalidJavadoc=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.invalidJavadocTags=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.invalidJavadocTagsDeprecatedRef=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.invalidJavadocTagsNotVisibleRef=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.invalidJavadocTagsVisibility=public
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.localVariableHiding=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.methodWithConstructorName=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingDefaultCase=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingDeprecatedAnnotation=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingEnumCaseDespiteDefault=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingHashCodeMethod=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocComments=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocCommentsOverriding=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocCommentsVisibility=public
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocTagDescription=return_tag
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocTags=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocTagsMethodTypeParameters=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocTagsOverriding=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingJavadocTagsVisibility=public
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingOverrideAnnotation=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingOverrideAnnotationForInterfaceMethodImplementation=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingSerialVersion=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.missingSynchronizedOnInheritedMethod=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.noEffectAssignment=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.noImplicitStringConversion=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.nonExternalizedStringLiteral=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.nonnullParameterAnnotationDropped=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.nonnullTypeVariableFromLegacyInvocation=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.nullAnnotationInferenceConflict=error
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.nullReference=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.nullSpecViolation=error
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.nullUncheckedConversion=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.overridingMethodWithoutSuperInvocation=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.overridingPackageDefaultMethod=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.parameterAssignment=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.pessimisticNullAnalysisForFreeTypeVariables=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.possibleAccidentalBooleanAssignment=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.potentialNullReference=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.potentiallyUnclosedCloseable=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.rawTypeReference=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.redundantNullAnnotation=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.redundantNullCheck=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.redundantSpecificationOfTypeArguments=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.redundantSuperinterface=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.reportMethodCanBePotentiallyStatic=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.reportMethodCanBeStatic=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.specialParameterHidingField=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.staticAccessReceiver=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.suppressOptionalErrors=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.suppressWarnings=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.syntacticNullAnalysisForFields=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.syntheticAccessEmulation=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.tasks=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.typeParameterHiding=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unavoidableGenericTypeProblems=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.uncheckedTypeOperation=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unclosedCloseable=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.undocumentedEmptyBlock=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unhandledWarningToken=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.uninternedIdentityComparison=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unnecessaryElse=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unnecessaryTypeCheck=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unqualifiedFieldAccess=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedDeclaredThrownException=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedDeclaredThrownExceptionExemptExceptionAndThrowable=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedDeclaredThrownExceptionIncludeDocCommentReference=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedDeclaredThrownExceptionWhenOverriding=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedExceptionParameter=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedImport=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedLabel=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedLocal=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedObjectAllocation=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedParameter=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedParameterIncludeDocCommentReference=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedParameterWhenImplementingAbstract=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedParameterWhenOverridingConcrete=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedPrivateMember=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedTypeArgumentsForMethodInvocation=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedTypeParameter=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.unusedWarningToken=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.varargsArgumentNeedCast=warning
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.processAnnotations=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.source=1.3
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.storeAnnotations=disabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.taskCaseSensitive=enabled
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.taskPriorities=NORMAL,HIGH,NORMAL
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.taskTags=TODO,FIXME,XXX
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.computeJavaBuildOrder=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.align_fields_grouping_blank_lines=2147483647
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.align_type_members_on_columns=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_arguments_in_allocation_expression=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_arguments_in_annotation=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_arguments_in_enum_constant=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_arguments_in_explicit_constructor_call=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_arguments_in_method_invocation=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_arguments_in_qualified_allocation_expression=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_assignment=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_binary_expression=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_compact_if=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_conditional_expression=80
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_enum_constants=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_expressions_in_array_initializer=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_expressions_in_for_loop_header=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_method_declaration=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_multiple_fields=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_parameterized_type_references=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_parameters_in_constructor_declaration=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_parameters_in_method_declaration=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_resources_in_try=80
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_selector_in_method_invocation=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_superclass_in_type_declaration=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_superinterfaces_in_enum_declaration=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_superinterfaces_in_type_declaration=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_throws_clause_in_constructor_declaration=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_throws_clause_in_method_declaration=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_type_arguments=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_type_parameters=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.alignment_for_union_type_in_multicatch=16
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_after_imports=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_after_package=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_before_field=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_before_first_class_body_declaration=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_before_imports=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_before_member_type=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_before_method=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_before_new_chunk=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_before_package=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_between_import_groups=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.blank_lines_between_type_declarations=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_annotation_type_declaration=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_anonymous_type_declaration=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_array_initializer=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_block=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_block_in_case=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_constructor_declaration=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_enum_constant=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_enum_declaration=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_lambda_body=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_method_declaration=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_switch=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.brace_position_for_type_declaration=end_of_line
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.clear_blank_lines_in_block_comment=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.clear_blank_lines_in_javadoc_comment=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.format_block_comments=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.format_header=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.format_html=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.format_javadoc_comments=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.format_line_comments=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.format_source_code=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.indent_parameter_description=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.indent_root_tags=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.insert_new_line_before_root_tags=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.insert_new_line_for_parameter=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.line_length=80
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.new_lines_at_block_boundaries=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.new_lines_at_javadoc_boundaries=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.comment.preserve_white_space_between_code_and_line_comments=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.compact_else_if=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.continuation_indentation=2
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.continuation_indentation_for_array_initializer=2
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.disabling_tag=@formatter\:off
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.enabling_tag=@formatter\:on
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.format_guardian_clause_on_one_line=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.format_line_comment_starting_on_first_column=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_annotation_declaration_header=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_enum_constant_header=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_enum_declaration_header=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_type_header=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_breaks_compare_to_cases=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_empty_lines=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_statements_compare_to_block=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_statements_compare_to_body=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_cases=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_switch=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.indentation.size=4
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_enum_constant=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_field=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_local_variable=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_method=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_package=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_parameter=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_type=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_label=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_opening_brace_in_array_initializer=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_after_type_annotation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_at_end_of_file_if_missing=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_before_catch_in_try_statement=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_before_closing_brace_in_array_initializer=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_before_else_in_if_statement=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_before_finally_in_try_statement=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_before_while_in_do_statement=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_in_empty_annotation_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_in_empty_anonymous_type_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_in_empty_block=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_in_empty_enum_constant=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_in_empty_enum_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_in_empty_method_body=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_new_line_in_empty_type_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_and_in_type_parameter=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_assignment_operator=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_at_in_annotation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_at_in_annotation_type_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_binary_operator=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_closing_angle_bracket_in_type_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_closing_angle_bracket_in_type_parameters=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_closing_brace_in_block=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_closing_paren_in_cast=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_colon_in_assert=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_colon_in_case=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_colon_in_conditional=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_colon_in_for=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_colon_in_labeled_statement=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_allocation_expression=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_annotation=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_array_initializer=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_constructor_declaration_parameters=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_constructor_declaration_throws=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_enum_constant_arguments=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_enum_declarations=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_explicitconstructorcall_arguments=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_for_increments=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_for_inits=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_method_declaration_parameters=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_method_declaration_throws=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_method_invocation_arguments=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_multiple_field_declarations=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_multiple_local_declarations=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_parameterized_type_reference=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_superinterfaces=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_type_arguments=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_comma_in_type_parameters=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_ellipsis=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_lambda_arrow=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_angle_bracket_in_parameterized_type_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_angle_bracket_in_type_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_angle_bracket_in_type_parameters=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_brace_in_array_initializer=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_bracket_in_array_allocation_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_bracket_in_array_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_annotation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_cast=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_catch=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_constructor_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_enum_constant=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_for=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_if=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_method_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_method_invocation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_parenthesized_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_switch=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_synchronized=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_try=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_while=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_postfix_operator=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_prefix_operator=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_question_in_conditional=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_question_in_wildcard=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_semicolon_in_for=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_semicolon_in_try_resources=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_after_unary_operator=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_and_in_type_parameter=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_assignment_operator=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_at_in_annotation_type_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_binary_operator=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_angle_bracket_in_parameterized_type_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_angle_bracket_in_type_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_angle_bracket_in_type_parameters=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_brace_in_array_initializer=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_bracket_in_array_allocation_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_bracket_in_array_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_annotation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_cast=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_catch=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_constructor_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_enum_constant=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_for=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_if=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_method_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_method_invocation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_parenthesized_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_switch=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_synchronized=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_try=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_while=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_colon_in_assert=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_colon_in_case=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_colon_in_conditional=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_colon_in_default=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_colon_in_for=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_colon_in_labeled_statement=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_allocation_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_annotation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_array_initializer=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_constructor_declaration_parameters=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_constructor_declaration_throws=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_enum_constant_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_enum_declarations=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_explicitconstructorcall_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_for_increments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_for_inits=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_method_declaration_parameters=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_method_declaration_throws=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_method_invocation_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_multiple_field_declarations=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_multiple_local_declarations=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_parameterized_type_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_superinterfaces=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_type_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_comma_in_type_parameters=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_ellipsis=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_lambda_arrow=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_angle_bracket_in_parameterized_type_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_angle_bracket_in_type_arguments=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_angle_bracket_in_type_parameters=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_annotation_type_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_anonymous_type_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_array_initializer=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_block=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_constructor_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_enum_constant=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_enum_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_method_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_switch=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_type_declaration=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_bracket_in_array_allocation_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_bracket_in_array_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_bracket_in_array_type_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_annotation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_annotation_type_member_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_catch=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_constructor_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_enum_constant=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_for=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_if=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_method_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_method_invocation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_parenthesized_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_switch=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_synchronized=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_try=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_while=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_parenthesized_expression_in_return=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_parenthesized_expression_in_throw=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_postfix_operator=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_prefix_operator=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_question_in_conditional=insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_question_in_wildcard=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_semicolon=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_semicolon_in_for=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_semicolon_in_try_resources=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_before_unary_operator=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_brackets_in_array_type_reference=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_empty_braces_in_array_initializer=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_empty_brackets_in_array_allocation_expression=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_annotation_type_member_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_constructor_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_enum_constant=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_method_declaration=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_method_invocation=do not insert
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.join_lines_in_comments=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.join_wrapped_lines=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.keep_else_statement_on_same_line=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.keep_empty_array_initializer_on_one_line=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.keep_imple_if_on_one_line=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.keep_then_statement_on_same_line=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.lineSplit=120
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.never_indent_block_comments_on_first_column=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.never_indent_line_comments_on_first_column=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.number_of_blank_lines_at_beginning_of_method_body=0
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.number_of_empty_lines_to_preserve=1
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_annotation=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_catch_clause=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_enum_constant_declaration=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_for_statment=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_if_while_statement=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_lambda_declaration=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_method_delcaration=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_method_invocation=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_switch_statement=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.parentheses_positions_in_try_clause=common_lines
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.put_empty_statement_on_new_line=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.tabulation.char=tab
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.tabulation.size=4
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.use_on_off_tags=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.use_tabs_only_for_leading_indentations=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.wrap_before_assignment_operator=false
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.wrap_before_binary_operator=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.wrap_before_conditional_operator=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.wrap_before_or_operator_multicatch=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.formatter.wrap_outer_expressions_when_nested=true
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.incompatibleJDKLevel=ignore
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.incompleteClasspath=error
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.javaFormatter=org.eclipse.jdt.core.defaultJavaFormatter
/bundle_defaults/org.eclipse.jdt.core/org.eclipse.jdt.core.timeoutForParameterNameFromAttachedJavadoc=50
/bundle_defaults/org.eclipse.jdt.ui/CallHierarchy.anonymousExpandWithConstructors=true
/bundle_defaults/org.eclipse.jdt.ui/CallHierarchy.defaultExpandWithConstructorsMembers=java.lang.Runnable.run;java.util.concurrent.Callable.call;org.eclipse.swt.widgets.Listener.handleEvent
/bundle_defaults/org.eclipse.jdt.ui/JavaEditor.ShowTemporaryProblem=true
/bundle_defaults/org.eclipse.jdt.ui/JavaEditor.SyncOutlineOnCursorMove=true
/bundle_defaults/org.eclipse.jdt.ui/JavaUI.update=JavaUI.update.whileEditing
/bundle_defaults/org.eclipse.jdt.ui/PackagesView.pkgNamePatternForPackagesView=
/bundle_defaults/org.eclipse.jdt.ui/Refactor.lightweight=true
/bundle_defaults/org.eclipse.jdt.ui/Refactoring.ErrorPage.severityThreshold=2
/bundle_defaults/org.eclipse.jdt.ui/Refactoring.savealleditors=false
/bundle_defaults/org.eclipse.jdt.ui/Search.usereducemenu=true
/bundle_defaults/org.eclipse.jdt.ui/addJavaDocTags=true
/bundle_defaults/org.eclipse.jdt.ui/autoFormatJavaDocs=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_default_serial_version_id=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_generated_serial_version_id=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_missing_annotations=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_missing_deprecated_annotations=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_missing_methods=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_missing_nls_tags=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_missing_override_annotations=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_missing_override_annotations_interface_methods=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.add_serial_version_id=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.always_use_blocks=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.always_use_parentheses_in_expressions=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.always_use_this_for_non_static_field_access=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.always_use_this_for_non_static_method_access=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.convert_functional_interfaces=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.convert_to_enhanced_for_loop=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.correct_indentation=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.format_source_code=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.format_source_code_changes_only=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.insert_inferred_type_arguments=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.make_local_variable_final=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.make_parameters_final=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.make_private_fields_final=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.make_type_abstract_if_missing_method=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.make_variable_declarations_final=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.never_use_blocks=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.never_use_parentheses_in_expressions=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.on_save_profile_id=org.eclipse.jdt.ui.default.save_participant_clean_up_profile
/bundle_defaults/org.eclipse.jdt.ui/cleanup.organize_imports=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.qualify_static_field_accesses_with_declaring_class=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.qualify_static_member_accesses_through_instances_with_declaring_class=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.qualify_static_member_accesses_through_subtypes_with_declaring_class=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.qualify_static_member_accesses_with_declaring_class=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.qualify_static_method_accesses_with_declaring_class=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_private_constructors=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_redundant_type_arguments=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_trailing_whitespaces=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_trailing_whitespaces_all=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_trailing_whitespaces_ignore_empty=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unnecessary_casts=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unnecessary_nls_tags=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unused_imports=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unused_local_variables=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unused_private_fields=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unused_private_members=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unused_private_methods=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.remove_unused_private_types=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.showwizard=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.sort_members=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.sort_members_all=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_anonymous_class_creation=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_blocks=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_blocks_only_for_return_and_throw=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_lambda=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_parentheses_in_expressions=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_this_for_non_static_field_access=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_this_for_non_static_field_access_only_if_necessary=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_this_for_non_static_method_access=false
/bundle_defaults/org.eclipse.jdt.ui/cleanup.use_this_for_non_static_method_access_only_if_necessary=true
/bundle_defaults/org.eclipse.jdt.ui/cleanup_profile=org.eclipse.jdt.ui.default.eclipse_clean_up_profile
/bundle_defaults/org.eclipse.jdt.ui/closeBraces=true
/bundle_defaults/org.eclipse.jdt.ui/closeBrackets=true
/bundle_defaults/org.eclipse.jdt.ui/closeJavaDocs=true
/bundle_defaults/org.eclipse.jdt.ui/closeStrings=true
/bundle_defaults/org.eclipse.jdt.ui/content_assist_add_import=true
/bundle_defaults/org.eclipse.jdt.ui/content_assist_autoactivation=true
/bundle_defaults/org.eclipse.jdt.ui/content_assist_autoactivation_delay=0
/bundle_defaults/org.eclipse.jdt.ui/content_assist_autoactivation_triggers_java=.
/bundle_defaults/org.eclipse.jdt.ui/content_assist_autoactivation_triggers_javadoc=@\#
/bundle_defaults/org.eclipse.jdt.ui/content_assist_autoinsert=true
/bundle_defaults/org.eclipse.jdt.ui/content_assist_case_sensitivity=false
/bundle_defaults/org.eclipse.jdt.ui/content_assist_category_order=org.eclipse.jdt.ui.spellingProposalCategory\:65545\u0000org.eclipse.jdt.ui.javaTypeProposalCategory\:65540\u0000org.eclipse.jdt.ui.javaNoTypeProposalCategory\:65539\u0000org.eclipse.jdt.ui.textProposalCategory\:65541\u0000org.eclipse.jdt.ui.javaAllProposalCategory\:65542\u0000org.eclipse.jdt.ui.templateProposalCategory\:2\u0000org.eclipse.jdt.ui.swtProposalCategory\:3\u0000
/bundle_defaults/org.eclipse.jdt.ui/content_assist_completion_replacement_background=255,255,0
/bundle_defaults/org.eclipse.jdt.ui/content_assist_completion_replacement_foreground=255,0,0
/bundle_defaults/org.eclipse.jdt.ui/content_assist_disabled_computers=org.eclipse.jdt.ui.textProposalCategory\u0000org.eclipse.jdt.ui.javaTypeProposalCategory\u0000org.eclipse.jdt.ui.javaNoTypeProposalCategory\u0000
/bundle_defaults/org.eclipse.jdt.ui/content_assist_favorite_static_members=
/bundle_defaults/org.eclipse.jdt.ui/content_assist_fill_method_arguments=true
/bundle_defaults/org.eclipse.jdt.ui/content_assist_guess_method_arguments=false
/bundle_defaults/org.eclipse.jdt.ui/content_assist_insert_completion=true
/bundle_defaults/org.eclipse.jdt.ui/content_assist_lru_history=
/bundle_defaults/org.eclipse.jdt.ui/content_assist_parameters_background=255,255,255
/bundle_defaults/org.eclipse.jdt.ui/content_assist_parameters_foreground=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/content_assist_prefix_completion=false
/bundle_defaults/org.eclipse.jdt.ui/content_assist_proposals_background=255,255,255
/bundle_defaults/org.eclipse.jdt.ui/content_assist_proposals_foreground=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/content_assist_show_visible_proposals=true
/bundle_defaults/org.eclipse.jdt.ui/content_assist_sorter=org.eclipse.jdt.ui.RelevanceSorter
/bundle_defaults/org.eclipse.jdt.ui/editor_annotation_roll_over=false
/bundle_defaults/org.eclipse.jdt.ui/editor_folding_default_headers=true
/bundle_defaults/org.eclipse.jdt.ui/editor_folding_default_imports=true
/bundle_defaults/org.eclipse.jdt.ui/editor_folding_default_innertypes=false
/bundle_defaults/org.eclipse.jdt.ui/editor_folding_default_javadoc=false
/bundle_defaults/org.eclipse.jdt.ui/editor_folding_default_methods=false
/bundle_defaults/org.eclipse.jdt.ui/editor_folding_enabled=true
/bundle_defaults/org.eclipse.jdt.ui/editor_folding_provider=org.eclipse.jdt.ui.text.defaultFoldingProvider
/bundle_defaults/org.eclipse.jdt.ui/enclosingBrackets=false
/bundle_defaults/org.eclipse.jdt.ui/escapeStrings=false
/bundle_defaults/org.eclipse.jdt.ui/formatter_profile=org.eclipse.jdt.ui.default.eclipse_profile
/bundle_defaults/org.eclipse.jdt.ui/handleTemporaryProblems=true
/bundle_defaults/org.eclipse.jdt.ui/highlightBracketAtCaretLocation=false
/bundle_defaults/org.eclipse.jdt.ui/hoverModifierMasks=org.eclipse.jdt.ui.BestMatchHover;0;org.eclipse.jdt.ui.JavaSourceHover;131072;org.eclipse.jdt.ui.NLSStringHover;4259840;org.eclipse.jdt.ui.JavadocHover;4325376
/bundle_defaults/org.eclipse.jdt.ui/hoverModifiers=org.eclipse.jdt.ui.BestMatchHover;0;org.eclipse.jdt.ui.JavaSourceHover;Shift;org.eclipse.jdt.ui.NLSStringHover;Command+Alt;org.eclipse.jdt.ui.JavadocHover;Command+Shift
/bundle_defaults/org.eclipse.jdt.ui/importsOnPaste=true
/bundle_defaults/org.eclipse.jdt.ui/java_annotation=100,100,100
/bundle_defaults/org.eclipse.jdt.ui/java_annotation_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_annotation_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_bracket=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/java_bracket_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_bracket_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_comment_task_tag=127,159,191
/bundle_defaults/org.eclipse.jdt.ui/java_comment_task_tag_bold=true
/bundle_defaults/org.eclipse.jdt.ui/java_comment_task_tag_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_default=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/java_default_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_default_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_doc_default=63,95,191
/bundle_defaults/org.eclipse.jdt.ui/java_doc_default_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_doc_default_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_doc_keyword=127,159,191
/bundle_defaults/org.eclipse.jdt.ui/java_doc_keyword_bold=true
/bundle_defaults/org.eclipse.jdt.ui/java_doc_keyword_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_doc_link=63,63,191
/bundle_defaults/org.eclipse.jdt.ui/java_doc_link_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_doc_link_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_doc_tag=127,127,159
/bundle_defaults/org.eclipse.jdt.ui/java_doc_tag_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_doc_tag_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_keyword=127,0,85
/bundle_defaults/org.eclipse.jdt.ui/java_keyword_bold=true
/bundle_defaults/org.eclipse.jdt.ui/java_keyword_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_keyword_return=127,0,85
/bundle_defaults/org.eclipse.jdt.ui/java_keyword_return_bold=true
/bundle_defaults/org.eclipse.jdt.ui/java_keyword_return_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_method_name=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/java_method_name_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_method_name_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_multi_line_comment=63,127,95
/bundle_defaults/org.eclipse.jdt.ui/java_multi_line_comment_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_multi_line_comment_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_operator=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/java_operator_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_operator_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_single_line_comment=63,127,95
/bundle_defaults/org.eclipse.jdt.ui/java_single_line_comment_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_single_line_comment_italic=false
/bundle_defaults/org.eclipse.jdt.ui/java_string=42,0,255
/bundle_defaults/org.eclipse.jdt.ui/java_string_bold=false
/bundle_defaults/org.eclipse.jdt.ui/java_string_italic=false
/bundle_defaults/org.eclipse.jdt.ui/linkedPositionColor=121,121,121
/bundle_defaults/org.eclipse.jdt.ui/markBreakContinueTargets=true
/bundle_defaults/org.eclipse.jdt.ui/markConstantOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/markExceptionOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/markFieldOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/markImplementors=true
/bundle_defaults/org.eclipse.jdt.ui/markLocalVariableOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/markMethodExitPoints=true
/bundle_defaults/org.eclipse.jdt.ui/markMethodOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/markOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/markTypeOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/matchingBrackets=true
/bundle_defaults/org.eclipse.jdt.ui/matchingBracketsColor=192,192,192
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.abbreviatepackagenames=false
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.browsing.memberstoeditor=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.browsing.packagestoeditor=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.browsing.projectstoeditor=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.browsing.stackVertically=false
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.browsing.typestoeditor=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.category=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.compresspackagenames=false
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.editor.showSegments=false
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.editor.tab.width=4
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.enable.visibility.order=false
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.exception.name=e
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.flatPackagesInPackageExplorer=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.gettersetter.use.is=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.ignorelowercasenames=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.importorder=java;javax;org;com
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.javadoc=false
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.keywordthis=false
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.methodreturntype=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.methodtypeparametesr=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.ondemandthreshold=99
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.openTypeHierarchy=viewPart
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.overrideannotation=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.packages.cuchildren=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.pkgNameAbbreviationPatternForPackagesView=
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.staticondemandthreshold=99
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.template.format=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.typefilter.disabled=
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.typefilter.enabled=
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.visibility.order=B,V,R,D
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.wizards.jre.index=0
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.wizards.jre.list=JRE+container 5 org.eclipse.jdt.launching.JRE_CONTAINER \# \# false ;JRE_LIB+variable+%28deprecated%29 4 JRE_LIB JRE_SRC JRE_SRCROOT false ;
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.wizards.srcBinFoldersBinName=bin
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.wizards.srcBinFoldersInNewProjects=true
/bundle_defaults/org.eclipse.jdt.ui/org.eclipse.jdt.ui.wizards.srcBinFoldersSrcName=src
/bundle_defaults/org.eclipse.jdt.ui/outlinesortoption=T,SF,SI,SM,F,I,C,M
/bundle_defaults/org.eclipse.jdt.ui/packageview.doubleclick=packageview.doubleclick.expands
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_argument=127,0,85
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_argument_bold=true
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_argument_italic=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_assignment=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_assignment_bold=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_assignment_italic=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_comment=63,127,95
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_comment_bold=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_comment_italic=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_key=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_key_bold=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_key_italic=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_value=42,0,255
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_value_bold=false
/bundle_defaults/org.eclipse.jdt.ui/pf_coloring_value_italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractClass.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractClass.color=139,136,22
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractClass.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractClass.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractClass.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractClass.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractMethodInvocation.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractMethodInvocation.color=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractMethodInvocation.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractMethodInvocation.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractMethodInvocation.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.abstractMethodInvocation.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotation.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotation.color=100,100,100
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotation.enabled=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotation.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotation.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotation.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotationElementReference.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotationElementReference.color=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotationElementReference.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotationElementReference.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotationElementReference.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.annotationElementReference.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.autoboxing.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.autoboxing.color=171,48,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.autoboxing.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.autoboxing.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.autoboxing.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.autoboxing.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.class.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.class.color=0,80,50
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.class.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.class.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.class.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.class.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.deprecatedMember.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.deprecatedMember.color=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.deprecatedMember.enabled=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.deprecatedMember.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.deprecatedMember.strikethrough=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.deprecatedMember.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.enum.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.enum.color=100,70,50
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.enum.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.enum.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.enum.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.enum.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.field.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.field.color=0,0,192
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.field.enabled=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.field.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.field.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.field.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedField.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedField.color=0,0,192
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedField.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedField.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedField.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedField.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedMethodInvocation.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedMethodInvocation.color=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedMethodInvocation.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedMethodInvocation.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedMethodInvocation.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.inheritedMethodInvocation.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.interface.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.interface.color=50,63,112
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.interface.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.interface.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.interface.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.interface.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariable.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariable.color=106,62,62
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariable.enabled=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariable.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariable.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariable.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariableDeclaration.bold=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariableDeclaration.color=106,62,62
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariableDeclaration.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariableDeclaration.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariableDeclaration.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.localVariableDeclaration.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.method.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.method.color=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.method.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.method.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.method.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.method.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.methodDeclarationName.bold=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.methodDeclarationName.color=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.methodDeclarationName.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.methodDeclarationName.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.methodDeclarationName.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.methodDeclarationName.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.number.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.number.color=42,0,255
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.number.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.number.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.number.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.number.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.parameterVariable.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.parameterVariable.color=106,62,62
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.parameterVariable.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.parameterVariable.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.parameterVariable.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.parameterVariable.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticField.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticField.color=0,0,192
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticField.enabled=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticField.italic=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticField.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticField.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticFinalField.bold=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticFinalField.color=0,0,192
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticFinalField.enabled=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticFinalField.italic=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticFinalField.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticFinalField.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticMethodInvocation.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticMethodInvocation.color=0,0,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticMethodInvocation.enabled=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticMethodInvocation.italic=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticMethodInvocation.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.staticMethodInvocation.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeArgument.bold=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeArgument.color=13,100,0
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeArgument.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeArgument.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeArgument.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeArgument.underline=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeParameter.bold=true
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeParameter.color=100,70,50
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeParameter.enabled=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeParameter.italic=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeParameter.strikethrough=false
/bundle_defaults/org.eclipse.jdt.ui/semanticHighlighting.typeParameter.underline=false
/bundle_defaults/org.eclipse.jdt.ui/smartIndentAfterNewline=true
/bundle_defaults/org.eclipse.jdt.ui/smartPaste=true
/bundle_defaults/org.eclipse.jdt.ui/smart_backspace=true
/bundle_defaults/org.eclipse.jdt.ui/smart_tab=true
/bundle_defaults/org.eclipse.jdt.ui/sourceHoverBackgroundColor.SystemDefault=true
/bundle_defaults/org.eclipse.jdt.ui/spacesForTabs=false
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_ampersand_in_properties=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_digits=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_java_strings=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_mixed=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_non_letters=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_sentence=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_single_letters=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_upper=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_ignore_urls=true
/bundle_defaults/org.eclipse.jdt.ui/spelling_locale=en_US
/bundle_defaults/org.eclipse.jdt.ui/spelling_problems_threshold=1000
/bundle_defaults/org.eclipse.jdt.ui/spelling_proposal_threshold=20
/bundle_defaults/org.eclipse.jdt.ui/spelling_user_dictionary=
/bundle_defaults/org.eclipse.jdt.ui/spelling_user_dictionary_encoding=UTF-8
/bundle_defaults/org.eclipse.jdt.ui/stickyOccurrences=true
/bundle_defaults/org.eclipse.jdt.ui/subWordNavigation=true
/bundle_defaults/org.eclipse.jdt.ui/wrapStrings=true
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.autoUpdateProjects=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.debugOutput=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.defaultRuntime=
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.downloadJavadoc=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.downloadSources=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.globalUpdatePolicy=true
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.hideFoldersOfNestedProjects=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.offline=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.outputFolder=target-eclipse
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.problem.duplicateParentGroupId=warning
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.problem.duplicateParentVersion=warning
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.problem.notCoveredMojoExecution=error
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.problem.outofdateProjectConfig=error
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.problem.overridingManagedVersion=warning
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.runtimes=
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.showConsoleOnErr=true
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.showConsoleOnOutput=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.updateIndexes=false
/bundle_defaults/org.eclipse.m2e.core/eclipse.m2.updateProjects=false
/bundle_defaults/org.eclipse.oomph.setup.ui/preferred.text.editor=org.eclipse.ui.DefaultTextEditor
/bundle_defaults/org.eclipse.pde.ds.annotations/enabled=false
/bundle_defaults/org.eclipse.pde.ds.annotations/path=OSGI-INF
/bundle_defaults/org.eclipse.pde.ds.annotations/validationErrorLevel=error
/bundle_defaults/org.eclipse.pde.ds.annotations/validationErrorLevel.missingImplicitUnbindMethod=error
/bundle_defaults/org.eclipse.pde.ui/Preferences.MainPage.showObjects=useIds
/bundle_defaults/org.eclipse.pde.ui/Preferences.MainPage.showTargetStatus=false
/bundle_defaults/org.eclipse.pde.ui/editor.color.default=0,0,0
/bundle_defaults/org.eclipse.pde.ui/editor.color.externalized_string=128,0,128
/bundle_defaults/org.eclipse.pde.ui/editor.color.header_assignment=0,0,0
/bundle_defaults/org.eclipse.pde.ui/editor.color.header_attributes=128,128,0
/bundle_defaults/org.eclipse.pde.ui/editor.color.header_attributes_italic=true
/bundle_defaults/org.eclipse.pde.ui/editor.color.header_key=128,0,0
/bundle_defaults/org.eclipse.pde.ui/editor.color.header_osgi=128,0,0
/bundle_defaults/org.eclipse.pde.ui/editor.color.header_osgi_bold=true
/bundle_defaults/org.eclipse.pde.ui/editor.color.header_value=0,0,0
/bundle_defaults/org.eclipse.pde.ui/editor.color.instr=128,128,128
/bundle_defaults/org.eclipse.pde.ui/editor.color.string=0,128,0
/bundle_defaults/org.eclipse.pde.ui/editor.color.tag=0,0,128
/bundle_defaults/org.eclipse.pde.ui/editor.color.xml_comment=128,0,0
/bundle_defaults/org.eclipse.pde.ui/editor.folding=false
/bundle_defaults/org.eclipse.rse.core/CREATE_LOCAL_CONNECTION=true
/bundle_defaults/org.eclipse.rse.core/DEFAULT_PERSISTENCE_PROVIDER=org.eclipse.rse.persistence.MetadataPropertyFileProvider
/bundle_defaults/org.eclipse.rse.core/activeuserprofiles=Team;R5081566
/bundle_defaults/org.eclipse.rse.core/logging_level=0
/bundle_defaults/org.eclipse.rse.core/useDeferredQueries=true
/bundle_defaults/org.eclipse.rse.ui/APPEND_MNEMONICS_PATTERN=zh.*|ja.*|ko.*
/bundle_defaults/org.eclipse.rse.ui/MNEMONICS_POLICY=3
/bundle_defaults/org.eclipse.rse.ui/SHOW_EMPTY_LISTS=true
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.filterpools.show=false
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.history.folder=
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.order.connections=
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.qualifyconnectionnames=false
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.rememberState=true
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.restoreStateFromCache=true
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.shownewconnection=false
/bundle_defaults/org.eclipse.rse.ui/org.eclipse.rse.preferences.uda.cascade=false
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.apply_patch_in_sychronize_view=false
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.compress_folders=true
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.default_layout=org.eclipse.team.ui.compressed_layout
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.first_time=true
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.remove_from_view_without_prompt=false
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.reuse_open_compare_editors=true
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.run_import_in_background_=false
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.show_author_in_compare_editor=false
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.sychronizing_default_participant=none
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.sychronizing_default_participant_sec_id=none
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.sychronizing_default_perspective_to_show=prompt
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.syncview_default_perspective=org.eclipse.team.ui.TeamSynchronizingPerspective
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.validate_edit_with_no_context=false
/bundle_defaults/org.eclipse.team.ui/org.eclipse.team.ui.view_syncinfo_in_label=false
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Accessibility.UseCustomCarets=true
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Accessibility.WideCaret=true
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Color.Background=255,255,255
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Color.Background.SystemDefault=true
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Color.FindScope=185,176,180
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Color.Foreground=0,0,0
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Color.Foreground.SystemDefault=true
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Color.SelectionBackground.SystemDefault=true
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Color.SelectionForeground.SystemDefault=true
/bundle_defaults/org.eclipse.ui.editors/AbstractTextEditor.Navigation.SmartHomeEnd=true
/bundle_defaults/org.eclipse.ui.editors/Accessibility.UseSaturatedColors=false
/bundle_defaults/org.eclipse.ui.editors/additionIndication=false
/bundle_defaults/org.eclipse.ui.editors/additionIndicationColor=188,188,222
/bundle_defaults/org.eclipse.ui.editors/additionIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/additionIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/adviceIndication=true
/bundle_defaults/org.eclipse.ui.editors/adviceIndicationColor=222,109,33
/bundle_defaults/org.eclipse.ui.editors/adviceIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/adviceIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/bookmarkIndication=false
/bundle_defaults/org.eclipse.ui.editors/bookmarkIndicationColor=34,164,99
/bundle_defaults/org.eclipse.ui.editors/bookmarkIndicationHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/bookmarkIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/bookmarkIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/bookmarkTextStyle=SQUIGGLES
/bundle_defaults/org.eclipse.ui.editors/breakpointHighlight=false
/bundle_defaults/org.eclipse.ui.editors/breakpointIndication=false
/bundle_defaults/org.eclipse.ui.editors/breakpointIndicationColor=0,0,255
/bundle_defaults/org.eclipse.ui.editors/breakpointIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/breakpointTextStyle=SQUIGGLES
/bundle_defaults/org.eclipse.ui.editors/breakpointVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/changeIndication=false
/bundle_defaults/org.eclipse.ui.editors/changeIndicationColor=204,163,205
/bundle_defaults/org.eclipse.ui.editors/changeIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/changeIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/currentIPColor=198,219,174
/bundle_defaults/org.eclipse.ui.editors/currentIPHighlight=true
/bundle_defaults/org.eclipse.ui.editors/currentIPIndication=false
/bundle_defaults/org.eclipse.ui.editors/currentIPOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/currentIPTextStyle=NONE
/bundle_defaults/org.eclipse.ui.editors/currentIPVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/currentLine=true
/bundle_defaults/org.eclipse.ui.editors/currentLineColor=232,242,254
/bundle_defaults/org.eclipse.ui.editors/deletionIndication=false
/bundle_defaults/org.eclipse.ui.editors/deletionIndicationColor=0,0,0
/bundle_defaults/org.eclipse.ui.editors/deletionIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/deletionIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/errorIndication=true
/bundle_defaults/org.eclipse.ui.editors/errorIndicationColor=255,0,128
/bundle_defaults/org.eclipse.ui.editors/errorIndicationHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/errorIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/errorIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/errorTextStyle=PROBLEM_UNDERLINE
/bundle_defaults/org.eclipse.ui.editors/filteredSearchResultHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/filteredSearchResultIndication=false
/bundle_defaults/org.eclipse.ui.editors/filteredSearchResultIndicationColor=237,237,252
/bundle_defaults/org.eclipse.ui.editors/filteredSearchResultIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/filteredSearchResultIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/filteredSearchResultTextStyle=SQUIGGLES
/bundle_defaults/org.eclipse.ui.editors/hoverReplaceMode=0
/bundle_defaults/org.eclipse.ui.editors/hyperlinkColor=0,0,255
/bundle_defaults/org.eclipse.ui.editors/hyperlinkColor.SystemDefault=true
/bundle_defaults/org.eclipse.ui.editors/hyperlinkKeyModifier=Command
/bundle_defaults/org.eclipse.ui.editors/hyperlinkKeyModifierMask=4194304
/bundle_defaults/org.eclipse.ui.editors/hyperlinksEnabled=true
/bundle_defaults/org.eclipse.ui.editors/infoIndication=true
/bundle_defaults/org.eclipse.ui.editors/infoIndicationColor=0,128,255
/bundle_defaults/org.eclipse.ui.editors/infoIndicationHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/infoIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/infoIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/infoTextStyle=SQUIGGLES
/bundle_defaults/org.eclipse.ui.editors/isAdditionGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isAdditionGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isBookmarkGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isBookmarkGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isBreakpointIndicationGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isBreakpointIndicationGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isChangeGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isChangeGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isDeletionGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isDeletionGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isErrorGoToNextNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/isErrorGoToPreviousNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/isFilteredSearchResultGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isFilteredSearchResultGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isInfoGoToNextNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/isInfoGoToPreviousNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/isOccurrenceGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isOccurrenceGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isOverrideIndicatorGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isOverrideIndicatorGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isRevisionAnnotationGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isRevisionAnnotationGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isSearchResultGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isSearchResultGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isSpellingGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isSpellingGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isTaskGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isTaskGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isUnchangedGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isUnchangedGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/isWarningGoToNextNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/isWarningGoToPreviousNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/javaScriptIsOccurrenceGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptIsOccurrenceGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptIsOverrideIndicatorGoToNextNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptIsOverrideIndicatorGoToPreviousNavigationTarget=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptOccurrenceHighlighting=true
/bundle_defaults/org.eclipse.ui.editors/javaScriptOccurrenceIndication=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptOccurrenceIndicationColor=212,212,212
/bundle_defaults/org.eclipse.ui.editors/javaScriptOccurrenceIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/javaScriptOccurrenceIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptOverrideIndicator=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptOverrideIndicatorColor=180,207,205
/bundle_defaults/org.eclipse.ui.editors/javaScriptOverrideIndicatorHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptOverrideIndicatorInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/javaScriptOverrideIndicatorInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/javaScriptShowOccurrenceInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/javaScriptShowoverrideIndicatorInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.color=0,180,0
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.highlight=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.text=true
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.text.style=IBEAM
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.exit.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.color=70,100,165
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.highlight=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.text=true
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.text.style=BOX
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.focus.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.color=180,215,255
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.highlight=true
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.text=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.text.style=NONE
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.slave.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.color=70,100,165
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.highlight=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.text=true
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.text.style=BOX
/bundle_defaults/org.eclipse.ui.editors/jdt.linked.target.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/lineNumberColor=120,120,120
/bundle_defaults/org.eclipse.ui.editors/lineNumberRuler=false
/bundle_defaults/org.eclipse.ui.editors/linked.exit.color=0,180,0
/bundle_defaults/org.eclipse.ui.editors/linked.exit.highlight=false
/bundle_defaults/org.eclipse.ui.editors/linked.exit.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/linked.exit.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/linked.exit.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/linked.exit.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/linked.exit.text=true
/bundle_defaults/org.eclipse.ui.editors/linked.exit.text.style=IBEAM
/bundle_defaults/org.eclipse.ui.editors/linked.exit.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/linked.focus.color=70,100,165
/bundle_defaults/org.eclipse.ui.editors/linked.focus.highlight=false
/bundle_defaults/org.eclipse.ui.editors/linked.focus.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/linked.focus.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/linked.focus.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/linked.focus.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/linked.focus.text=true
/bundle_defaults/org.eclipse.ui.editors/linked.focus.text.style=BOX
/bundle_defaults/org.eclipse.ui.editors/linked.focus.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/linked.slave.color=180,215,255
/bundle_defaults/org.eclipse.ui.editors/linked.slave.highlight=true
/bundle_defaults/org.eclipse.ui.editors/linked.slave.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/linked.slave.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/linked.slave.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/linked.slave.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/linked.slave.text=false
/bundle_defaults/org.eclipse.ui.editors/linked.slave.text.style=NONE
/bundle_defaults/org.eclipse.ui.editors/linked.slave.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/linked.target.color=70,100,165
/bundle_defaults/org.eclipse.ui.editors/linked.target.highlight=false
/bundle_defaults/org.eclipse.ui.editors/linked.target.navigation.dropdown=false
/bundle_defaults/org.eclipse.ui.editors/linked.target.navigation.next=false
/bundle_defaults/org.eclipse.ui.editors/linked.target.navigation.previous=false
/bundle_defaults/org.eclipse.ui.editors/linked.target.overviewruler=false
/bundle_defaults/org.eclipse.ui.editors/linked.target.text=true
/bundle_defaults/org.eclipse.ui.editors/linked.target.text.style=BOX
/bundle_defaults/org.eclipse.ui.editors/linked.target.verticalruler=false
/bundle_defaults/org.eclipse.ui.editors/manifestHighlighting=true
/bundle_defaults/org.eclipse.ui.editors/matchingTagHighlight=true
/bundle_defaults/org.eclipse.ui.editors/matchingTagIndication=false
/bundle_defaults/org.eclipse.ui.editors/matchingTagIndicationColor=212,212,212
/bundle_defaults/org.eclipse.ui.editors/matchingTagIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/matchingTagTextStyle=NONE
/bundle_defaults/org.eclipse.ui.editors/matchingTagVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/occurrenceHighlighting=true
/bundle_defaults/org.eclipse.ui.editors/occurrenceIndication=false
/bundle_defaults/org.eclipse.ui.editors/occurrenceIndicationColor=212,212,212
/bundle_defaults/org.eclipse.ui.editors/occurrenceIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/occurrenceIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/occurrenceTextStyle=NONE
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.ant.ui.AntElementHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.mylyn.ui.commitHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedColor=221,255,221
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedGoToNextNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedGoToPreviousNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffAddedIndication=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedColor=255,221,221
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedGoToNextNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedGoToPreviousNavigationTarget=true
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.egit.ui.commitEditor.diffRemovedIndication=false
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.debug.ui.hyperlinkdetector.stepIntoSelection_stateMask=4259840
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.internal.ui.javaeditor.JavaElementHyperlinkDeclaredTypeDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.internal.ui.javaeditor.JavaElementHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.internal.ui.javaeditor.JavaElementHyperlinkImplementationDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.internal.ui.javaeditor.JavaElementHyperlinkReturnTypeDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.internal.ui.javaeditor.JavaElementHyperlinkSuperImplementationDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.internal.ui.javaeditor.NLSKeyHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jdt.internal.ui.propertiesfileeditor.PropertyKeyHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jpt.jpa.ui.jpql.generic_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jst.jsf.ui.elhyperlinkdetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jst.jsp.ui.internal.hyperlink.JSPJavaHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jst.jsp.ui.internal.hyperlink.TaglibHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.jst.jsp.ui.internal.hyperlink.XMLJavaHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.mylyn.java.hyperlink.detector.stack_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.mylyn.tasks.ui.hyperlinks.detectors.task.multiple_stateMask=262144
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.mylyn.tasks.ui.hyperlinks.detectors.task_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.mylyn.tasks.ui.hyperlinks.detectors.url_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.ui.internal.editors.text.URLHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.css.ui.internal.hyperlink.CSSHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.html.ui.internal.hyperlink.AnchorHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.jsdt.debug.ui.hyperlink.detector_stateMask=4259840
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.jsdt.internal.ui.javaeditor.JavaElementHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.jsdt.web.ui.JSDTHyperlinkDetector.HTML_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.jsdt.web.ui.JSDTHyperlinkDetector.SCRIPT.events_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.jsdt.web.ui.JSDTHyperlinkDetector.SCRIPT_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.json.ui.internal.hyperlink.JSONHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.wsdl.ui.internal.text.WSDLHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.xml.ui.internal.hyperlink.XMLHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.eclipse.wst.xsd.ui.internal.editor.XSDHyperlinkDetector_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/org.springframework.ide.eclipse.quickfix.AutowireHyperlink_stateMask=-1
/bundle_defaults/org.eclipse.ui.editors/othersIndication=false
/bundle_defaults/org.eclipse.ui.editors/othersIndicationColor=0,0,0
/bundle_defaults/org.eclipse.ui.editors/othersIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/overrideIndicator=false
/bundle_defaults/org.eclipse.ui.editors/overrideIndicatorColor=180,207,205
/bundle_defaults/org.eclipse.ui.editors/overrideIndicatorHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/overrideIndicatorInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/overrideIndicatorInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/overrideIndicatorTextStyle=SQUIGGLES
/bundle_defaults/org.eclipse.ui.editors/overviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/printMargin=false
/bundle_defaults/org.eclipse.ui.editors/printMarginColor=176,180,185
/bundle_defaults/org.eclipse.ui.editors/printMarginColumn=80
/bundle_defaults/org.eclipse.ui.editors/problemIndication=true
/bundle_defaults/org.eclipse.ui.editors/problemIndicationColor=0,112,60
/bundle_defaults/org.eclipse.ui.editors/problemIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/problemIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/quickdiff.characterMode=false
/bundle_defaults/org.eclipse.ui.editors/quickdiff.defaultProvider=org.eclipse.ui.internal.editors.quickdiff.LastSaveReferenceProvider
/bundle_defaults/org.eclipse.ui.editors/quickdiff.nowarn.before.switch=
/bundle_defaults/org.eclipse.ui.editors/quickdiff.quickDiff=true
/bundle_defaults/org.eclipse.ui.editors/revisionAnnotationIndication=false
/bundle_defaults/org.eclipse.ui.editors/revisionAnnotationIndicationColor=88,88,22
/bundle_defaults/org.eclipse.ui.editors/revisionAnnotationIndicationHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/revisionAnnotationIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/revisionAnnotationIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/revisionRulerRenderingMode=Age
/bundle_defaults/org.eclipse.ui.editors/revisionRulerShowAuthor=false
/bundle_defaults/org.eclipse.ui.editors/revisionRulerShowRevision=false
/bundle_defaults/org.eclipse.ui.editors/rulerContributions=
/bundle_defaults/org.eclipse.ui.editors/searchResultHighlighting=true
/bundle_defaults/org.eclipse.ui.editors/searchResultIndication=false
/bundle_defaults/org.eclipse.ui.editors/searchResultIndicationColor=206,204,247
/bundle_defaults/org.eclipse.ui.editors/searchResultIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/searchResultIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/searchResultTextStyle=NONE
/bundle_defaults/org.eclipse.ui.editors/secondaryIPColor=219,235,204
/bundle_defaults/org.eclipse.ui.editors/secondaryIPHighlight=true
/bundle_defaults/org.eclipse.ui.editors/secondaryIPIndication=false
/bundle_defaults/org.eclipse.ui.editors/secondaryIPOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/secondaryIPTextStyle=NONE
/bundle_defaults/org.eclipse.ui.editors/secondaryIPVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/showAdditionInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showBookmarkInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showBreakpointIndicationInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showCarriageReturn=true
/bundle_defaults/org.eclipse.ui.editors/showChangeInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showDeletionInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/showEnclosedIdeographicSpaces=true
/bundle_defaults/org.eclipse.ui.editors/showEnclosedSpaces=true
/bundle_defaults/org.eclipse.ui.editors/showEnclosedTabs=true
/bundle_defaults/org.eclipse.ui.editors/showErrorInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showFilteredSearchResultInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/showInfoInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showLeadingIdeographicSpaces=true
/bundle_defaults/org.eclipse.ui.editors/showLeadingSpaces=true
/bundle_defaults/org.eclipse.ui.editors/showLeadingTabs=true
/bundle_defaults/org.eclipse.ui.editors/showLineFeed=true
/bundle_defaults/org.eclipse.ui.editors/showOccurrenceInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showRevisionAnnotationInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/showSearchResultInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showSpellingInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showTaskInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showTextHoverAffordance=true
/bundle_defaults/org.eclipse.ui.editors/showTrailingIdeographicSpaces=true
/bundle_defaults/org.eclipse.ui.editors/showTrailingSpaces=true
/bundle_defaults/org.eclipse.ui.editors/showTrailingTabs=true
/bundle_defaults/org.eclipse.ui.editors/showUnchangedInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/showWarningInNextPrevDropdownToolbarAction=true
/bundle_defaults/org.eclipse.ui.editors/showWhitespaceCharacters=false
/bundle_defaults/org.eclipse.ui.editors/show_range_indicator=true
/bundle_defaults/org.eclipse.ui.editors/showoverrideIndicatorInNextPrevDropdownToolbarAction=false
/bundle_defaults/org.eclipse.ui.editors/spacesForTabs=false
/bundle_defaults/org.eclipse.ui.editors/spellingEnabled=true
/bundle_defaults/org.eclipse.ui.editors/spellingEngine=
/bundle_defaults/org.eclipse.ui.editors/spellingIndication=true
/bundle_defaults/org.eclipse.ui.editors/spellingIndicationColor=255,128,64
/bundle_defaults/org.eclipse.ui.editors/spellingIndicationHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/spellingIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/spellingIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/spellingTextStyle=PROBLEM_UNDERLINE
/bundle_defaults/org.eclipse.ui.editors/tabWidth=4
/bundle_defaults/org.eclipse.ui.editors/taskIndication=false
/bundle_defaults/org.eclipse.ui.editors/taskIndicationColor=0,128,255
/bundle_defaults/org.eclipse.ui.editors/taskIndicationHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/taskIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/taskIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/taskTextStyle=SQUIGGLES
/bundle_defaults/org.eclipse.ui.editors/textDragAndDropEnabled=true
/bundle_defaults/org.eclipse.ui.editors/unchangedIndication=false
/bundle_defaults/org.eclipse.ui.editors/unchangedIndicationColor=0,0,0
/bundle_defaults/org.eclipse.ui.editors/unchangedIndicationInOverviewRuler=false
/bundle_defaults/org.eclipse.ui.editors/unchangedIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/undoHistorySize=200
/bundle_defaults/org.eclipse.ui.editors/useAnnotationsPrefPage=false
/bundle_defaults/org.eclipse.ui.editors/useQuickDiffPrefPage=false
/bundle_defaults/org.eclipse.ui.editors/warn_if_input_derived=true
/bundle_defaults/org.eclipse.ui.editors/warningIndication=true
/bundle_defaults/org.eclipse.ui.editors/warningIndicationColor=244,200,45
/bundle_defaults/org.eclipse.ui.editors/warningIndicationHighlighting=false
/bundle_defaults/org.eclipse.ui.editors/warningIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/warningIndicationInVerticalRuler=true
/bundle_defaults/org.eclipse.ui.editors/warningTextStyle=PROBLEM_UNDERLINE
/bundle_defaults/org.eclipse.ui.editors/whitespaceCharacterAlphaValue=80
/bundle_defaults/org.eclipse.ui.editors/wordwrap.enabled=false
/bundle_defaults/org.eclipse.ui.editors/writeOccurrenceHighlighting=true
/bundle_defaults/org.eclipse.ui.editors/writeOccurrenceIndication=false
/bundle_defaults/org.eclipse.ui.editors/writeOccurrenceIndicationColor=240,216,168
/bundle_defaults/org.eclipse.ui.editors/writeOccurrenceIndicationInOverviewRuler=true
/bundle_defaults/org.eclipse.ui.editors/writeOccurrenceIndicationInVerticalRuler=false
/bundle_defaults/org.eclipse.ui.editors/writeOccurrenceTextStyle=NONE
/bundle_defaults/org.eclipse.ui.ide/BOOKMARKS_FILTERS_MIGRATE=false
/bundle_defaults/org.eclipse.ui.ide/BOOKMARKS_LIMIT=100
/bundle_defaults/org.eclipse.ui.ide/CLOSE_UNRELATED_PROJECTS=false
/bundle_defaults/org.eclipse.ui.ide/EXIT_PROMPT_ON_CLOSE_LAST_WINDOW=true
/bundle_defaults/org.eclipse.ui.ide/IMPORT_FILES_AND_FOLDERS_MODE=prompt
/bundle_defaults/org.eclipse.ui.ide/IMPORT_FILES_AND_FOLDERS_RELATIVE=true
/bundle_defaults/org.eclipse.ui.ide/IMPORT_FILES_AND_FOLDERS_TYPE=
/bundle_defaults/org.eclipse.ui.ide/IMPORT_FILES_AND_FOLDERS_VIRTUAL_FOLDER_MODE=prompt
/bundle_defaults/org.eclipse.ui.ide/LIMIT_BOOKMARKS=true
/bundle_defaults/org.eclipse.ui.ide/LIMIT_PROBLEMS=true
/bundle_defaults/org.eclipse.ui.ide/LIMIT_TASKS=true
/bundle_defaults/org.eclipse.ui.ide/MARKER_LIMITS_VALUE=100
/bundle_defaults/org.eclipse.ui.ide/OPEN_REQUIRED_PROJECTS=prompt
/bundle_defaults/org.eclipse.ui.ide/PROBLEMS_FILTERS_MIGRATE=false
/bundle_defaults/org.eclipse.ui.ide/PROBLEMS_LIMIT=100
/bundle_defaults/org.eclipse.ui.ide/PROJECT_OPEN_NEW_PERSPECTIVE=OPEN_PERSPECTIVE_REPLACE
/bundle_defaults/org.eclipse.ui.ide/REFRESH_WORKSPACE_ON_STARTUP=false
/bundle_defaults/org.eclipse.ui.ide/SAVE_ALL_BEFORE_BUILD=false
/bundle_defaults/org.eclipse.ui.ide/SHOW_WORKSPACE_SELECTION_DIALOG=true
/bundle_defaults/org.eclipse.ui.ide/SWITCH_PERSPECTIVE_ON_PROJECT_CREATION=prompt
/bundle_defaults/org.eclipse.ui.ide/SYSTEM_EXPLORER=open -R "${selected_resource_loc}"
/bundle_defaults/org.eclipse.ui.ide/TASKS_FILTERS_MIGRATE=false
/bundle_defaults/org.eclipse.ui.ide/TASKS_LIMIT=100
/bundle_defaults/org.eclipse.ui.ide/USE_MARKER_LIMITS=true
/bundle_defaults/org.eclipse.ui.ide/WARN_ABOUT_WORKSPACE_INCOMPATIBILITY=true
/bundle_defaults/org.eclipse.ui.ide/WELCOME_DIALOG=true
/bundle_defaults/org.eclipse.ui.ide/saveInterval=5
/bundle_defaults/org.eclipse.ui.ide/unassociatedEditorStrategy=org.eclipse.ui.ide.systemEditorThenTextEditor
/bundle_defaults/org.eclipse.ui.ide/useSeparator.help.group.assist=true
/bundle_defaults/org.eclipse.ui.ide/useSeparator.help.group.main=true
/bundle_defaults/org.eclipse.ui.ide/useSeparator.help.group.updates=true
/bundle_defaults/org.eclipse.ui.monitoring/deadlock_reporting_threshold=300000
/bundle_defaults/org.eclipse.ui.monitoring/log_to_error_log=true
/bundle_defaults/org.eclipse.ui.monitoring/long_event_error_threshold=2000
/bundle_defaults/org.eclipse.ui.monitoring/long_event_warning_threshold=500
/bundle_defaults/org.eclipse.ui.monitoring/max_stack_samples=3
/bundle_defaults/org.eclipse.ui.monitoring/monitoring_enabled=false
/bundle_defaults/org.eclipse.ui.monitoring/noninteresting_thread_filter=java.*,sun.*,org.eclipse.core.internal.jobs.WorkerPool.sleep,org.eclipse.core.internal.jobs.WorkerPool.startJob,org.eclipse.core.internal.jobs.Worker.run,org.eclipse.osgi.framework.eventmgr.EventManager$EventThread.getNextEvent,org.eclipse.osgi.framework.eventmgr.EventManager$EventThread.run,org.eclipse.equinox.internal.util.impl.tpt.timer.TimerImpl.run,org.eclipse.equinox.internal.util.impl.tpt.threadpool.Executor.run
/bundle_defaults/org.eclipse.ui.monitoring/ui_thread_filter=
/bundle_defaults/org.eclipse.ui.workbench/BIDI_SUPPORT=false
/bundle_defaults/org.eclipse.ui.workbench/COLOR_ICONS=true
/bundle_defaults/org.eclipse.ui.workbench/DISABLE_DIALOG_FONT=false
/bundle_defaults/org.eclipse.ui.workbench/DISABLE_OPEN_EDITOR_IN_PLACE=false
/bundle_defaults/org.eclipse.ui.workbench/EDITORLIST_DISPLAY_FULL_NAME=false
/bundle_defaults/org.eclipse.ui.workbench/EDITORLIST_PULLDOWN_ACTIVE=false
/bundle_defaults/org.eclipse.ui.workbench/EDITORLIST_SELECTION_SCOPE=1
/bundle_defaults/org.eclipse.ui.workbench/EDITORLIST_SORT_CRITERIA=0
/bundle_defaults/org.eclipse.ui.workbench/EDITOR_TAB_WIDTH=3
/bundle_defaults/org.eclipse.ui.workbench/ENABLED_DECORATORS=
/bundle_defaults/org.eclipse.ui.workbench/ENABLE_CONFIGURABLE_PROJECT_WIZARD=false
/bundle_defaults/org.eclipse.ui.workbench/ENABLE_COOL_BARS=true
/bundle_defaults/org.eclipse.ui.workbench/ENABLE_NEW_MENUS=true
/bundle_defaults/org.eclipse.ui.workbench/HeapStatus.showMax=false
/bundle_defaults/org.eclipse.ui.workbench/HeapStatus.updateInterval=500
/bundle_defaults/org.eclipse.ui.workbench/KEYS_PREFERENCE_SELECTED_TAB=0
/bundle_defaults/org.eclipse.ui.workbench/LAYOUT_DIRECTION=0
/bundle_defaults/org.eclipse.ui.workbench/MULTI_KEY_ASSIST=true
/bundle_defaults/org.eclipse.ui.workbench/MULTI_KEY_ASSIST_TIME=1000
/bundle_defaults/org.eclipse.ui.workbench/NL_EXTENSIONS=
/bundle_defaults/org.eclipse.ui.workbench/OPEN_AFTER_DELAY=false
/bundle_defaults/org.eclipse.ui.workbench/OPEN_ON_SINGLE_CLICK=false
/bundle_defaults/org.eclipse.ui.workbench/OPEN_PERSPECTIVE_MODE=0
/bundle_defaults/org.eclipse.ui.workbench/RECENT_FILES=4
/bundle_defaults/org.eclipse.ui.workbench/REUSE_DIRTY_EDITORS=true
/bundle_defaults/org.eclipse.ui.workbench/REUSE_OPEN_EDITORS=8
/bundle_defaults/org.eclipse.ui.workbench/REUSE_OPEN_EDITORS_BOOLEAN=false
/bundle_defaults/org.eclipse.ui.workbench/SAVE_AUTOMATICALLY=false
/bundle_defaults/org.eclipse.ui.workbench/SAVE_AUTOMATICALLY_INTERVAL=20
/bundle_defaults/org.eclipse.ui.workbench/SELECT_ON_HOVER=false
/bundle_defaults/org.eclipse.ui.workbench/SHOW_MEMORY_MONITOR=false
/bundle_defaults/org.eclipse.ui.workbench/SINGLE_CLICK_METHOD=0
/bundle_defaults/org.eclipse.ui.workbench/STICKY_CYCLE=false
/bundle_defaults/org.eclipse.ui.workbench/TEXT_DIRECTION=
/bundle_defaults/org.eclipse.ui.workbench/USE_IPERSISTABLE_EDITORS=true
/bundle_defaults/org.eclipse.ui.workbench/WORKBENCH_SAVE_INTERVAL=5
/bundle_defaults/org.eclipse.ui.workbench/coolBarVisible=true
/bundle_defaults/org.eclipse.ui.workbench/overridepresentation=false
/bundle_defaults/org.eclipse.ui.workbench/perspectiveBarVisible=true
/bundle_defaults/org.eclipse.ui.workbench/shouldPromptForEnablement=true
/bundle_defaults/org.eclipse.ui/ALTERNATE_OPEN_NEW_PERSPECTIVE=OPEN_PERSPECTIVE_REPLACE
/bundle_defaults/org.eclipse.ui/CLOSE_EDITORS_ON_EXIT=false
/bundle_defaults/org.eclipse.ui/DOCK_PERSPECTIVE_BAR=topLeft
/bundle_defaults/org.eclipse.ui/EDITOR_MINIMUM_CHARACTERS=-1
/bundle_defaults/org.eclipse.ui/EDITOR_TAB_POSITION=128
/bundle_defaults/org.eclipse.ui/ENABLE_32_STICKY_CLOSE_BEHAVIOR=false
/bundle_defaults/org.eclipse.ui/ENABLE_ANIMATIONS=false
/bundle_defaults/org.eclipse.ui/ENABLE_DETACHED_VIEWS=true
/bundle_defaults/org.eclipse.ui/ENABLE_MIN_MAX=true
/bundle_defaults/org.eclipse.ui/KEY_CONFIGURATION_ID=org.eclipse.ui.defaultAcceleratorConfiguration
/bundle_defaults/org.eclipse.ui/LINK_NAVIGATOR_TO_EDITOR=false
/bundle_defaults/org.eclipse.ui/OPEN_NEW_PERSPECTIVE=OPEN_PERSPECTIVE_REPLACE
/bundle_defaults/org.eclipse.ui/PROJECT_OPEN_NEW_PERSPECTIVE=OPEN_PERSPECTIVE_REPLACE
/bundle_defaults/org.eclipse.ui/PROMPT_WHEN_SAVEABLE_STILL_OPEN=true
/bundle_defaults/org.eclipse.ui/RECENTLY_USED_WORKINGSETS_SIZE=5
/bundle_defaults/org.eclipse.ui/SHIFT_OPEN_NEW_PERSPECTIVE=OPEN_PERSPECTIVE_REPLACE
/bundle_defaults/org.eclipse.ui/SHOW_FILTERED_TEXTS=true
/bundle_defaults/org.eclipse.ui/SHOW_MULTIPLE_EDITOR_TABS=true
/bundle_defaults/org.eclipse.ui/SHOW_OPEN_ON_PERSPECTIVE_BAR=true
/bundle_defaults/org.eclipse.ui/SHOW_OTHER_IN_PERSPECTIVE_MENU=true
/bundle_defaults/org.eclipse.ui/SHOW_SYSTEM_JOBS=false
/bundle_defaults/org.eclipse.ui/SHOW_TEXT_ON_PERSPECTIVE_BAR=false
/bundle_defaults/org.eclipse.ui/SHOW_TRADITIONAL_STYLE_TABS=true
/bundle_defaults/org.eclipse.ui/USE_COLORED_LABELS=true
/bundle_defaults/org.eclipse.ui/USE_WINDOW_WORKING_SET_BY_DEFAULT=false
/bundle_defaults/org.eclipse.ui/VIEW_MINIMUM_CHARACTERS=1
/bundle_defaults/org.eclipse.ui/VIEW_TAB_POSITION=128
/bundle_defaults/org.eclipse.ui/disableNewFastView=false
/bundle_defaults/org.eclipse.ui/initialFastViewBarLocation=bottom
/bundle_defaults/org.eclipse.ui/showIntro=true
/bundle_defaults/org.eclipse.wst.sse.core/task-tags/enabled=false
/bundle_defaults/org.eclipse.wst.sse.core/task-tags/ignored-contentTypes=
/bundle_defaults/org.eclipse.wst.sse.core/task-tags/taskPriorities=1,2,1
/bundle_defaults/org.eclipse.wst.sse.core/task-tags/taskTags=TODO,FIXME,XXX
/bundle_defaults/org.eclipse.wst.web/org.eclipse.jst.j2ee.preference.staticWebContentName=WebContent
/bundle_defaults/org.springsource.ide.eclipse.commons.configurator/org.springsource.ide.eclipse.commons.configurator.installPath=/Users/m134910/eclipse/jee-neon
/configuration/org.eclipse.core.net/org.eclipse.core.net.hasMigrated=true
/configuration/org.eclipse.equinox.p2.garbagecollector/gc_enabled=false
/configuration/org.eclipse.ui.ide/MAX_RECENT_WORKSPACES=10
/configuration/org.eclipse.ui.ide/RECENT_WORKSPACES=/Users/m134910/Documents/workspace/nlp
/configuration/org.eclipse.ui.ide/RECENT_WORKSPACES_PROTOCOL=3
/configuration/org.eclipse.ui.ide/SHOW_RECENT_WORKSPACES=false
/configuration/org.eclipse.ui.ide/SHOW_WORKSPACE_SELECTION_DIALOG=true
/instance/org.eclipse.core.net/org.eclipse.core.net.hasMigrated=true
/instance/org.eclipse.core.resources/version=1
/instance/org.eclipse.debug.ui/org.eclipse.debug.ui.PREF_LAUNCH_PERSPECTIVES=<?xml version\="1.0" encoding\="UTF-8" standalone\="no"?>\n<launchPerspectives/>\n
/instance/org.eclipse.debug.ui/preferredTargets=default\:default|
/instance/org.eclipse.dltk.launching/org.eclipse.dltk.launching.PREF_INTERPRETER_XML=<?xml version\="1.0" encoding\="UTF-8" standalone\="no"?>\n<interpreterSettings>\n<defaultInterpreter environment\="org.eclipse.dltk.core.environment.localEnvironment" id\="65,org.apache.uima.ruta.ide.debug.ui.launcher.GenericRutaInstallType47,org.apache.uima.ruta.ide.launching.embeddedRuta" nature\="org.apache.uima.ruta.ide.nature"/>\n<interpreterType id\="org.apache.uima.ruta.ide.debug.ui.launcher.GenericRutaInstallType">\n<interpreter environmentId\="org.eclipse.dltk.core.environment.localEnvironment" id\="org.apache.uima.ruta.ide.launching.embeddedRuta" name\="UIMA Ruta Interpreter" path\="/Users/m134910/eclipse/java-neon/Eclipse.app/Contents/Eclipse"/>\n</interpreterType>\n</interpreterSettings>\n
/instance/org.eclipse.egit.core/GitRepositoriesView.GitDirectories=/Users/m134910/git_repos/nlp-clinical-medtagger.git/.git\:/Users/m134910/git_repos/nlp-clinical-medtagger/.git\:/Users/m134910/git_repos/mc-spring-boot-generic/.git\:/Users/m134910/git_repos/mayo-nlp-rules.git/.git\:/Users/m134910/git_repos/nlp-medtagger-common/.git\:/Users/m134910/git_repos/mayo-nlp-rules/.git\:/Users/m134910/git_repos/nlp-medtagger-common.git/.git\:/Users/m134910/git_repos/nlp-mea-rest/.git\:/Users/m134910/git_repos/nlp-mayo-storm/.git\:/Users/m134910/git_repos/nlp-es-rest/.git\:/Users/m134910/git_repos/test-data-framework/.git\:
/instance/org.eclipse.egit.core/GitRepositoriesView.GitDirectories.relative=/Users/m134910/git_repos/nlp-clinical-medtagger.git/.git\:/Users/m134910/git_repos/nlp-clinical-medtagger/.git\:/Users/m134910/git_repos/mc-spring-boot-generic/.git\:/Users/m134910/git_repos/mayo-nlp-rules.git/.git\:/Users/m134910/git_repos/nlp-medtagger-common/.git\:/Users/m134910/git_repos/mayo-nlp-rules/.git\:/Users/m134910/git_repos/nlp-medtagger-common.git/.git\:/Users/m134910/git_repos/nlp-mea-rest/.git\:/Users/m134910/git_repos/nlp-mayo-storm/.git\:/Users/m134910/git_repos/nlp-es-rest/.git\:/Users/m134910/git_repos/test-data-framework/.git\:
/instance/org.eclipse.egit.core/core_autoIgnoreDerivedResources=false
/instance/org.eclipse.egit.ui/commit_dialog_history_messages=<?xml version\="1.0" encoding\="UTF-8"?>\n<messages>\n<message>Update maven-shade-plugin to 2.4&\#x0A;&\#x0A;Updating this plugin appears to solve certain build issues for people&\#x0A;where the artifacts created by Maven couldn&apos;t be installed due to&\#x0A;&quot;Permission Denied&quot; issues.&\#x0A;</message>\n</messages>
/instance/org.eclipse.epp.logging.aeri.ide/resetSendMode=KEEP
/instance/org.eclipse.epp.logging.aeri.ide/resetSendModeOn=0
/instance/org.eclipse.epp.logging.aeri.ide/sendMode=NEVER
/instance/org.eclipse.epp.mpc.ui/CatalogDescriptor=http\://marketplace.eclipse.org
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.builder.resourceCopyExclusionFilter=
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.classpathVariable.JRE_LIB=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/lib/rt.jar
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.classpathVariable.JRE_SRC=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/src.zip
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.classpathVariable.JRE_SRCROOT=src
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.codeComplete.visibilityCheck=enabled
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.inlineJsrBytecode=enabled
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.targetPlatform=1.8
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.compliance=1.8
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.assertIdentifier=error
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.enumIdentifier=error
/instance/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.source=1.8
/instance/org.eclipse.jdt.launching/org.eclipse.jdt.launching.PREF_VM_XML=<?xml version\="1.0" encoding\="UTF-8" standalone\="no"?>\n<vmSettings defaultVM\="52,org.eclipse.jdt.internal.launching.macosx.MacOSXType25,com.oracle.java.8u102.jdk" defaultVMConnector\="">\n<vmType id\="org.eclipse.jdt.internal.launching.macosx.MacOSXType">\n<vm id\="com.oracle.java.8u102.jdk" name\="Java SE 8 [1.8.0_102]" path\="/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home"/>\n</vmType>\n</vmSettings>\n
/instance/org.eclipse.jdt.ui/content_assist_disabled_computers=org.eclipse.jdt.ui.textProposalCategory\u0000org.eclipse.recommenders.calls.rcp.proposalCategory.templates\u0000org.eclipse.mylyn.java.ui.javaAllProposalCategory\u0000org.eclipse.jdt.ui.javaAllProposalCategory\u0000org.eclipse.jdt.ui.javaTypeProposalCategory\u0000org.eclipse.jdt.ui.javaNoTypeProposalCategory\u0000org.eclipse.recommenders.chain.rcp.proposalCategory.chain\u0000
/instance/org.eclipse.jdt.ui/content_assist_favorite_static_members=org.assertj.core.api.Assertions.*;org.mockito.Matchers.*;org.mockito.Mockito.*;org.springframework.security.test.web.servlet.request.SecurityMockMvcRequestBuilders.*;org.springframework.security.test.web.servlet.request.SecurityMockMvcRequestPostProcessors.*;org.springframework.security.test.web.servlet.response.SecurityMockMvcResultMatchers.*;org.springframework.security.test.web.servlet.setup.SecurityMockMvcConfigurers.*;org.springframework.restdocs.mockmvc.MockMvcRestDocumentation.*;org.springframework.test.web.client.match.MockRestRequestMatchers.*;org.springframework.test.web.client.response.MockRestResponseCreators.*;org.springframework.test.web.servlet.request.MockMvcRequestBuilders.*;org.springframework.test.web.servlet.result.MockMvcResultHandlers.*;org.springframework.test.web.servlet.result.MockMvcResultMatchers.*;org.hamcrest.CoreMatchers.*;org.junit.Assert.*
/instance/org.eclipse.jdt.ui/content_assist_number_of_computers=30
/instance/org.eclipse.jdt.ui/content_assist_proposals_background=255,255,255
/instance/org.eclipse.jdt.ui/content_assist_proposals_foreground=0,0,0
/instance/org.eclipse.jdt.ui/fontPropagated=true
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.internal.ui.navigator.layout=2
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.internal.ui.navigator.librariesnode=true
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.ui.editor.tab.width=
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.ui.formatterprofiles.version=12
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.ui.javadoclocations.migrated=true
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.ui.text.code_templates_migrated=true
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.ui.text.custom_code_templates=<?xml version\="1.0" encoding\="UTF-8" standalone\="no"?><templates/>
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.ui.text.custom_templates=<?xml version\="1.0" encoding\="UTF-8" standalone\="no"?><templates/>
/instance/org.eclipse.jdt.ui/org.eclipse.jdt.ui.text.templates_migrated=true
/instance/org.eclipse.jdt.ui/org.eclipse.jface.textfont=1|Monaco|11.0|0|COCOA|1|;
/instance/org.eclipse.jdt.ui/proposalOrderMigrated=true
/instance/org.eclipse.jdt.ui/spelling_locale_initialized=true
/instance/org.eclipse.jdt.ui/tabWidthPropagated=true
/instance/org.eclipse.jdt.ui/useAnnotationsPrefPage=true
/instance/org.eclipse.jdt.ui/useQuickDiffPrefPage=true
/instance/org.eclipse.jst.j2ee.webservice.ui/areThereWebServices=false
/instance/org.eclipse.m2e.discovery/org.eclipse.m2e.discovery.pref.projects=
/instance/org.eclipse.mat.hprof/org.eclipse.mat.hprof.acquire.JMapHeapDumpProvider.lastJDKDir=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
/instance/org.eclipse.mat.hprof/org.eclipse.mat.hprof.acquire.JMapHeapDumpProvider.lastJmapJDKDir=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home
/instance/org.eclipse.mat.ibmdump/org.eclipse.mat.ibmvm.acquire.IBMExecDumpProvider.lastDir=/Library/Java/JavaVirtualMachines/jdk1.8.0_102.jdk/Contents/Home/jre/bin
/instance/org.eclipse.mat.ui/org.eclipse.mat.ui.internal.acquire.AcquireDialog.lastDir=/Users/m134910
/instance/org.eclipse.mat.ui/org.eclipse.mat.ui.snapshot.OpenSnapshot.lastDir=/Users/m134910
/instance/org.eclipse.mylyn.context.core/mylyn.attention.migrated=true
/instance/org.eclipse.mylyn.java.ui/org.eclipse.mylyn.java.ui.run.count.3_10_0=1
/instance/org.eclipse.mylyn.java.ui/org.eclipse.mylyn.java.ui.run.count.3_1_0=1
/instance/org.eclipse.mylyn.monitor.ui/org.eclipse.mylyn.monitor.activity.tracking.enabled.checked=true
/instance/org.eclipse.mylyn.tasks.ui/migrated.task.repositories.secure.store=true
/instance/org.eclipse.mylyn.tasks.ui/org.eclipse.mylyn.tasks.ui.filters.nonmatching=true
/instance/org.eclipse.mylyn.tasks.ui/org.eclipse.mylyn.tasks.ui.filters.nonmatching.encouraged=true
/instance/org.eclipse.mylyn.tasks.ui/org.eclipse.mylyn.tasks.ui.welcome.message=true
/instance/org.eclipse.oomph.workingsets/working.set.group=<?xml version\="1.0" encoding\="UTF-8"?>\n<workingsets\:WorkingSetGroup xmi\:version\="2.0" xmlns\:xmi\="http\://www.omg.org/XMI" xmlns\:workingsets\="http\://www.eclipse.org/oomph/workingsets/1.0"/>\n
/instance/org.eclipse.pde.api.tools/knownEEFragments=
/instance/org.eclipse.recommenders.completion.rcp/completion_tips_seen=org.eclipse.recommenders.completion.rcp.tips.discovery
/instance/org.eclipse.rse.core/activeuserprofiles=R5081566;Team
/instance/org.eclipse.rse.core/org.eclipse.rse.systemtype.local.systemType.defaultUserId=m134910
/instance/org.eclipse.rse.core/useridperkey=R5081566.Local\=m134910;
/instance/org.eclipse.rse.ui/org.eclipse.rse.preferences.order.connections=R5081566.Local
/instance/org.eclipse.search/org.eclipse.search.defaultPerspective=org.eclipse.search.defaultPerspective.none
/instance/org.eclipse.team.ui/org.eclipse.team.ui.first_time=false
/instance/org.eclipse.ui.editors/overviewRuler_migration=migrated_3.1
/instance/org.eclipse.ui.ide/PROBLEMS_FILTERS_MIGRATE=true
/instance/org.eclipse.ui.ide/platformState=1493664970877
/instance/org.eclipse.ui.ide/quickStart=false
/instance/org.eclipse.ui.ide/tipsAndTricks=true
/instance/org.eclipse.ui.workbench//org.eclipse.ui.commands/state/org.eclipse.ui.navigator.resources.nested.changeProjectPresentation/org.eclipse.ui.commands.radioState=false
/instance/org.eclipse.ui.workbench//org.eclipse.ui.commands/state/org.eclipse.wst.xml.views.XPathView.processor.xpathprocessor/org.eclipse.ui.commands.radioState=xpath10
/instance/org.eclipse.ui.workbench/PLUGINS_NOT_ACTIVATED_ON_STARTUP=org.eclipse.m2e.discovery;
/instance/org.eclipse.ui.workbench/org.eclipse.ui.commands=<?xml version\="1.0" encoding\="UTF-8"?>\n<org.eclipse.ui.commands>\n<activeKeyConfiguration keyConfigurationId\="org.eclipse.ui.emacsAcceleratorConfiguration"/>\n</org.eclipse.ui.commands>
/instance/org.eclipse.ui/KEY_CONFIGURATION_ID=org.eclipse.ui.emacsAcceleratorConfiguration
/instance/org.eclipse.ui/showIntro=false
/instance/org.eclipse.wst.jsdt.ui/fontPropagated=true
/instance/org.eclipse.wst.jsdt.ui/org.eclipse.jface.textfont=1|Monaco|11.0|0|COCOA|1|;
/instance/org.eclipse.wst.jsdt.ui/org.eclipse.wst.jsdt.internal.ui.navigator.layout=1
/instance/org.eclipse.wst.jsdt.ui/org.eclipse.wst.jsdt.ui.editor.tab.width=
/instance/org.eclipse.wst.jsdt.ui/org.eclipse.wst.jsdt.ui.formatterprofiles.version=11
/instance/org.eclipse.wst.jsdt.ui/org.eclipse.wst.jsdt.ui.javadoclocations.migrated=true
/instance/org.eclipse.wst.jsdt.ui/proposalOrderMigrated=true
/instance/org.eclipse.wst.jsdt.ui/tabWidthPropagated=true
/instance/org.eclipse.wst.jsdt.ui/useAnnotationsPrefPage=true
/instance/org.eclipse.wst.jsdt.ui/useQuickDiffPrefPage=true
/instance/org.eclipse.wst.sse.ui/content_assist_number_of_computers=20
/instance/org.eclipse.wst.sse.ui/useAnnotationsPrefPage=true
/instance/org.eclipse.wst.sse.ui/useQuickDiffPrefPage=true
/instance/org.eclipse.wst.ws.service.policy/org.eclipse.wst.ws.service.policy.ui.servicepols.wsiprofilecomp.wsiap.defaultProtocol=http\://schemas.xmlsoap.org/wsdl/soap/
/instance/org.eclipse.wst.ws.service.policy/org.eclipse.wst.ws.service.policy.ui.servicepols.wsiprofilecomp.wsissbp.defaultProtocol=http\://schemas.xmlsoap.org/wsdl/soap/
/instance/org.eclipse.wst.xml.ui/org.eclipse.wst.xml.ui.internal.tabletree.XMLMultiPageEditorPart.lastActivePage=1
/instance/org.python.pydev/INTERPRETERS_CHECKED_ONCE=true
/instance/org.scala-ide.sdt.core/org.scalaide.ui.config.defaultScalaHoverCss=/* It is also possible to change the font configuration here.\n * If one is configured, it will be preferred instead of the one\n * in the "Colors and Fonts" preference page.\n */\nhtml {}\n\nbody {\n  overflow\: auto;\n  margin\: 0.3em;\n}\n\nul {\n  list-style\: square;\n  margin-top\: 0;\n  margin-bottom\: 0;\n  margin-left\: 1em;\n}\n\nli {\n  margin-top\: 0.3em;\n  margin-bottom\: 0;\n}\n\ncode {\n  font-family\: monospace;\n  background-color\: \#eee;\n}\n\npre {\n  overflow\: auto;\n  background-color\: \#eee;\n}\n
/instance/org.scala-ide.sdt.core/org.scalaide.ui.config.scalaHoverCss=/* It is also possible to change the font configuration here.\n * If one is configured, it will be preferred instead of the one\n * in the "Colors and Fonts" preference page.\n */\nhtml {}\n\nbody {\n  overflow\: auto;\n  margin\: 0.3em;\n}\n\nul {\n  list-style\: square;\n  margin-top\: 0;\n  margin-bottom\: 0;\n  margin-left\: 1em;\n}\n\nli {\n  margin-top\: 0.3em;\n  margin-bottom\: 0;\n}\n\ncode {\n  font-family\: monospace;\n  background-color\: \#eee;\n}\n\npre {\n  overflow\: auto;\n  background-color\: \#eee;\n}\n
/instance/org.springframework.ide.eclipse.imports/org.springframework.ide.eclipse.imports.importStaticsInstanceScope=true
/instance/org.springsource.ide.eclipse.commons.configurator/org.springsource.ide.eclipse.commons.configurator.processed=true
/instance/org.springsource.ide.eclipse.commons.frameworks.core/org.springsource.ide.eclipse.commons.frameworks.ui.legacyconversion.done=true
/instance/org.springsource.ide.eclipse.commons.ui/egit.pref.fixed.core_autoIgnoreDerivedResources=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/name=download cache
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/uri=file\:/Users/m134910/.p2/org.eclipse.equinox.p2.core/cache/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_org.eclipse.equinox.p2.core_cache/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/name=Bundle pool
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/uri=file\:/Users/m134910/.p2/pool/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/name=/Users/m134910/.p2/pool/.eclipseextension
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/suffix=eclipse
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/type=org.eclipse.equinox.p2.extensionlocation.artifactRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/uri=file\:/Users/m134910/.p2/pool/.eclipseextension
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/version=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/name=dropins
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/uri=file\:/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/Eclipse/configuration/org.eclipse.osgi/345/data/listener_1925729951/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/name=org.springsource.sts.product
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/uri=http\://dist.springsource.com/release/TOOLS/update/3.8.4.RELEASE/e4.6/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/name=SpringSource Update Site for Eclipse 4.6
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/suffix=compositeArtifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/type=org.eclipse.equinox.internal.p2.artifact.repository.CompositeArtifactRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/uri=http\://dist.springsource.com/release/TOOLS/update/e4.6/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/name=Cloud Foundry Tools
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/suffix=compositeArtifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/type=org.eclipse.equinox.internal.p2.artifact.repository.CompositeArtifactRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/uri=http\://download.eclipse.org/cft/1.0.3/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/name=Cloud Foundry Tools
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/uri=http\://download.eclipse.org/cft/1.0.3/org.eclipse.cft-1.0.3.v201703012110
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/count=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/name=The Eclipse Project repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/nickname=The Eclipse Project Updates
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/suffix=compositeArtifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/type=org.eclipse.equinox.internal.p2.artifact.repository.CompositeArtifactRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/uri=http\://download.eclipse.org/eclipse/updates/4.6
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/name=Eclipse Project Repository for Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6-201606061100
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/name=Eclipse Project Repository for Neon.1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6.1-201609071200
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/name=Eclipse Project Repository for Neon.2
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6.2-201611241400
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/name=Eclipse Project Repository for Neon.3
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6.3-201703010400
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/name=Oomph S20170307-122318-1.7.0-M4
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/uri=http\://download.eclipse.org/oomph/drops/milestone/S20170307-122318-1.7.0-M4
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/name=Oomph Latest Milestone
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/suffix=compositeArtifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/type=org.eclipse.equinox.internal.p2.artifact.repository.CompositeArtifactRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/uri=http\://download.eclipse.org/oomph/updates/milestone/latest
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/count=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/name=Eclipse Repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/nickname=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/suffix=compositeArtifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/type=org.eclipse.equinox.internal.p2.artifact.repository.CompositeArtifactRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/uri=http\://download.eclipse.org/releases/neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/name=neon/201606221000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/uri=http\://download.eclipse.org/releases/neon/201606221000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/name=neon/201609281000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/uri=http\://download.eclipse.org/releases/neon/201609281000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/name=neon/201610111000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/uri=http\://download.eclipse.org/releases/neon/201610111000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/name=neon/201612211000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/uri=http\://download.eclipse.org/releases/neon/201612211000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/name=neon/201703141400
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/uri=http\://download.eclipse.org/releases/neon/201703141400
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/name=neon/201703231000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/suffix=artifacts.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/uri=http\://download.eclipse.org/releases/neon/201703231000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/uri=http\://download.eclipse.org/technology/epp/packages/neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/R-3.8.0-20160608130753/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M4-20151215010029/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M5-20160202064558/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M6-20160324010110/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M7-20160503010110/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0RC3-20160601010110/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.1/R-3.8.1-20160912100321/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/count=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/name=The Eclipse Web Tools Platform (WTP) software repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/nickname=The Eclipse Web Tools Platform (WTP) software repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/suffix=compositeArtifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/type=org.eclipse.equinox.internal.p2.artifact.repository.CompositeArtifactRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/uri=http\://download.eclipse.org/webtools/repository/neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/name=com.github.eclipsecolortheme.updatesite
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/suffix=artifacts.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/type=org.eclipse.equinox.p2.artifact.repository.simpleRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/uri=http\://eclipse-color-theme.github.com/update
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.artifact.repository/repositories/http\:__eclipse-color-theme.github.com_update/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/name=/Users/m134910/.p2/pool/.eclipseextension
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/suffix=eclipse
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/type=org.eclipse.equinox.p2.extensionlocation.metadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/uri=file\:/Users/m134910/.p2/pool/.eclipseextension
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_.p2_pool_.eclipseextension/version=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/name=dropins
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/uri=file\:/Users/m134910/eclipse/jee-neon/Eclipse.app/Contents/Eclipse/configuration/org.eclipse.osgi/345/data/listener_1925729951/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/file\:_Users_m134910_eclipse_jee-neon_Eclipse.app_Contents_Eclipse_configuration_org.eclipse.osgi_345_data_listener_1925729951/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/name=org.springsource.sts.product
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/uri=http\://dist.springsource.com/release/TOOLS/update/3.8.4.RELEASE/e4.6/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_3.8.4.RELEASE_e4.6/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/name=SpringSource Update Site for Eclipse 4.5
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/suffix=compositeContent.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/type=org.eclipse.equinox.internal.p2.metadata.repository.CompositeMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/uri=http\://dist.springsource.com/release/TOOLS/update/e4.6/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__dist.springsource.com_release_TOOLS_update_e4.6/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/name=Cloud Foundry Tools
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/suffix=compositeContent.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/type=org.eclipse.equinox.internal.p2.metadata.repository.CompositeMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/uri=http\://download.eclipse.org/cft/1.0.3/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/name=Cloud Foundry Tools
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/uri=http\://download.eclipse.org/cft/1.0.3/org.eclipse.cft-1.0.3.v201703012110
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_cft_1.0.3_org.eclipse.cft-1.0.3.v201703012110/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/count=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/name=The Eclipse Project repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/nickname=The Eclipse Project Updates
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/suffix=compositeContent.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/type=org.eclipse.equinox.internal.p2.metadata.repository.CompositeMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/uri=http\://download.eclipse.org/eclipse/updates/4.6
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/name=Eclipse Project Repository for Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6-201606061100
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6-201606061100/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/name=Eclipse Project Repository for Neon.1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6.1-201609071200
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.1-201609071200/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/name=Eclipse Project Repository for Neon.2
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6.2-201611241400
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.2-201611241400/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/name=Eclipse Project Repository for Neon.3
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/uri=http\://download.eclipse.org/eclipse/updates/4.6/R-4.6.3-201703010400
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_R-4.6.3-201703010400/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_categoriesNeon/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_categoriesNeon/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_categoriesNeon/name=The Eclipse Project Updates
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_categoriesNeon/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_categoriesNeon/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_categoriesNeon/uri=http\://download.eclipse.org/eclipse/updates/4.6/categoriesNeon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_eclipse_updates_4.6_categoriesNeon/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/name=Oomph S20170307-122318-1.7.0-M4
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/uri=http\://download.eclipse.org/oomph/drops/milestone/S20170307-122318-1.7.0-M4
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_drops_milestone_S20170307-122318-1.7.0-M4/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/name=Oomph Latest Milestone
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/suffix=compositeContent.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/type=org.eclipse.equinox.internal.p2.metadata.repository.CompositeMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/uri=http\://download.eclipse.org/oomph/updates/milestone/latest
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_oomph_updates_milestone_latest/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/count=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/name=Eclipse Repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/nickname=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/suffix=compositeContent.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/type=org.eclipse.equinox.internal.p2.metadata.repository.CompositeMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/uri=http\://download.eclipse.org/releases/neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/name=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/uri=http\://download.eclipse.org/releases/neon/201606221000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201606221000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/name=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/uri=http\://download.eclipse.org/releases/neon/201609281000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201609281000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/name=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/uri=http\://download.eclipse.org/releases/neon/201610111000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201610111000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/name=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/uri=http\://download.eclipse.org/releases/neon/201612211000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201612211000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/name=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/uri=http\://download.eclipse.org/releases/neon/201703141400
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703141400/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/name=Neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/uri=http\://download.eclipse.org/releases/neon/201703231000
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_releases_neon_201703231000/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/suffix=content.xml.xz
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/uri=http\://download.eclipse.org/technology/epp/packages/neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_technology_epp_packages_neon/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/R-3.8.0-20160608130753/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_R-3.8.0-20160608130753_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M4-20151215010029/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M4-20151215010029_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M5-20160202064558/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M5-20160202064558_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M6-20160324010110/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M6-20160324010110_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0M7-20160503010110/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0M7-20160503010110_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.0/S-3.8.0RC3-20160601010110/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.0_S-3.8.0RC3-20160601010110_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/enabled=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/isSystem=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/name=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/uri=http\://download.eclipse.org/webtools/downloads/drops/R3.8.1/R-3.8.1-20160912100321/repository/
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_downloads_drops_R3.8.1_R-3.8.1-20160912100321_repository/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/count=1
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/description=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/name=The Eclipse Web Tools Platform (WTP) software repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/nickname=The Eclipse Web Tools Platform (WTP) software repository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/provider=
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/suffix=compositeContent.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/type=org.eclipse.equinox.internal.p2.metadata.repository.CompositeMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/uri=http\://download.eclipse.org/webtools/repository/neon
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__download.eclipse.org_webtools_repository_neon/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__eclipse-color-theme.github.com_update/enabled=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__eclipse-color-theme.github.com_update/isSystem=false
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__eclipse-color-theme.github.com_update/name=com.github.eclipsecolortheme.updatesite
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__eclipse-color-theme.github.com_update/suffix=content.xml
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__eclipse-color-theme.github.com_update/type=org.eclipse.equinox.internal.p2.metadata.repository.LocalMetadataRepository
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__eclipse-color-theme.github.com_update/uri=http\://eclipse-color-theme.github.com/update
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.metadata.repository/repositories/http\:__eclipse-color-theme.github.com_update/version=1.0.0
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.ui.sdk.scheduler/autoUpdateInit=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.ui.sdk.scheduler/lastAutoCheckForUpdates=2017-05-01T13\:56\:45.596-0500
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.ui.sdk.scheduler/migrated34Prefs=true
/profile/file\:\\2fUsers\\2fm134910\\2f.p2\\2f/_SELF_/org.eclipse.equinox.p2.ui.sdk/allowNonOKPlan=prompt
/project/mc-spring-boot-generic/org.eclipse.core.resources/encoding//src/main/java=UTF-8
/project/mc-spring-boot-generic/org.eclipse.core.resources/encoding//src/main/resources=UTF-8
/project/mc-spring-boot-generic/org.eclipse.core.resources/encoding//src/test/java=UTF-8
/project/mc-spring-boot-generic/org.eclipse.core.resources/encoding/<project>=UTF-8
/project/mc-spring-boot-generic/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.codegen.targetPlatform=1.6
/project/mc-spring-boot-generic/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.compliance=1.6
/project/mc-spring-boot-generic/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.problem.forbiddenReference=warning
/project/mc-spring-boot-generic/org.eclipse.jdt.core/org.eclipse.jdt.core.compiler.source=1.6
/project/mc-spring-boot-generic/org.eclipse.wst.validation/disabled=06target
@org.eclipse.core.net=1.3.0.v20160418-1534
@org.eclipse.core.resources=3.11.1.v20161107-2032
@org.eclipse.debug.ui=3.11.202.v20161114-0338
@org.eclipse.egit.core=4.6.1.201703071140-r
@org.eclipse.egit.ui=4.6.1.201703071140-r
@org.eclipse.epp.logging.aeri.ide=2.0.4.v20170307-1435
@org.eclipse.epp.mpc.ui=1.5.4.v20170222-1941
@org.eclipse.jdt.core=3.12.3.v20170228-1205
@org.eclipse.jdt.launching=3.8.101.v20161111-2014
@org.eclipse.jdt.ui=3.12.2.v20160929-0804
@org.eclipse.jst.j2ee.webservice.ui=1.1.500.v201302011850
@org.eclipse.m2e.discovery=1.7.0.20160603-1933
@org.eclipse.mylyn.context.core=3.21.0.v20160701-1337
@org.eclipse.mylyn.java.ui=3.21.0.v20160701-1337
@org.eclipse.mylyn.monitor.ui=3.21.0.v20160630-1702
@org.eclipse.mylyn.tasks.ui=3.21.0.v20160913-2131
@org.eclipse.oomph.workingsets=1.7.0.v20170104-1401
@org.eclipse.pde.api.tools=1.1.2.v20161115-0549
@org.eclipse.recommenders.completion.rcp=2.4.6.v20170307-1041
@org.eclipse.rse.core=3.3.100.201603151753
@org.eclipse.rse.ui=3.3.300.201610252046
@org.eclipse.search=3.11.1.v20161113-1700
@org.eclipse.team.ui=3.8.0.v20160518-1906
@org.eclipse.ui=3.108.1.v20160929-1045
@org.eclipse.ui.editors=3.10.1.v20161106-1856
@org.eclipse.ui.ide=3.12.3.v20170119-0935
@org.eclipse.ui.workbench=3.108.3.v20170216-1539
@org.eclipse.wst.jsdt.ui=2.0.200.v201612151739
@org.eclipse.wst.sse.ui=1.3.500.v201605120129
@org.eclipse.wst.ws.service.policy=1.0.450.v201505131719
@org.eclipse.wst.xml.ui=1.1.700.v201604272318
@org.springframework.ide.eclipse.imports=3.8.4.201703310634-RELEASE
@org.springsource.ide.eclipse.commons.configurator=3.8.4.201703310458-RELEASE
@org.springsource.ide.eclipse.commons.frameworks.core=3.8.4.201703310458-RELEASE
@org.springsource.ide.eclipse.commons.ui=3.8.4.201703310458-RELEASE
file_export_version=3.0

*** Current Install Configuration:

Bundles in the system:

Id: ch.qos.logback.classic, Version: 1.0.7.v20121108-1250, Location: reference:file:/Users/m134910/.p2/pool/plugins/ch.qos.logback.classic_1.0.7.v20121108-1250.jar
Id: ch.qos.logback.core, Version: 1.0.7.v20121108-1250, Location: reference:file:/Users/m134910/.p2/pool/plugins/ch.qos.logback.core_1.0.7.v20121108-1250.jar
Id: ch.qos.logback.slf4j, Version: 1.0.7.v201505121915, Location: reference:file:/Users/m134910/.p2/pool/plugins/ch.qos.logback.slf4j_1.0.7.v201505121915.jar
Id: com.fasterxml.jackson.core.jackson-annotations, Version: 2.6.2.v20161117-2150, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.fasterxml.jackson.core.jackson-annotations_2.6.2.v20161117-2150.jar
Id: com.fasterxml.jackson.core.jackson-core, Version: 2.6.2.v20161117-2150, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.fasterxml.jackson.core.jackson-core_2.6.2.v20161117-2150.jar
Id: com.fasterxml.jackson.core.jackson-databind, Version: 2.6.2.v20161117-2150, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.fasterxml.jackson.core.jackson-databind_2.6.2.v20161117-2150.jar
Id: com.github.eclipsecolortheme, Version: 1.0.0.201410260308, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.github.eclipsecolortheme_1.0.0.201410260308.jar
Id: com.google.gson, Version: 2.2.4.v201311231704, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.google.gson_2.2.4.v201311231704.jar
Id: com.google.guava, Version: 15.0.0.v201403281430, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.google.guava_15.0.0.v201403281430.jar
Id: com.google.inject, Version: 3.0.0.v201605172100, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.google.inject_3.0.0.v201605172100.jar
Id: com.google.inject.multibindings, Version: 3.0.0.v201605172100, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.google.inject.multibindings_3.0.0.v201605172100.jar
Id: com.google.protobuf, Version: 2.4.0.v201105131100, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.google.protobuf_2.4.0.v201105131100.jar
Id: com.ibm.icu, Version: 56.1.0.v201601250100, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.ibm.icu_56.1.0.v201601250100.jar
Id: com.jcraft.jsch, Version: 0.1.54.v20170116-1932, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.jcraft.jsch_0.1.54.v20170116-1932.jar
Id: com.sun.el, Version: 2.2.0.v201303151357, Location: reference:file:/Users/m134910/.p2/pool/plugins/com.sun.el_2.2.0.v201303151357.jar
Id: io.projectreactor.reactor-core, Version: 3.0.5.201703211214-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/io.projectreactor.reactor-core_3.0.5.201703211214-RELEASE.jar
Id: java_cup.runtime, Version: 0.10.0.v201005080400, Location: reference:file:/Users/m134910/.p2/pool/plugins/java_cup.runtime_0.10.0.v201005080400.jar
Id: javaewah, Version: 1.1.6.v20160919-1400, Location: reference:file:/Users/m134910/.p2/pool/plugins/javaewah_1.1.6.v20160919-1400.jar
Id: javax.activation, Version: 1.1.0.v201211130549, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.activation_1.1.0.v201211130549.jar
Id: javax.annotation, Version: 1.2.0.v201602091430, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.annotation_1.2.0.v201602091430.jar
Id: javax.el, Version: 2.2.0.v201303151357, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.el_2.2.0.v201303151357.jar
Id: javax.inject, Version: 1.0.0.v20091030, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.inject_1.0.0.v20091030.jar
Id: javax.jms, Version: 1.1.0.v201205091237, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.jms_1.1.0.v201205091237.jar
Id: javax.jws, Version: 2.0.0.v201005080400, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.jws_2.0.0.v201005080400.jar
Id: javax.mail, Version: 1.4.0.v201005080615, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.mail_1.4.0.v201005080615.jar
Id: javax.persistence, Version: 2.1.0.v201304241213, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.persistence_2.1.0.v201304241213.jar
Id: javax.servlet, Version: 3.1.0.v201410161800, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.servlet_3.1.0.v201410161800.jar
Id: javax.servlet.jsp, Version: 2.2.0.v201112011158, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.servlet.jsp_2.2.0.v201112011158.jar
Id: javax.validation, Version: 1.0.0.GA_v201205091237, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.validation_1.0.0.GA_v201205091237.jar
Id: javax.wsdl, Version: 1.5.1.v201012040544, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.wsdl_1.5.1.v201012040544.jar
Id: javax.wsdl, Version: 1.6.2.v201012040545, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.wsdl_1.6.2.v201012040545.jar
Id: javax.xml, Version: 1.3.4.v201005080400, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.xml_1.3.4.v201005080400.jar
Id: javax.xml.rpc, Version: 1.1.0.v201209140446, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.xml.rpc_1.1.0.v201209140446
Id: javax.xml.soap, Version: 1.2.0.v201005080501, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.xml.soap_1.2.0.v201005080501
Id: javax.xml.stream, Version: 1.0.1.v201004272200, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.xml.stream_1.0.1.v201004272200.jar
Id: javax.xml.ws, Version: 2.1.0.v200902101523, Location: reference:file:/Users/m134910/.p2/pool/plugins/javax.xml.ws_2.1.0.v200902101523.jar
Id: net.sourceforge.lpg.lpgjavaruntime, Version: 1.1.0.v201004271650, Location: reference:file:/Users/m134910/.p2/pool/plugins/net.sourceforge.lpg.lpgjavaruntime_1.1.0.v201004271650.jar
Id: org.aopalliance, Version: 1.0.0.v201105210816, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.aopalliance_1.0.0.v201105210816.jar
Id: org.apache.ant, Version: 1.9.6.v201510161327, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.ant_1.9.6.v201510161327
Id: org.apache.axis, Version: 1.4.0.v201411182030, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.axis_1.4.0.v201411182030
Id: org.apache.batik.css, Version: 1.7.0.v201011041433, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.batik.css_1.7.0.v201011041433.jar
Id: org.apache.batik.util, Version: 1.7.0.v201011041433, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.batik.util_1.7.0.v201011041433.jar
Id: org.apache.batik.util.gui, Version: 1.7.0.v200903091627, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.batik.util.gui_1.7.0.v200903091627.jar
Id: org.apache.bcel, Version: 5.2.0.v201005080400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.bcel_5.2.0.v201005080400.jar
Id: org.apache.commons.codec, Version: 1.6.0.v201305230611, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.codec_1.6.0.v201305230611.jar
Id: org.apache.commons.collections, Version: 3.2.2.v201511171945, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.collections_3.2.2.v201511171945.jar
Id: org.apache.commons.compress, Version: 1.6.0.v201310281400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.compress_1.6.0.v201310281400.jar
Id: org.apache.commons.discovery, Version: 0.2.0.v201004190315, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.discovery_0.2.0.v201004190315
Id: org.apache.commons.httpclient, Version: 3.1.0.v201012070820, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.httpclient_3.1.0.v201012070820.jar
Id: org.apache.commons.io, Version: 2.2.0.v201405211200, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.io_2.2.0.v201405211200.jar
Id: org.apache.commons.jxpath, Version: 1.3.0.v200911051830, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.jxpath_1.3.0.v200911051830.jar
Id: org.apache.commons.lang, Version: 2.6.0.v201404270220, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.lang_2.6.0.v201404270220.jar
Id: org.apache.commons.lang3, Version: 3.1.0.v201403281430, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.lang3_3.1.0.v201403281430.jar
Id: org.apache.commons.logging, Version: 1.0.4.v201101211617, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.logging_1.0.4.v201101211617.jar
Id: org.apache.commons.logging, Version: 1.1.1.v201101211721, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.logging_1.1.1.v201101211721.jar
Id: org.apache.commons.math, Version: 2.1.0.v201105210652, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.math_2.1.0.v201105210652.jar
Id: org.apache.commons.net, Version: 3.2.0.v201305141515, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.net_3.2.0.v201305141515.jar
Id: org.apache.commons.pool, Version: 1.6.0.v201204271246, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.commons.pool_1.6.0.v201204271246.jar
Id: org.apache.felix.gogo.command, Version: 0.10.0.v201209301215, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.felix.gogo.command_0.10.0.v201209301215.jar
Id: org.apache.felix.gogo.runtime, Version: 0.10.0.v201209301036, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.felix.gogo.runtime_0.10.0.v201209301036.jar
Id: org.apache.felix.gogo.shell, Version: 0.10.0.v201212101605, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.felix.gogo.shell_0.10.0.v201212101605.jar
Id: org.apache.httpcomponents.httpclient, Version: 4.3.6.v201511171540, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.httpcomponents.httpclient_4.3.6.v201511171540.jar
Id: org.apache.httpcomponents.httpcore, Version: 4.3.3.v201411290715, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.httpcomponents.httpcore_4.3.3.v201411290715.jar
Id: org.apache.jasper.glassfish, Version: 2.2.2.v201501141630, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.jasper.glassfish_2.2.2.v201501141630.jar
Id: org.apache.log4j, Version: 1.2.15.v201012070815, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.log4j_1.2.15.v201012070815.jar
Id: org.apache.lucene.analysis, Version: 3.5.0.v20120725-1805, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.lucene.analysis_3.5.0.v20120725-1805.jar
Id: org.apache.lucene.core, Version: 3.5.0.v20120725-1805, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.lucene.core_3.5.0.v20120725-1805.jar
Id: org.apache.solr.client.solrj, Version: 3.5.0.v20150506-0844, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.solr.client.solrj_3.5.0.v20150506-0844.jar
Id: org.apache.velocity, Version: 1.5.0.v200905192330, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.velocity_1.5.0.v200905192330.jar
Id: org.apache.ws.commons.util, Version: 1.0.1.v20100518-1140, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.ws.commons.util_1.0.1.v20100518-1140.jar
Id: org.apache.wsil4j, Version: 1.0.0.v200901211807, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.wsil4j_1.0.0.v200901211807.jar
Id: org.apache.xalan, Version: 2.7.1.v201005080400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.xalan_2.7.1.v201005080400.jar
Id: org.apache.xerces, Version: 2.9.0.v201101211617, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.xerces_2.9.0.v201101211617.jar
Id: org.apache.xml.resolver, Version: 1.2.0.v201005080400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.xml.resolver_1.2.0.v201005080400.jar
Id: org.apache.xml.serializer, Version: 2.7.1.v201005080400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.xml.serializer_2.7.1.v201005080400.jar
Id: org.apache.xmlrpc, Version: 3.0.0.v20100427-1100, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.apache.xmlrpc_3.0.0.v20100427-1100.jar
Id: org.aspectj.runtime, Version: 1.8.10.201703272045, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.aspectj.runtime_1.8.10.201703272045.jar
Id: org.aspectj.weaver, Version: 1.8.10.201703272045, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.aspectj.weaver_1.8.10.201703272045.jar
Id: org.codehaus.jackson.core, Version: 1.6.0.v20101005-0925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.codehaus.jackson.core_1.6.0.v20101005-0925.jar
Id: org.codehaus.jackson.mapper, Version: 1.6.0.v20101005-0925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.codehaus.jackson.mapper_1.6.0.v20101005-0925.jar
Id: org.dadacoalition.yedit, Version: 1.0.18.201602092025-RELEASE-SIGNED, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.dadacoalition.yedit_1.0.18.201602092025-RELEASE-SIGNED.jar
Id: org.eclipse.aether.api, Version: 1.0.1.v20141111, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.api_1.0.1.v20141111.jar
Id: org.eclipse.aether.connector.basic, Version: 1.0.1.v20141111, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.connector.basic_1.0.1.v20141111.jar
Id: org.eclipse.aether.impl, Version: 1.0.1.v20141111, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.impl_1.0.1.v20141111.jar
Id: org.eclipse.aether.maven, Version: 3.1.0.v20140706-2237, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.maven_3.1.0.v20140706-2237.jar
Id: org.eclipse.aether.spi, Version: 1.0.1.v20141111, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.spi_1.0.1.v20141111.jar
Id: org.eclipse.aether.transport.file, Version: 1.0.1.v20141111, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.transport.file_1.0.1.v20141111.jar
Id: org.eclipse.aether.transport.http, Version: 1.0.1.v20141111, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.transport.http_1.0.1.v20141111.jar
Id: org.eclipse.aether.util, Version: 1.0.1.v20141111, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.aether.util_1.0.1.v20141111.jar
Id: org.eclipse.ant.core, Version: 3.4.100.v20160505-0642, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ant.core_3.4.100.v20160505-0642.jar
Id: org.eclipse.ant.launching, Version: 1.1.201.v20161115-1135, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ant.launching_1.1.201.v20161115-1135.jar
Id: org.eclipse.ant.ui, Version: 3.6.201.v20161115-1135, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ant.ui_3.6.201.v20161115-1135.jar
Id: org.eclipse.cdt.core.macosx, Version: 5.3.0.201703062208, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cdt.core.macosx_5.3.0.201703062208.jar
Id: org.eclipse.cdt.core.native, Version: 5.10.0.201703062208, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cdt.core.native_5.10.0.201703062208.jar
Id: org.eclipse.cft.server.branding.core, Version: 1.0.2.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.branding.core_1.0.2.v201703012110.jar
Id: org.eclipse.cft.server.branding.ui, Version: 1.0.2.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.branding.ui_1.0.2.v201703012110.jar
Id: org.eclipse.cft.server.core, Version: 1.2.1.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.core_1.2.1.v201703012110.jar
Id: org.eclipse.cft.server.rse, Version: 1.0.1.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.rse_1.0.1.v201703012110.jar
Id: org.eclipse.cft.server.standalone.core, Version: 1.0.4.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.standalone.core_1.0.4.v201703012110.jar
Id: org.eclipse.cft.server.standalone.ui, Version: 1.0.4.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.standalone.ui_1.0.4.v201703012110.jar
Id: org.eclipse.cft.server.ui, Version: 1.0.108.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.ui_1.0.108.v201703012110.jar
Id: org.eclipse.cft.server.verify.ui, Version: 1.0.1.v201703012110, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.cft.server.verify.ui_1.0.1.v201703012110.jar
Id: org.eclipse.compare, Version: 3.7.1.v20170103-1805, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.compare_3.7.1.v20170103-1805.jar
Id: org.eclipse.compare.core, Version: 3.6.0.v20160418-1534, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.compare.core_3.6.0.v20160418-1534.jar
Id: org.eclipse.core.commands, Version: 3.8.1.v20161221-1651, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.commands_3.8.1.v20161221-1651.jar
Id: org.eclipse.core.contenttype, Version: 3.5.100.v20160418-1621, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.contenttype_3.5.100.v20160418-1621.jar
Id: org.eclipse.core.databinding, Version: 1.6.0.v20160412-0910, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.databinding_1.6.0.v20160412-0910.jar
Id: org.eclipse.core.databinding.beans, Version: 1.3.100.v20160509-1025, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.databinding.beans_1.3.100.v20160509-1025.jar
Id: org.eclipse.core.databinding.observable, Version: 1.6.0.v20160511-1747, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.databinding.observable_1.6.0.v20160511-1747.jar
Id: org.eclipse.core.databinding.property, Version: 1.6.0.v20160427-0852, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.databinding.property_1.6.0.v20160427-0852.jar
Id: org.eclipse.core.expressions, Version: 3.5.100.v20160418-1621, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.expressions_3.5.100.v20160418-1621.jar
Id: org.eclipse.core.externaltools, Version: 1.0.400.v20160509-1057, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.externaltools_1.0.400.v20160509-1057.jar
Id: org.eclipse.core.filebuffers, Version: 3.6.0.v20160503-1849, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.filebuffers_3.6.0.v20160503-1849.jar
Id: org.eclipse.core.filesystem, Version: 1.6.1.v20161113-2349, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.filesystem_1.6.1.v20161113-2349.jar
Id: org.eclipse.core.filesystem.macosx, Version: 1.3.0.v20140124-1940, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.filesystem.macosx_1.3.0.v20140124-1940.jar
Id: org.eclipse.core.jobs, Version: 3.8.0.v20160509-0411, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.jobs_3.8.0.v20160509-0411.jar
Id: org.eclipse.core.net, Version: 1.3.0.v20160418-1534, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.net_1.3.0.v20160418-1534.jar
Id: org.eclipse.core.resources, Version: 3.11.1.v20161107-2032, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.resources_3.11.1.v20161107-2032.jar
Id: org.eclipse.core.runtime, Version: 3.12.0.v20160606-1342, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.runtime_3.12.0.v20160606-1342.jar
Id: org.eclipse.core.variables, Version: 3.3.0.v20160419-1720, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.core.variables_3.3.0.v20160419-1720.jar
Id: org.eclipse.datatools.common.doc.user, Version: 1.7.0.20090521092446, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.common.doc.user_1.7.0.20090521092446.jar
Id: org.eclipse.datatools.connectivity, Version: 1.13.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity_1.13.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.apache.derby, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.apache.derby_1.1.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.apache.derby.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.apache.derby.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.apache.derby.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.apache.derby.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.console.profile, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.console.profile_1.1.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.db.generic, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.db.generic_1.1.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.db.generic.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.db.generic.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.dbdefinition.genericJDBC, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.dbdefinition.genericJDBC_1.1.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.doc.user, Version: 1.7.0.20090521092446, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.doc.user_1.7.0.20090521092446.jar
Id: org.eclipse.datatools.connectivity.doc.user.contexts, Version: 1.7.0.20090521092446, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.doc.user.contexts_1.7.0.20090521092446.jar
Id: org.eclipse.datatools.connectivity.oda, Version: 3.5.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda_3.5.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.oda.consumer, Version: 3.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda.consumer_3.3.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.oda.design, Version: 3.4.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda.design_3.4.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.oda.design.ui, Version: 3.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda.design.ui_3.3.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.oda.flatfile, Version: 3.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda.flatfile_3.2.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.oda.flatfile.ui, Version: 3.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda.flatfile.ui_3.2.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.oda.profile, Version: 3.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda.profile_3.3.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.oda.template.ui, Version: 3.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.oda.template.ui_3.3.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.sqm.core, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.sqm.core_1.3.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.sqm.core.ui, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.sqm.core.ui_1.3.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.sqm.server.ui, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.sqm.server.ui_1.2.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.ui, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.ui_1.3.0.201603142002.jar
Id: org.eclipse.datatools.connectivity.ui.dse, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.connectivity.ui.dse_1.2.0.201603142002.jar
Id: org.eclipse.datatools.doc.user, Version: 1.7.0.20090521092446, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.doc.user_1.7.0.20090521092446.jar
Id: org.eclipse.datatools.enablement.finfo, Version: 1.6.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.finfo_1.6.0.201603142002.jar
Id: org.eclipse.datatools.enablement.hsqldb, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.hsqldb_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.hsqldb.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.hsqldb.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.hsqldb.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.hsqldb.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.iseries, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.iseries_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.iseries.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.iseries.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.iseries.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.iseries.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.luw, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.luw_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.luw.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.luw.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.luw.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.luw.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.zseries, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.zseries_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.zseries.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.zseries.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.db2.zseries.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.db2.zseries.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.informix, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.informix_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.informix.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.informix.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.informix.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.informix.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ibm.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ibm.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ingres, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ingres_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ingres.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ingres.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.ingres.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.ingres.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.jdt.classpath, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.jdt.classpath_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.msft.sqlserver, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.msft.sqlserver_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.msft.sqlserver.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.msft.sqlserver.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.msft.sqlserver.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.msft.sqlserver.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.mysql, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.mysql_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.mysql.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.mysql.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.mysql.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.mysql.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.oda.ws, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.oda.ws_1.3.0.201603142002.jar
Id: org.eclipse.datatools.enablement.oda.ws.ui, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.oda.ws.ui_1.3.0.201603142002.jar
Id: org.eclipse.datatools.enablement.oda.xml, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.oda.xml_1.3.0.201603142002.jar
Id: org.eclipse.datatools.enablement.oda.xml.ui, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.oda.xml.ui_1.3.0.201603142002.jar
Id: org.eclipse.datatools.enablement.oracle, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.oracle_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.oracle.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.oracle.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.oracle.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.oracle.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.postgresql, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.postgresql_1.2.0.201603142002.jar
Id: org.eclipse.datatools.enablement.postgresql.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.postgresql.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.postgresql.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.postgresql.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sap.maxdb, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sap.maxdb_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sap.maxdb.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sap.maxdb.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sap.maxdb.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sap.maxdb.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sqlite, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sqlite_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sqlite.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sqlite.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sqlite.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sqlite.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.asa, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.asa_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.asa.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.asa.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.asa.models, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.asa.models_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.asa.schemaobjecteditor.examples, Version: 2.6.0.200810071, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.asa.schemaobjecteditor.examples_2.6.0.200810071.jar
Id: org.eclipse.datatools.enablement.sybase.asa.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.asa.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.ase, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.ase_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.ase.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.ase.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.ase.models, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.ase.models_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.ase.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.ase.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.models, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.models_1.1.0.201603142002.jar
Id: org.eclipse.datatools.enablement.sybase.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.enablement.sybase.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.help, Version: 1.6.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.help_1.6.0.201603142002.jar
Id: org.eclipse.datatools.intro, Version: 1.7.0.v201005281800, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.intro_1.7.0.v201005281800.jar
Id: org.eclipse.datatools.modelbase.dbdefinition, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.modelbase.dbdefinition_1.1.0.201603142002.jar
Id: org.eclipse.datatools.modelbase.derby, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.modelbase.derby_1.1.0.201603142002.jar
Id: org.eclipse.datatools.modelbase.sql, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.modelbase.sql_1.1.0.201603142002.jar
Id: org.eclipse.datatools.modelbase.sql.edit, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.modelbase.sql.edit_1.1.0.201603142002.jar
Id: org.eclipse.datatools.modelbase.sql.query, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.modelbase.sql.query_1.2.0.201603142002.jar
Id: org.eclipse.datatools.modelbase.sql.query.edit, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.modelbase.sql.query.edit_1.1.0.201603142002.jar
Id: org.eclipse.datatools.modelbase.sql.xml.query, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.modelbase.sql.xml.query_1.1.0.201603142002.jar
Id: org.eclipse.datatools.oda.cshelp, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.oda.cshelp_1.2.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.common.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.common.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.data.core, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.data.core_1.3.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.data.ui, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.data.ui_1.3.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.db.derby, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.db.derby_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.db.derby.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.db.derby.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.db.generic, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.db.generic_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.db.generic.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.db.generic.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.ddlgen.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.ddlgen.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.debugger.core, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.debugger.core_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.debugger.core.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.debugger.core.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.doc.user, Version: 1.7.0.20090521092446, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.doc.user_1.7.0.20090521092446.jar
Id: org.eclipse.datatools.sqltools.doc.user.contexts, Version: 1.7.0.20090521092446, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.doc.user.contexts_1.7.0.20090521092446.jar
Id: org.eclipse.datatools.sqltools.editor.core, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.editor.core_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.editor.core.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.editor.core.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.parsers.sql, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.parsers.sql_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.parsers.sql.lexer, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.parsers.sql.lexer_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.parsers.sql.query, Version: 1.3.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.parsers.sql.query_1.3.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.parsers.sql.xml.query, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.parsers.sql.xml.query_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.plan, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.plan_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.result, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.result_1.2.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.result.ui, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.result.ui_1.2.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.routineeditor, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.routineeditor_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.routineeditor.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.routineeditor.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.schemaobjecteditor, Version: 1.2.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.schemaobjecteditor_1.2.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.schemaobjecteditor.ui, Version: 1.2.0.200810071, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.schemaobjecteditor.ui_1.2.0.200810071.jar
Id: org.eclipse.datatools.sqltools.schemaobjecteditor.ui.pages, Version: 1.2.0.200810071, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.schemaobjecteditor.ui.pages_1.2.0.200810071.jar
Id: org.eclipse.datatools.sqltools.sql, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.sql_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.sql.ui, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.sql.ui_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.sqlbuilder, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.sqlbuilder_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.sqleditor, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.sqleditor_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.sqlscrapbook, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.sqlscrapbook_1.1.0.201603142002.jar
Id: org.eclipse.datatools.sqltools.tabledataeditor, Version: 1.1.0.201603142002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.datatools.sqltools.tabledataeditor_1.1.0.201603142002.jar
Id: org.eclipse.debug.core, Version: 3.10.100.v20160419-1720, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.debug.core_3.10.100.v20160419-1720.jar
Id: org.eclipse.debug.ui, Version: 3.11.202.v20161114-0338, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.debug.ui_3.11.202.v20161114-0338.jar
Id: org.eclipse.draw2d, Version: 3.10.100.201606061308, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.draw2d_3.10.100.201606061308.jar
Id: org.eclipse.dstore.core, Version: 3.4.0.201501311530, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.dstore.core_3.4.0.201501311530.jar
Id: org.eclipse.dstore.extra, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.dstore.extra_2.1.400.201403100950.jar
Id: org.eclipse.e4.core.commands, Version: 0.11.100.v20160506-0804, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.core.commands_0.11.100.v20160506-0804.jar
Id: org.eclipse.e4.core.contexts, Version: 1.5.1.v20170203-1100, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.core.contexts_1.5.1.v20170203-1100.jar
Id: org.eclipse.e4.core.di, Version: 1.6.1.v20160712-0927, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.core.di_1.6.1.v20160712-0927.jar
Id: org.eclipse.e4.core.di.annotations, Version: 1.5.0.v20151127-1241, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.core.di.annotations_1.5.0.v20151127-1241.jar
Id: org.eclipse.e4.core.di.extensions, Version: 0.14.0.v20160211-1614, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.core.di.extensions_0.14.0.v20160211-1614.jar
Id: org.eclipse.e4.core.services, Version: 2.0.100.v20160509-1032, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.core.services_2.0.100.v20160509-1032.jar
Id: org.eclipse.e4.emf.xpath, Version: 0.1.200.v20160506-0804, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.emf.xpath_0.1.200.v20160506-0804.jar
Id: org.eclipse.e4.ui.bindings, Version: 0.11.100.v20160509-1025, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.bindings_0.11.100.v20160509-1025.jar
Id: org.eclipse.e4.ui.css.core, Version: 0.12.1.v20161114-0210, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.css.core_0.12.1.v20161114-0210.jar
Id: org.eclipse.e4.ui.css.swt, Version: 0.12.100.v20160517-1505, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.css.swt_0.12.100.v20160517-1505.jar
Id: org.eclipse.e4.ui.css.swt.theme, Version: 0.10.100.v20160523-0836, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.css.swt.theme_0.10.100.v20160523-0836.jar
Id: org.eclipse.e4.ui.di, Version: 1.1.100.v20160506-0759, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.di_1.1.100.v20160506-0759.jar
Id: org.eclipse.e4.ui.dialogs, Version: 1.1.0.v20151127-1218, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.dialogs_1.1.0.v20151127-1218.jar
Id: org.eclipse.e4.ui.model.workbench, Version: 1.2.0.v20160229-1459, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.model.workbench_1.2.0.v20160229-1459.jar
Id: org.eclipse.e4.ui.services, Version: 1.2.100.v20160506-0759, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.services_1.2.100.v20160506-0759.jar
Id: org.eclipse.e4.ui.widgets, Version: 1.1.100.v20160506-0759, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.widgets_1.1.100.v20160506-0759.jar
Id: org.eclipse.e4.ui.workbench, Version: 1.4.0.v20160517-1624, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.workbench_1.4.0.v20160517-1624.jar
Id: org.eclipse.e4.ui.workbench.addons.swt, Version: 1.2.101.v20170206-1129, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.workbench.addons.swt_1.2.101.v20170206-1129.jar
Id: org.eclipse.e4.ui.workbench.renderers.swt, Version: 0.14.1.v20170117-1415, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.workbench.renderers.swt_0.14.1.v20170117-1415.jar
Id: org.eclipse.e4.ui.workbench.renderers.swt.cocoa, Version: 0.11.300.v20160330-1418, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.workbench.renderers.swt.cocoa_0.11.300.v20160330-1418.jar
Id: org.eclipse.e4.ui.workbench.swt, Version: 0.14.1.v20160829-0832, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.workbench.swt_0.14.1.v20160829-0832.jar
Id: org.eclipse.e4.ui.workbench3, Version: 0.13.100.v20160506-0759, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.e4.ui.workbench3_0.13.100.v20160506-0759.jar
Id: org.eclipse.ecf, Version: 3.8.0.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf_3.8.0.v20160823-2221.jar
Id: org.eclipse.ecf.filetransfer, Version: 5.0.0.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf.filetransfer_5.0.0.v20160823-2221.jar
Id: org.eclipse.ecf.identity, Version: 3.7.0.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf.identity_3.7.0.v20160823-2221.jar
Id: org.eclipse.ecf.provider.filetransfer, Version: 3.2.200.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf.provider.filetransfer_3.2.200.v20160823-2221.jar
Id: org.eclipse.ecf.provider.filetransfer.httpclient4, Version: 1.1.100.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf.provider.filetransfer.httpclient4_1.1.100.v20160823-2221.jar
Id: org.eclipse.ecf.provider.filetransfer.httpclient4.ssl, Version: 1.1.0.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf.provider.filetransfer.httpclient4.ssl_1.1.0.v20160823-2221.jar
Id: org.eclipse.ecf.provider.filetransfer.ssl, Version: 1.0.0.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf.provider.filetransfer.ssl_1.0.0.v20160823-2221.jar
Id: org.eclipse.ecf.ssl, Version: 1.2.0.v20160823-2221, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ecf.ssl_1.2.0.v20160823-2221.jar
Id: org.eclipse.egit, Version: 4.6.1.201703071140-r, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.egit_4.6.1.201703071140-r.jar
Id: org.eclipse.egit.core, Version: 4.6.1.201703071140-r, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.egit.core_4.6.1.201703071140-r.jar
Id: org.eclipse.egit.doc, Version: 4.6.1.201703071140-r, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.egit.doc_4.6.1.201703071140-r.jar
Id: org.eclipse.egit.mylyn.ui, Version: 4.6.1.201703071140-r, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.egit.mylyn.ui_4.6.1.201703071140-r.jar
Id: org.eclipse.egit.ui, Version: 4.6.1.201703071140-r, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.egit.ui_4.6.1.201703071140-r.jar
Id: org.eclipse.emf, Version: 2.6.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf_2.6.0.v20160526-0356.jar
Id: org.eclipse.emf.ant, Version: 2.8.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.ant_2.8.0.v20160526-0356.jar
Id: org.eclipse.emf.codegen, Version: 2.11.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.codegen_2.11.0.v20160526-0356.jar
Id: org.eclipse.emf.codegen.ecore, Version: 2.12.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.codegen.ecore_2.12.0.v20160526-0356.jar
Id: org.eclipse.emf.codegen.ecore.ui, Version: 2.12.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.codegen.ecore.ui_2.12.0.v20160526-0356.jar
Id: org.eclipse.emf.codegen.ui, Version: 2.6.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.codegen.ui_2.6.0.v20160526-0356.jar
Id: org.eclipse.emf.common, Version: 2.12.0.v20160420-0247, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.common_2.12.0.v20160420-0247.jar
Id: org.eclipse.emf.common.ui, Version: 2.11.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.common.ui_2.11.0.v20160526-0356.jar
Id: org.eclipse.emf.converter, Version: 2.7.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.converter_2.7.0.v20160526-0356.jar
Id: org.eclipse.emf.databinding, Version: 1.3.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.databinding_1.3.0.v20160526-0356.jar
Id: org.eclipse.emf.databinding.edit, Version: 1.3.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.databinding.edit_1.3.0.v20160526-0356.jar
Id: org.eclipse.emf.ecore, Version: 2.12.0.v20160420-0247, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.ecore_2.12.0.v20160420-0247.jar
Id: org.eclipse.emf.ecore.change, Version: 2.11.0.v20160420-0247, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.ecore.change_2.11.0.v20160420-0247.jar
Id: org.eclipse.emf.ecore.change.edit, Version: 2.6.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.ecore.change.edit_2.6.0.v20160526-0356.jar
Id: org.eclipse.emf.ecore.edit, Version: 2.9.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.ecore.edit_2.9.0.v20160526-0356.jar
Id: org.eclipse.emf.ecore.editor, Version: 2.12.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.ecore.editor_2.12.0.v20160526-0356.jar
Id: org.eclipse.emf.ecore.xmi, Version: 2.12.0.v20160420-0247, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.ecore.xmi_2.12.0.v20160420-0247.jar
Id: org.eclipse.emf.edit, Version: 2.12.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.edit_2.12.0.v20160526-0356.jar
Id: org.eclipse.emf.edit.ui, Version: 2.12.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.edit.ui_2.12.0.v20160526-0356.jar
Id: org.eclipse.emf.exporter, Version: 2.7.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.exporter_2.7.0.v20160526-0356.jar
Id: org.eclipse.emf.importer, Version: 2.9.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.importer_2.9.0.v20160526-0356.jar
Id: org.eclipse.emf.importer.ecore, Version: 2.8.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.importer.ecore_2.8.0.v20160526-0356.jar
Id: org.eclipse.emf.importer.java, Version: 2.7.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.importer.java_2.7.0.v20160526-0356.jar
Id: org.eclipse.emf.importer.rose, Version: 2.8.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.importer.rose_2.8.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping, Version: 2.9.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping_2.9.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping.ecore, Version: 2.6.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping.ecore_2.6.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping.ecore.editor, Version: 2.6.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping.ecore.editor_2.6.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping.ecore2ecore, Version: 2.9.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping.ecore2ecore_2.9.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping.ecore2ecore.editor, Version: 2.7.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping.ecore2ecore.editor_2.7.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping.ecore2xml, Version: 2.9.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping.ecore2xml_2.9.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping.ecore2xml.ui, Version: 2.8.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping.ecore2xml.ui_2.8.0.v20160526-0356.jar
Id: org.eclipse.emf.mapping.ui, Version: 2.7.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.emf.mapping.ui_2.7.0.v20160526-0356.jar
Id: org.eclipse.epp.logging.aeri.core, Version: 2.0.4.v20170307-1435, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.epp.logging.aeri.core_2.0.4.v20170307-1435.jar
Id: org.eclipse.epp.logging.aeri.ide, Version: 2.0.4.v20170307-1435, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.epp.logging.aeri.ide_2.0.4.v20170307-1435.jar
Id: org.eclipse.epp.mpc.core, Version: 1.5.4.v20170222-1921, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.epp.mpc.core_1.5.4.v20170222-1921.jar
Id: org.eclipse.epp.mpc.help.ui, Version: 1.5.4.v20170201-1845, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.epp.mpc.help.ui_1.5.4.v20170201-1845.jar
Id: org.eclipse.epp.mpc.ui, Version: 1.5.4.v20170222-1941, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.epp.mpc.ui_1.5.4.v20170222-1941.jar
Id: org.eclipse.epp.package.jee, Version: 4.6.3.20170314-1500, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.epp.package.jee_4.6.3.20170314-1500
Id: org.eclipse.equinox.app, Version: 1.3.400.v20150715-1528, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.app_1.3.400.v20150715-1528.jar
Id: org.eclipse.equinox.bidi, Version: 1.0.0.v20160307-1318, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.bidi_1.0.0.v20160307-1318.jar
Id: org.eclipse.equinox.common, Version: 3.8.0.v20160509-1230, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.common_3.8.0.v20160509-1230.jar
Id: org.eclipse.equinox.concurrent, Version: 1.1.0.v20130327-1442, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.concurrent_1.1.0.v20130327-1442.jar
Id: org.eclipse.equinox.console, Version: 1.1.200.v20150929-1405, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.console_1.1.200.v20150929-1405.jar
Id: org.eclipse.equinox.ds, Version: 1.4.400.v20160226-2036, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.ds_1.4.400.v20160226-2036.jar
Id: org.eclipse.equinox.event, Version: 1.3.200.v20160324-1850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.event_1.3.200.v20160324-1850.jar
Id: org.eclipse.equinox.frameworkadmin, Version: 2.0.300.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.frameworkadmin_2.0.300.v20160504-1450.jar
Id: org.eclipse.equinox.frameworkadmin.equinox, Version: 1.0.700.v20160102-2223, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.frameworkadmin.equinox_1.0.700.v20160102-2223.jar
Id: org.eclipse.equinox.http.jetty, Version: 3.3.0.v20160324-1850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.http.jetty_3.3.0.v20160324-1850.jar
Id: org.eclipse.equinox.http.registry, Version: 1.1.400.v20150715-1528, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.http.registry_1.1.400.v20150715-1528.jar
Id: org.eclipse.equinox.http.servlet, Version: 1.3.1.v20160808-1329, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.http.servlet_1.3.1.v20160808-1329.jar
Id: org.eclipse.equinox.jsp.jasper, Version: 1.0.500.v20150119-1358, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.jsp.jasper_1.0.500.v20150119-1358.jar
Id: org.eclipse.equinox.jsp.jasper.registry, Version: 1.0.300.v20130327-1442, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.jsp.jasper.registry_1.0.300.v20130327-1442.jar
Id: org.eclipse.equinox.launcher, Version: 1.3.201.v20161025-1711, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.launcher_1.3.201.v20161025-1711.jar
Id: org.eclipse.equinox.launcher.cocoa.macosx.x86_64, Version: 1.1.401.v20161122-1740, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.launcher.cocoa.macosx.x86_64_1.1.401.v20161122-1740
Id: org.eclipse.equinox.p2.artifact.repository, Version: 1.1.500.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.artifact.repository_1.1.500.v20160419-0834.jar
Id: org.eclipse.equinox.p2.console, Version: 1.0.500.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.console_1.0.500.v20160504-1450.jar
Id: org.eclipse.equinox.p2.core, Version: 2.4.100.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.core_2.4.100.v20160419-0834.jar
Id: org.eclipse.equinox.p2.director, Version: 2.3.300.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.director_2.3.300.v20160504-1450.jar
Id: org.eclipse.equinox.p2.director.app, Version: 1.0.500.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.director.app_1.0.500.v20160419-0834.jar
Id: org.eclipse.equinox.p2.directorywatcher, Version: 1.1.100.v20150423-1455, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.directorywatcher_1.1.100.v20150423-1455.jar
Id: org.eclipse.equinox.p2.discovery, Version: 1.0.400.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.discovery_1.0.400.v20160504-1450.jar
Id: org.eclipse.equinox.p2.discovery.compatibility, Version: 1.0.200.v20131211-1531, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.discovery.compatibility_1.0.200.v20131211-1531.jar
Id: org.eclipse.equinox.p2.engine, Version: 2.4.100.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.engine_2.4.100.v20160419-0834.jar
Id: org.eclipse.equinox.p2.extensionlocation, Version: 1.2.300.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.extensionlocation_1.2.300.v20160419-0834.jar
Id: org.eclipse.equinox.p2.garbagecollector, Version: 1.0.300.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.garbagecollector_1.0.300.v20160504-1450.jar
Id: org.eclipse.equinox.p2.jarprocessor, Version: 1.0.500.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.jarprocessor_1.0.500.v20160504-1450.jar
Id: org.eclipse.equinox.p2.metadata, Version: 2.3.100.v20160427-2220, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.metadata_2.3.100.v20160427-2220.jar
Id: org.eclipse.equinox.p2.metadata.repository, Version: 1.2.300.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.metadata.repository_1.2.300.v20160419-0834.jar
Id: org.eclipse.equinox.p2.operations, Version: 2.4.200.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.operations_2.4.200.v20160504-1450.jar
Id: org.eclipse.equinox.p2.publisher, Version: 1.4.100.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.publisher_1.4.100.v20160504-1450.jar
Id: org.eclipse.equinox.p2.publisher.eclipse, Version: 1.2.100.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.publisher.eclipse_1.2.100.v20160504-1450.jar
Id: org.eclipse.equinox.p2.reconciler.dropins, Version: 1.1.400.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.reconciler.dropins_1.1.400.v20160504-1450.jar
Id: org.eclipse.equinox.p2.repository, Version: 2.3.200.v20160421-0324, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.repository_2.3.200.v20160421-0324.jar
Id: org.eclipse.equinox.p2.repository.tools, Version: 2.1.300.v20160421-0324, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.repository.tools_2.1.300.v20160421-0324.jar
Id: org.eclipse.equinox.p2.touchpoint.eclipse, Version: 2.1.400.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.touchpoint.eclipse_2.1.400.v20160419-0834.jar
Id: org.eclipse.equinox.p2.touchpoint.natives, Version: 1.2.100.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.touchpoint.natives_1.2.100.v20160419-0834.jar
Id: org.eclipse.equinox.p2.transport.ecf, Version: 1.1.201.v20161115-1927, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.transport.ecf_1.1.201.v20161115-1927.jar
Id: org.eclipse.equinox.p2.ui, Version: 2.4.100.v20160419-0834, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.ui_2.4.100.v20160419-0834.jar
Id: org.eclipse.equinox.p2.ui.discovery, Version: 1.0.201.v20160901-1335, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.ui.discovery_1.0.201.v20160901-1335.jar
Id: org.eclipse.equinox.p2.ui.importexport, Version: 1.1.200.v20160521-1138, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.ui.importexport_1.1.200.v20160521-1138.jar
Id: org.eclipse.equinox.p2.ui.sdk, Version: 1.0.400.v20150423-1455, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.ui.sdk_1.0.400.v20150423-1455.jar
Id: org.eclipse.equinox.p2.ui.sdk.scheduler, Version: 1.3.0.v20161124-1529, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.ui.sdk.scheduler_1.3.0.v20161124-1529.jar
Id: org.eclipse.equinox.p2.updatechecker, Version: 1.1.300.v20161124-1529, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.updatechecker_1.1.300.v20161124-1529.jar
Id: org.eclipse.equinox.p2.updatesite, Version: 1.0.600.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.p2.updatesite_1.0.600.v20160504-1450.jar
Id: org.eclipse.equinox.preferences, Version: 3.6.1.v20160815-1406, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.preferences_3.6.1.v20160815-1406.jar
Id: org.eclipse.equinox.registry, Version: 3.6.100.v20160223-2218, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.registry_3.6.100.v20160223-2218.jar
Id: org.eclipse.equinox.security, Version: 1.2.200.v20150715-1528, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.security_1.2.200.v20150715-1528.jar
Id: org.eclipse.equinox.security.macosx, Version: 1.100.200.v20130327-1442, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.security.macosx_1.100.200.v20130327-1442.jar
Id: org.eclipse.equinox.security.ui, Version: 1.1.300.v20150803-1225, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.security.ui_1.1.300.v20150803-1225.jar
Id: org.eclipse.equinox.simpleconfigurator, Version: 1.1.200.v20160504-1450, Location: initial@reference:file:../../../../../.p2/pool/plugins/org.eclipse.equinox.simpleconfigurator_1.1.200.v20160504-1450.jar
Id: org.eclipse.equinox.simpleconfigurator.manipulator, Version: 2.0.200.v20160504-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.simpleconfigurator.manipulator_2.0.200.v20160504-1450.jar
Id: org.eclipse.equinox.util, Version: 1.0.500.v20130404-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.equinox.util_1.0.500.v20130404-1337.jar
Id: org.eclipse.gef, Version: 3.11.0.201606061308, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.gef_3.11.0.201606061308.jar
Id: org.eclipse.help, Version: 3.7.0.v20160602-1307, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.help_3.7.0.v20160602-1307.jar
Id: org.eclipse.help.base, Version: 4.1.2.v20170301-0400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.help.base_4.1.2.v20170301-0400.jar
Id: org.eclipse.help.ui, Version: 4.0.200.v20160510-0758, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.help.ui_4.0.200.v20160510-0758.jar
Id: org.eclipse.help.webapp, Version: 3.8.0.v20160504-0839, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.help.webapp_3.8.0.v20160504-0839.jar
Id: org.eclipse.jdt, Version: 3.12.3.v20170301-0400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt_3.12.3.v20170301-0400.jar
Id: org.eclipse.jdt.annotation, Version: 1.1.100.v20160418-1457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.annotation_1.1.100.v20160418-1457.jar
Id: org.eclipse.jdt.annotation, Version: 2.1.0.v20160418-1457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.annotation_2.1.0.v20160418-1457.jar
Id: org.eclipse.jdt.apt.core, Version: 3.4.100.v20160525-0952, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.apt.core_3.4.100.v20160525-0952.jar
Id: org.eclipse.jdt.apt.pluggable.core, Version: 1.1.100.v20160418-1457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.apt.pluggable.core_1.1.100.v20160418-1457.jar
Id: org.eclipse.jdt.apt.ui, Version: 3.4.100.v20160418-1457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.apt.ui_3.4.100.v20160418-1457.jar
Id: org.eclipse.jdt.compiler.apt, Version: 1.2.100.v20160418-1457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.compiler.apt_1.2.100.v20160418-1457.jar
Id: org.eclipse.jdt.compiler.tool, Version: 1.1.100.v20160418-1457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.compiler.tool_1.1.100.v20160418-1457.jar
Id: org.eclipse.jdt.core, Version: 3.12.3.v20170228-1205, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.core_3.12.3.v20170228-1205.jar
Id: org.eclipse.jdt.core.manipulation, Version: 1.7.0.v20160419-0705, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.core.manipulation_1.7.0.v20160419-0705.jar
Id: org.eclipse.jdt.debug, Version: 3.10.1.v20160811-0441, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.debug_3.10.1.v20160811-0441
Id: org.eclipse.jdt.debug.ui, Version: 3.7.201.v20160811-0450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.debug.ui_3.7.201.v20160811-0450.jar
Id: org.eclipse.jdt.doc.user, Version: 3.12.1.v20160727-2009, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.doc.user_3.12.1.v20160727-2009.jar
Id: org.eclipse.jdt.junit, Version: 3.9.0.v20160421-1701, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.junit_3.9.0.v20160421-1701.jar
Id: org.eclipse.jdt.junit.core, Version: 3.8.0.v20160421-1701, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.junit.core_3.8.0.v20160421-1701.jar
Id: org.eclipse.jdt.junit.runtime, Version: 3.4.600.v20160505-0715, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.junit.runtime_3.4.600.v20160505-0715.jar
Id: org.eclipse.jdt.junit4.runtime, Version: 1.1.600.v20160505-0715, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.junit4.runtime_1.1.600.v20160505-0715.jar
Id: org.eclipse.jdt.launching, Version: 3.8.101.v20161111-2014, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.launching_3.8.101.v20161111-2014.jar
Id: org.eclipse.jdt.launching.macosx, Version: 3.3.0.v20160418-1524, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.launching.macosx_3.3.0.v20160418-1524.jar
Id: org.eclipse.jdt.launching.ui.macosx, Version: 1.1.0.v20160418-1524, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.launching.ui.macosx_1.1.0.v20160418-1524.jar
Id: org.eclipse.jdt.ui, Version: 3.12.2.v20160929-0804, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jdt.ui_3.12.2.v20160929-0804.jar
Id: org.eclipse.jem, Version: 2.0.600.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jem_2.0.600.v201302011850.jar
Id: org.eclipse.jem.beaninfo, Version: 2.0.300.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jem.beaninfo_2.0.300.v201302011850.jar
Id: org.eclipse.jem.beaninfo.vm, Version: 2.0.300.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jem.beaninfo.vm_2.0.300.v201302011850.jar
Id: org.eclipse.jem.beaninfo.vm.common, Version: 2.0.300.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jem.beaninfo.vm.common_2.0.300.v201302011850.jar
Id: org.eclipse.jem.proxy, Version: 2.0.500.v201504161518, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jem.proxy_2.0.500.v201504161518.jar
Id: org.eclipse.jem.util, Version: 2.1.200.v201404021757, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jem.util_2.1.200.v201404021757.jar
Id: org.eclipse.jem.workbench, Version: 2.0.400.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jem.workbench_2.0.400.v201302011850.jar
Id: org.eclipse.jetty.continuation, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.continuation_9.3.9.v20160517.jar
Id: org.eclipse.jetty.http, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.http_9.3.9.v20160517.jar
Id: org.eclipse.jetty.io, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.io_9.3.9.v20160517.jar
Id: org.eclipse.jetty.security, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.security_9.3.9.v20160517.jar
Id: org.eclipse.jetty.server, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.server_9.3.9.v20160517.jar
Id: org.eclipse.jetty.servlet, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.servlet_9.3.9.v20160517.jar
Id: org.eclipse.jetty.util, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.util_9.3.9.v20160517.jar
Id: org.eclipse.jetty.webapp, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.webapp_9.3.9.v20160517.jar
Id: org.eclipse.jetty.xml, Version: 9.3.9.v20160517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jetty.xml_9.3.9.v20160517.jar
Id: org.eclipse.jface, Version: 3.12.2.v20170113-2113, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jface_3.12.2.v20170113-2113.jar
Id: org.eclipse.jface.databinding, Version: 1.8.1.v20161026-1531, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jface.databinding_1.8.1.v20161026-1531.jar
Id: org.eclipse.jface.text, Version: 3.11.2.v20170220-1911, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jface.text_3.11.2.v20170220-1911.jar
Id: org.eclipse.jgit, Version: 4.6.1.201703071140-r, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jgit_4.6.1.201703071140-r.jar
Id: org.eclipse.jgit.archive, Version: 4.6.1.201703071140-r, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jgit.archive_4.6.1.201703071140-r.jar
Id: org.eclipse.jpt.common.branding, Version: 1.4.0.v201309202144, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.common.branding_1.4.0.v201309202144.jar
Id: org.eclipse.jpt.common.core, Version: 1.5.0.v201603181811, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.common.core_1.5.0.v201603181811.jar
Id: org.eclipse.jpt.common.eclipselink.branding, Version: 1.3.100.v201309202144, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.common.eclipselink.branding_1.3.100.v201309202144.jar
Id: org.eclipse.jpt.common.eclipselink.core, Version: 1.3.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.common.eclipselink.core_1.3.200.v201603180253.jar
Id: org.eclipse.jpt.common.ui, Version: 1.4.100.v201607281951, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.common.ui_1.4.100.v201607281951.jar
Id: org.eclipse.jpt.common.utility, Version: 2.4.0.v201603181811, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.common.utility_2.4.0.v201603181811.jar
Id: org.eclipse.jpt.dbws.eclipselink.branding, Version: 1.2.100.v201309202144, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.dbws.eclipselink.branding_1.2.100.v201309202144.jar
Id: org.eclipse.jpt.dbws.eclipselink.core.gen, Version: 1.1.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.dbws.eclipselink.core.gen_1.1.200.v201603180253.jar
Id: org.eclipse.jpt.dbws.eclipselink.ui, Version: 1.1.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.dbws.eclipselink.ui_1.1.200.v201603180253.jar
Id: org.eclipse.jpt.doc.user, Version: 3.2.100.v201308231650, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.doc.user_3.2.100.v201308231650.jar
Id: org.eclipse.jpt.jaxb.branding, Version: 1.4.0.v201309202144, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.branding_1.4.0.v201309202144.jar
Id: org.eclipse.jpt.jaxb.core, Version: 1.4.100.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.core_1.4.100.v201603180253.jar
Id: org.eclipse.jpt.jaxb.core.schemagen, Version: 1.1.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.core.schemagen_1.1.200.v201603180253.jar
Id: org.eclipse.jpt.jaxb.eclipselink.branding, Version: 1.4.100.v201309202144, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.eclipselink.branding_1.4.100.v201309202144.jar
Id: org.eclipse.jpt.jaxb.eclipselink.core, Version: 1.3.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.eclipselink.core_1.3.200.v201603180253.jar
Id: org.eclipse.jpt.jaxb.eclipselink.core.schemagen, Version: 1.2.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.eclipselink.core.schemagen_1.2.200.v201603180253.jar
Id: org.eclipse.jpt.jaxb.eclipselink.ui, Version: 1.4.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.eclipselink.ui_1.4.200.v201603180253.jar
Id: org.eclipse.jpt.jaxb.ui, Version: 1.5.100.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jaxb.ui_1.5.100.v201603180253.jar
Id: org.eclipse.jpt.jpa.annotate, Version: 1.0.100.v201309261652, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.annotate_1.0.100.v201309261652.jar
Id: org.eclipse.jpt.jpa.branding, Version: 3.4.0.v201309202144, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.branding_3.4.0.v201309202144.jar
Id: org.eclipse.jpt.jpa.core, Version: 3.5.0.v201603181811, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.core_3.5.0.v201603181811.jar
Id: org.eclipse.jpt.jpa.db, Version: 2.2.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.db_2.2.200.v201603180253.jar
Id: org.eclipse.jpt.jpa.db.ui, Version: 2.1.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.db.ui_2.1.200.v201603180253.jar
Id: org.eclipse.jpt.jpa.eclipselink.branding, Version: 3.4.0.v201309202144, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.eclipselink.branding_3.4.0.v201309202144.jar
Id: org.eclipse.jpt.jpa.eclipselink.core, Version: 2.4.100.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.eclipselink.core_2.4.100.v201603180253.jar
Id: org.eclipse.jpt.jpa.eclipselink.core.ddlgen, Version: 2.2.200.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.eclipselink.core.ddlgen_2.2.200.v201603180253.jar
Id: org.eclipse.jpt.jpa.eclipselink.ui, Version: 2.4.100.v201603180253, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.eclipselink.ui_2.4.100.v201603180253.jar
Id: org.eclipse.jpt.jpa.gen, Version: 2.3.200.v201512212242, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.gen_2.3.200.v201512212242.jar
Id: org.eclipse.jpt.jpa.ui, Version: 3.4.100.v201607131827, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jpt.jpa.ui_3.4.100.v201607131827.jar
Id: org.eclipse.jsch.core, Version: 1.3.0.v20160422-1917, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jsch.core_1.3.0.v20160422-1917.jar
Id: org.eclipse.jsch.ui, Version: 1.3.0.v20160323-1650, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jsch.ui_1.3.0.v20160323-1650.jar
Id: org.eclipse.jsf.branding, Version: 3.5.0.v201309172308, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jsf.branding_3.5.0.v201309172308.jar
Id: org.eclipse.json, Version: 1.0.1.v201612232230, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.json_1.0.1.v201612232230.jar
Id: org.eclipse.jst.common.annotations.controller, Version: 1.1.300.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.common.annotations.controller_1.1.300.v201302011850.jar
Id: org.eclipse.jst.common.annotations.core, Version: 1.1.300.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.common.annotations.core_1.1.300.v201302011850.jar
Id: org.eclipse.jst.common.annotations.ui, Version: 1.1.300.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.common.annotations.ui_1.1.300.v201302011850.jar
Id: org.eclipse.jst.common.frameworks, Version: 1.1.701.v201509021802, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.common.frameworks_1.1.701.v201509021802.jar
Id: org.eclipse.jst.common.project.facet.core, Version: 1.4.500.v201508121553, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.common.project.facet.core_1.4.500.v201508121553.jar
Id: org.eclipse.jst.common.project.facet.ui, Version: 1.4.510.v201501141810, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.common.project.facet.ui_1.4.510.v201501141810.jar
Id: org.eclipse.jst.common.ui, Version: 1.0.300.v201603172133, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.common.ui_1.0.300.v201603172133.jar
Id: org.eclipse.jst.ejb.doc.user, Version: 1.1.301.v201105130955, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ejb.doc.user_1.1.301.v201105130955.jar
Id: org.eclipse.jst.ejb.ui, Version: 1.1.910.v201701262130, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ejb.ui_1.1.910.v201701262130.jar
Id: org.eclipse.jst.ejb.ui.infopop, Version: 1.0.300.v201002231012, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ejb.ui.infopop_1.0.300.v201002231012.jar
Id: org.eclipse.jst.j2ee, Version: 1.1.901.v201701192236, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee_1.1.901.v201701192236.jar
Id: org.eclipse.jst.j2ee.core, Version: 1.3.200.v201505041449, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.core_1.3.200.v201505041449.jar
Id: org.eclipse.jst.j2ee.doc.user, Version: 1.1.400.v201008122207, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.doc.user_1.1.400.v201008122207.jar
Id: org.eclipse.jst.j2ee.ejb, Version: 1.1.900.v201701262105, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.ejb_1.1.900.v201701262105.jar
Id: org.eclipse.jst.j2ee.ejb.annotation.model, Version: 1.1.400.v201701262105, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.ejb.annotation.model_1.1.400.v201701262105.jar
Id: org.eclipse.jst.j2ee.ejb.annotations.emitter, Version: 1.1.300.v201701262105, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.ejb.annotations.emitter_1.1.300.v201701262105.jar
Id: org.eclipse.jst.j2ee.ejb.annotations.ui, Version: 1.1.300.v201701262105, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.ejb.annotations.ui_1.1.300.v201701262105.jar
Id: org.eclipse.jst.j2ee.ejb.annotations.xdoclet, Version: 1.2.300.v201701262105, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.ejb.annotations.xdoclet_1.2.300.v201701262105.jar
Id: org.eclipse.jst.j2ee.infopop, Version: 1.0.300.v201309091923, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.infopop_1.0.300.v201309091923.jar
Id: org.eclipse.jst.j2ee.jca, Version: 1.1.800.v201602161345, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.jca_1.1.800.v201602161345.jar
Id: org.eclipse.jst.j2ee.jca.ui, Version: 1.1.500.v201304231803, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.jca.ui_1.1.500.v201304231803.jar
Id: org.eclipse.jst.j2ee.navigator.ui, Version: 1.1.600.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.navigator.ui_1.1.600.v201302011850.jar
Id: org.eclipse.jst.j2ee.ui, Version: 1.1.900.v201602161345, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.ui_1.1.900.v201602161345.jar
Id: org.eclipse.jst.j2ee.web, Version: 1.1.851.v201608191717, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.web_1.1.851.v201608191717.jar
Id: org.eclipse.jst.j2ee.webservice, Version: 1.1.400.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.webservice_1.1.400.v201302011850.jar
Id: org.eclipse.jst.j2ee.webservice.ui, Version: 1.1.500.v201302011850, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.webservice.ui_1.1.500.v201302011850.jar
Id: org.eclipse.jst.j2ee.xdoclet.runtime, Version: 1.1.300.v201004280609, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.j2ee.xdoclet.runtime_1.1.300.v201004280609.jar
Id: org.eclipse.jst.jee, Version: 1.0.700.v201404092004, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jee_1.0.700.v201404092004.jar
Id: org.eclipse.jst.jee.ejb, Version: 1.0.500.v201701262105, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jee.ejb_1.0.500.v201701262105.jar
Id: org.eclipse.jst.jee.ui, Version: 1.0.701.v201408251535, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jee.ui_1.0.701.v201408251535.jar
Id: org.eclipse.jst.jee.web, Version: 1.0.500.v201404021628, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jee.web_1.0.500.v201404021628.jar
Id: org.eclipse.jst.jsf.apache.trinidad.tagsupport, Version: 1.4.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.apache.trinidad.tagsupport_1.4.0.v201309172102.jar
Id: org.eclipse.jst.jsf.common, Version: 1.5.101.v201504022146, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.common_1.5.101.v201504022146.jar
Id: org.eclipse.jst.jsf.common.runtime, Version: 1.4.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.common.runtime_1.4.0.v201309172102.jar
Id: org.eclipse.jst.jsf.common.ui, Version: 1.5.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.common.ui_1.5.0.v201309172102.jar
Id: org.eclipse.jst.jsf.core, Version: 1.7.111.v201603050214, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.core_1.7.111.v201603050214.jar
Id: org.eclipse.jst.jsf.doc.user, Version: 1.5.0.v201309172352, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.doc.user_1.5.0.v201309172352.jar
Id: org.eclipse.jst.jsf.facelet.core, Version: 1.3.110.v201603071844, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.facelet.core_1.3.110.v201603071844.jar
Id: org.eclipse.jst.jsf.facelet.ui, Version: 1.3.110.v201603071844, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.facelet.ui_1.3.110.v201603071844.jar
Id: org.eclipse.jst.jsf.facesconfig, Version: 1.5.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.facesconfig_1.5.0.v201309172102.jar
Id: org.eclipse.jst.jsf.facesconfig.ui, Version: 1.5.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.facesconfig.ui_1.5.0.v201309172102.jar
Id: org.eclipse.jst.jsf.standard.tagsupport, Version: 1.5.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.standard.tagsupport_1.5.0.v201309172102.jar
Id: org.eclipse.jst.jsf.ui, Version: 1.6.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsf.ui_1.6.0.v201309172102.jar
Id: org.eclipse.jst.jsp.core, Version: 1.2.901.v201608060346, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsp.core_1.2.901.v201608060346.jar
Id: org.eclipse.jst.jsp.ui, Version: 1.1.1100.v201605092203, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsp.ui_1.1.1100.v201605092203.jar
Id: org.eclipse.jst.jsp.ui.infopop, Version: 1.0.200.v201309112106, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.jsp.ui.infopop_1.0.200.v201309112106.jar
Id: org.eclipse.jst.pagedesigner, Version: 1.7.110.v201603071844, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.pagedesigner_1.7.110.v201603071844.jar
Id: org.eclipse.jst.pagedesigner.jsf.ui, Version: 1.5.0.v201309172102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.pagedesigner.jsf.ui_1.5.0.v201309172102.jar
Id: org.eclipse.jst.pagedesigner.jsp.core, Version: 1.5.100.v201603071844, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.pagedesigner.jsp.core_1.5.100.v201603071844.jar
Id: org.eclipse.jst.server.core, Version: 1.2.500.v201603031514, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.core_1.2.500.v201603031514.jar
Id: org.eclipse.jst.server.generic.core, Version: 1.0.900.v201606081655, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.generic.core_1.0.900.v201606081655.jar
Id: org.eclipse.jst.server.generic.jonas, Version: 1.5.500.v201405151744, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.generic.jonas_1.5.500.v201405151744.jar
Id: org.eclipse.jst.server.generic.ui, Version: 1.0.600.v201402262303, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.generic.ui_1.0.600.v201402262303.jar
Id: org.eclipse.jst.server.preview.adapter, Version: 1.1.300.v201606081655, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.preview.adapter_1.1.300.v201606081655.jar
Id: org.eclipse.jst.server.tomcat.core, Version: 1.1.801.v201609071751, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.tomcat.core_1.1.801.v201609071751.jar
Id: org.eclipse.jst.server.tomcat.ui, Version: 1.1.501.v201609071751, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.tomcat.ui_1.1.501.v201609071751.jar
Id: org.eclipse.jst.server.ui, Version: 1.1.300.v201309182039, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.ui_1.1.300.v201309182039.jar
Id: org.eclipse.jst.server.ui.doc.user, Version: 1.0.600.v201309182117, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.ui.doc.user_1.0.600.v201309182117.jar
Id: org.eclipse.jst.server.ui.infopop, Version: 1.0.500.v201309182117, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.server.ui.infopop_1.0.500.v201309182117.jar
Id: org.eclipse.jst.servlet.ui, Version: 1.1.900.v201605251556, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.servlet.ui_1.1.900.v201605251556.jar
Id: org.eclipse.jst.servlet.ui.infopop, Version: 1.0.500.v201105121947, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.servlet.ui.infopop_1.0.500.v201105121947.jar
Id: org.eclipse.jst.standard.schemas, Version: 1.2.201.v201501151629, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.standard.schemas_1.2.201.v201501151629.jar
Id: org.eclipse.jst.ws, Version: 1.0.800.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws_1.0.800.v201701262139.jar
Id: org.eclipse.jst.ws.annotations.core, Version: 1.2.200.v201311102023, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.annotations.core_1.2.200.v201311102023.jar
Id: org.eclipse.jst.ws.axis.consumption.core, Version: 1.0.550.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis.consumption.core_1.0.550.v201505131719.jar
Id: org.eclipse.jst.ws.axis.consumption.ui, Version: 1.0.900.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis.consumption.ui_1.0.900.v201701262139.jar
Id: org.eclipse.jst.ws.axis.creation.ui, Version: 1.0.900.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis.creation.ui_1.0.900.v201701262139.jar
Id: org.eclipse.jst.ws.axis.infopop, Version: 1.0.400.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis.infopop_1.0.400.v201309242123.jar
Id: org.eclipse.jst.ws.axis.ui.doc.user, Version: 1.1.200.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis.ui.doc.user_1.1.200.v201309242123.jar
Id: org.eclipse.jst.ws.axis2.consumption.core, Version: 1.0.200.v201309242118, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis2.consumption.core_1.0.200.v201309242118.jar
Id: org.eclipse.jst.ws.axis2.consumption.ui, Version: 1.0.200.v201309242118, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis2.consumption.ui_1.0.200.v201309242118.jar
Id: org.eclipse.jst.ws.axis2.core, Version: 1.0.300.v201309242118, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis2.core_1.0.300.v201309242118.jar
Id: org.eclipse.jst.ws.axis2.creation.core, Version: 1.0.200.v201309242118, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis2.creation.core_1.0.200.v201309242118.jar
Id: org.eclipse.jst.ws.axis2.creation.ui, Version: 1.0.200.v201309242118, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis2.creation.ui_1.0.200.v201309242118.jar
Id: org.eclipse.jst.ws.axis2.ui, Version: 1.0.400.v201309242118, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis2.ui_1.0.400.v201309242118.jar
Id: org.eclipse.jst.ws.axis2.ui.doc.user, Version: 1.0.200.v201309242118, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.axis2.ui.doc.user_1.0.200.v201309242118.jar
Id: org.eclipse.jst.ws.consumption, Version: 1.0.950.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.consumption_1.0.950.v201701262139.jar
Id: org.eclipse.jst.ws.consumption.infopop, Version: 1.0.400.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.consumption.infopop_1.0.400.v201309242123.jar
Id: org.eclipse.jst.ws.consumption.ui, Version: 1.1.850.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.consumption.ui_1.1.850.v201701262139.jar
Id: org.eclipse.jst.ws.consumption.ui.doc.user, Version: 1.0.700.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.consumption.ui.doc.user_1.0.700.v201309242123.jar
Id: org.eclipse.jst.ws.creation.ejb.ui, Version: 1.0.250.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.creation.ejb.ui_1.0.250.v201309242123.jar
Id: org.eclipse.jst.ws.creation.ui, Version: 1.0.950.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.creation.ui_1.0.950.v201701262139.jar
Id: org.eclipse.jst.ws.cxf.consumption.core, Version: 1.0.400.v201701262158, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.cxf.consumption.core_1.0.400.v201701262158.jar
Id: org.eclipse.jst.ws.cxf.consumption.ui, Version: 1.0.400.v201701262158, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.cxf.consumption.ui_1.0.400.v201701262158.jar
Id: org.eclipse.jst.ws.cxf.core, Version: 1.1.300.v201701262158, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.cxf.core_1.1.300.v201701262158.jar
Id: org.eclipse.jst.ws.cxf.creation.core, Version: 1.0.500.v201701262158, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.cxf.creation.core_1.0.500.v201701262158.jar
Id: org.eclipse.jst.ws.cxf.creation.ui, Version: 1.0.300.v201403242125, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.cxf.creation.ui_1.0.300.v201403242125.jar
Id: org.eclipse.jst.ws.cxf.doc.user, Version: 1.0.300.v201309232209, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.cxf.doc.user_1.0.300.v201309232209.jar
Id: org.eclipse.jst.ws.cxf.ui, Version: 1.0.300.v201309232152, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.cxf.ui_1.0.300.v201309232152.jar
Id: org.eclipse.jst.ws.doc.user, Version: 1.0.700.v201612121628, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.doc.user_1.0.700.v201612121628.jar
Id: org.eclipse.jst.ws.infopop, Version: 1.0.400.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.infopop_1.0.400.v201309242123.jar
Id: org.eclipse.jst.ws.jaxb.core, Version: 1.0.200.v201309232152, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxb.core_1.0.200.v201309232152.jar
Id: org.eclipse.jst.ws.jaxrs.core, Version: 1.0.700.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxrs.core_1.0.700.v201701262139.jar
Id: org.eclipse.jst.ws.jaxrs.ui, Version: 1.0.700.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxrs.ui_1.0.700.v201505131719.jar
Id: org.eclipse.jst.ws.jaxws.core, Version: 1.0.500.v201701262158, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxws.core_1.0.500.v201701262158.jar
Id: org.eclipse.jst.ws.jaxws.doc.user, Version: 1.0.400.v201309232209, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxws.doc.user_1.0.400.v201309232209.jar
Id: org.eclipse.jst.ws.jaxws.dom.integration, Version: 1.0.300.v201308151836, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxws.dom.integration_1.0.300.v201308151836.jar
Id: org.eclipse.jst.ws.jaxws.dom.runtime, Version: 1.0.300.v201308151836, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxws.dom.runtime_1.0.300.v201308151836.jar
Id: org.eclipse.jst.ws.jaxws.dom.ui, Version: 1.0.100.v201308151836, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxws.dom.ui_1.0.100.v201308151836.jar
Id: org.eclipse.jst.ws.jaxws.ui, Version: 1.0.401.v201504291921, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxws.ui_1.0.401.v201504291921.jar
Id: org.eclipse.jst.ws.jaxws.utils, Version: 1.0.301.v201504272154, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.jaxws.utils_1.0.301.v201504272154.jar
Id: org.eclipse.jst.ws.uddiregistry, Version: 1.0.600.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.uddiregistry_1.0.600.v201505131719.jar
Id: org.eclipse.jst.ws.ui, Version: 1.0.600.v201701262139, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.jst.ws.ui_1.0.600.v201701262139.jar
Id: org.eclipse.ltk.core.refactoring, Version: 3.7.0.v20160419-0705, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ltk.core.refactoring_3.7.0.v20160419-0705.jar
Id: org.eclipse.ltk.ui.refactoring, Version: 3.8.0.v20160518-1817, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ltk.ui.refactoring_3.8.0.v20160518-1817.jar
Id: org.eclipse.m2e.archetype.common, Version: 1.7.0.20160603-1931, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.archetype.common_1.7.0.20160603-1931
Id: org.eclipse.m2e.core, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.core_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.core.ui, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.core.ui_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.discovery, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.discovery_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.editor, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.editor_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.editor.xml, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.editor.xml_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.importer, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.importer_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.jdt, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.jdt_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.jdt.ui, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.jdt.ui_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.launching, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.launching_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.lifecyclemapping.defaults, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.lifecyclemapping.defaults_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.logback.appender, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.logback.appender_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.logback.configuration, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.logback.configuration_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.maven.indexer, Version: 1.7.0.20160603-1931, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.maven.indexer_1.7.0.20160603-1931
Id: org.eclipse.m2e.maven.runtime, Version: 1.7.0.20160603-1931, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.maven.runtime_1.7.0.20160603-1931
Id: org.eclipse.m2e.maven.runtime.slf4j.simple, Version: 1.7.0.20160603-1931, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.maven.runtime.slf4j.simple_1.7.0.20160603-1931
Id: org.eclipse.m2e.model.edit, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.model.edit_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.profiles.core, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.profiles.core_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.profiles.ui, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.profiles.ui_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.refactoring, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.refactoring_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.scm, Version: 1.7.0.20160603-1933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.scm_1.7.0.20160603-1933.jar
Id: org.eclipse.m2e.workspace.cli, Version: 0.3.1, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.workspace.cli_0.3.1.jar
Id: org.eclipse.m2e.wtp, Version: 1.3.1.20160831-1005, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.wtp_1.3.1.20160831-1005.jar
Id: org.eclipse.m2e.wtp.jaxrs, Version: 1.3.1.20160831-1005, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.wtp.jaxrs_1.3.1.20160831-1005.jar
Id: org.eclipse.m2e.wtp.jpa, Version: 1.3.1.20160831-1005, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.wtp.jpa_1.3.1.20160831-1005.jar
Id: org.eclipse.m2e.wtp.jsf, Version: 1.3.1.20160831-1005, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.wtp.jsf_1.3.1.20160831-1005.jar
Id: org.eclipse.m2e.wtp.overlay, Version: 1.3.1.20160831-1005, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.wtp.overlay_1.3.1.20160831-1005.jar
Id: org.eclipse.m2e.wtp.overlay.ui, Version: 1.3.1.20160831-1005, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.m2e.wtp.overlay.ui_1.3.1.20160831-1005.jar
Id: org.eclipse.mylyn.bugzilla.core, Version: 3.21.0.v20160909-1813, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.bugzilla.core_3.21.0.v20160909-1813.jar
Id: org.eclipse.mylyn.bugzilla.ide, Version: 3.21.0.v20160912-1820, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.bugzilla.ide_3.21.0.v20160912-1820.jar
Id: org.eclipse.mylyn.bugzilla.ui, Version: 3.21.0.v20160909-1813, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.bugzilla.ui_3.21.0.v20160909-1813.jar
Id: org.eclipse.mylyn.commons.core, Version: 3.21.0.v20160707-1856, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.core_3.21.0.v20160707-1856.jar
Id: org.eclipse.mylyn.commons.identity.core, Version: 1.13.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.identity.core_1.13.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.net, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.net_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.notifications.core, Version: 1.13.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.notifications.core_1.13.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.notifications.feed, Version: 1.13.0.v20160721-2347, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.notifications.feed_1.13.0.v20160721-2347.jar
Id: org.eclipse.mylyn.commons.notifications.ui, Version: 1.13.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.notifications.ui_1.13.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.repositories.core, Version: 1.13.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.repositories.core_1.13.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.repositories.ui, Version: 1.13.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.repositories.ui_1.13.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.screenshots, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.screenshots_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.ui, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.ui_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.workbench, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.workbench_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.commons.xmlrpc, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.commons.xmlrpc_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.context.core, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.context.core_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.context.tasks.ui, Version: 3.21.0.v20160815-2336, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.context.tasks.ui_3.21.0.v20160815-2336.jar
Id: org.eclipse.mylyn.context.ui, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.context.ui_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.debug.ui, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.debug.ui_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.discovery.core, Version: 3.21.0.v20160729-1739, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.discovery.core_3.21.0.v20160729-1739.jar
Id: org.eclipse.mylyn.discovery.ui, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.discovery.ui_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.help.ui, Version: 3.21.0.v20160913-2013, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.help.ui_3.21.0.v20160913-2013.jar
Id: org.eclipse.mylyn.ide.ant, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.ide.ant_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.ide.ui, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.ide.ui_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.java.tasks, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.java.tasks_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.java.ui, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.java.ui_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.monitor.core, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.monitor.core_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.monitor.ui, Version: 3.21.0.v20160630-1702, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.monitor.ui_3.21.0.v20160630-1702.jar
Id: org.eclipse.mylyn.resources.ui, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.resources.ui_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.tasks.bugs, Version: 3.21.0.v20160929-1805, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.tasks.bugs_3.21.0.v20160929-1805.jar
Id: org.eclipse.mylyn.tasks.core, Version: 3.21.0.v20160914-0252, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.tasks.core_3.21.0.v20160914-0252.jar
Id: org.eclipse.mylyn.tasks.index.core, Version: 3.21.0.v20160630-2019, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.tasks.index.core_3.21.0.v20160630-2019.jar
Id: org.eclipse.mylyn.tasks.index.ui, Version: 3.21.0.v20160630-2019, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.tasks.index.ui_3.21.0.v20160630-2019.jar
Id: org.eclipse.mylyn.tasks.search, Version: 3.21.0.v20160630-2019, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.tasks.search_3.21.0.v20160630-2019.jar
Id: org.eclipse.mylyn.tasks.ui, Version: 3.21.0.v20160913-2131, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.tasks.ui_3.21.0.v20160913-2131.jar
Id: org.eclipse.mylyn.team.ui, Version: 3.21.0.v20160701-1337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.team.ui_3.21.0.v20160701-1337.jar
Id: org.eclipse.mylyn.wikitext.asciidoc.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.asciidoc.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.asciidoc.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.asciidoc.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.confluence.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.confluence.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.confluence.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.confluence.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.context.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.context.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.core.ant, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.core.ant_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.core.osgi, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.core.osgi_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.help.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.help.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.html.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.html.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.markdown.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.markdown.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.markdown.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.markdown.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.mediawiki.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.mediawiki.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.mediawiki.core.ant, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.mediawiki.core.ant_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.mediawiki.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.mediawiki.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.tasks.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.tasks.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.textile.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.textile.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.textile.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.textile.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.tracwiki.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.tracwiki.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.tracwiki.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.tracwiki.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.twiki.core, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.twiki.core_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.twiki.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.twiki.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.mylyn.wikitext.ui, Version: 2.10.1.v20161129-1925, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.mylyn.wikitext.ui_2.10.1.v20161129-1925.jar
Id: org.eclipse.nebula.widgets.tablecombo, Version: 1.0.0.201702281340, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.nebula.widgets.tablecombo_1.0.0.201702281340.jar
Id: org.eclipse.oomph.base, Version: 1.7.0.v20170201-1645, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.base_1.7.0.v20170201-1645.jar
Id: org.eclipse.oomph.base.edit, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.base.edit_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.extractor.lib, Version: 1.3.0.v20161116-0647, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.extractor.lib_1.3.0.v20161116-0647.jar
Id: org.eclipse.oomph.jreinfo, Version: 1.7.0.v20170201-1645, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.jreinfo_1.7.0.v20170201-1645.jar
Id: org.eclipse.oomph.jreinfo.ui, Version: 1.7.0.v20161220-1444, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.jreinfo.ui_1.7.0.v20161220-1444.jar
Id: org.eclipse.oomph.p2, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.p2_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.p2.core, Version: 1.7.0.v20170228-1751, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.p2.core_1.7.0.v20170228-1751.jar
Id: org.eclipse.oomph.p2.doc, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.p2.doc_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.p2.edit, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.p2.edit_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.p2.ui, Version: 1.7.0.v20161231-0937, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.p2.ui_1.7.0.v20161231-0937.jar
Id: org.eclipse.oomph.predicates, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.predicates_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.predicates.edit, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.predicates.edit_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.preferences, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.preferences_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.resources, Version: 1.7.0.v20170217-1028, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.resources_1.7.0.v20170217-1028.jar
Id: org.eclipse.oomph.resources.edit, Version: 1.7.0.v20170103-0924, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.resources.edit_1.7.0.v20170103-0924.jar
Id: org.eclipse.oomph.setup, Version: 1.7.0.v20170224-1311, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup_1.7.0.v20170224-1311.jar
Id: org.eclipse.oomph.setup.core, Version: 1.7.0.v20170301-0747, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.core_1.7.0.v20170301-0747.jar
Id: org.eclipse.oomph.setup.doc, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.doc_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.setup.edit, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.edit_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.setup.editor, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.editor_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.setup.p2, Version: 1.7.0.v20170217-1051, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.p2_1.7.0.v20170217-1051.jar
Id: org.eclipse.oomph.setup.p2.edit, Version: 1.7.0.v20161230-1057, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.p2.edit_1.7.0.v20161230-1057.jar
Id: org.eclipse.oomph.setup.sync, Version: 1.7.0.v20170201-1631, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.sync_1.7.0.v20170201-1631.jar
Id: org.eclipse.oomph.setup.ui, Version: 1.7.0.v20170305-1123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.ui_1.7.0.v20170305-1123.jar
Id: org.eclipse.oomph.setup.ui.questionnaire, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.setup.ui.questionnaire_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.ui, Version: 1.7.0.v20170222-1350, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.ui_1.7.0.v20170222-1350.jar
Id: org.eclipse.oomph.util, Version: 1.7.0.v20170303-0927, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.util_1.7.0.v20170303-0927.jar
Id: org.eclipse.oomph.workingsets, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.workingsets_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.workingsets.edit, Version: 1.7.0.v20170104-1401, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.workingsets.edit_1.7.0.v20170104-1401.jar
Id: org.eclipse.oomph.workingsets.editor, Version: 1.7.0.v20161230-1057, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.oomph.workingsets.editor_1.7.0.v20161230-1057.jar
Id: org.eclipse.osgi, Version: 3.11.3.v20170209-1843, Location: System Bundle
Id: org.eclipse.osgi.compatibility.state, Version: 1.0.200.v20160504-1419, Location: initial@reference:file:../../../../../.p2/pool/plugins/org.eclipse.osgi.compatibility.state_1.0.200.v20160504-1419.jar
Id: org.eclipse.osgi.services, Version: 3.5.100.v20160504-1419, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.osgi.services_3.5.100.v20160504-1419.jar
Id: org.eclipse.osgi.util, Version: 3.3.100.v20150423-1351, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.osgi.util_3.3.100.v20150423-1351.jar
Id: org.eclipse.pde, Version: 3.12.3.v20170301-0400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde_3.12.3.v20170301-0400.jar
Id: org.eclipse.pde.api.tools, Version: 1.1.2.v20161115-0549, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.api.tools_1.1.2.v20161115-0549.jar
Id: org.eclipse.pde.api.tools.annotations, Version: 1.0.100.v20160418-1724, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.api.tools.annotations_1.0.100.v20160418-1724.jar
Id: org.eclipse.pde.api.tools.ui, Version: 1.1.0.v20160519-0701, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.api.tools.ui_1.1.0.v20160519-0701.jar
Id: org.eclipse.pde.build, Version: 3.9.200.v20160204-0642, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.build_3.9.200.v20160204-0642
Id: org.eclipse.pde.core, Version: 3.11.1.v20161115-1951, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.core_3.11.1.v20161115-1951.jar
Id: org.eclipse.pde.doc.user, Version: 3.12.2.v20170221-1001, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.doc.user_3.12.2.v20170221-1001.jar
Id: org.eclipse.pde.ds.annotations, Version: 1.0.0.v20160525-1437, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.ds.annotations_1.0.0.v20160525-1437.jar
Id: org.eclipse.pde.ds.core, Version: 1.1.0.v20151201-1325, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.ds.core_1.1.0.v20151201-1325.jar
Id: org.eclipse.pde.ds.ui, Version: 1.1.0.v20160518-1843, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.ds.ui_1.1.0.v20160518-1843.jar
Id: org.eclipse.pde.junit.runtime, Version: 3.5.0.v20151013-0625, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.junit.runtime_3.5.0.v20151013-0625.jar
Id: org.eclipse.pde.launching, Version: 3.6.401.v20161115-0549, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.launching_3.6.401.v20161115-0549.jar
Id: org.eclipse.pde.runtime, Version: 3.5.0.v20160418-1724, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.runtime_3.5.0.v20160418-1724.jar
Id: org.eclipse.pde.ua.core, Version: 1.0.500.v20160204-0642, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.ua.core_1.0.500.v20160204-0642.jar
Id: org.eclipse.pde.ua.ui, Version: 1.1.0.v20160518-1843, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.ua.ui_1.1.0.v20160518-1843.jar
Id: org.eclipse.pde.ui, Version: 3.9.100.v20161102-0517, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.ui_3.9.100.v20161102-0517.jar
Id: org.eclipse.pde.ui.templates, Version: 3.6.0.v20160424-1948, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.pde.ui.templates_3.6.0.v20160424-1948.jar
Id: org.eclipse.persistence.antlr, Version: 3.2.0.v201302191141, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.antlr_3.2.0.v201302191141.jar
Id: org.eclipse.persistence.asm, Version: 5.0.1.v201405080102, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.asm_5.0.1.v201405080102.jar
Id: org.eclipse.persistence.core, Version: 2.6.0.v20140809-296a69f, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.core_2.6.0.v20140809-296a69f.jar
Id: org.eclipse.persistence.dbws, Version: 2.6.0.v20140809-296a69f, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.dbws_2.6.0.v20140809-296a69f.jar
Id: org.eclipse.persistence.dbws.builder, Version: 2.6.0.v20140809-296a69f, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.dbws.builder_2.6.0.v20140809-296a69f.jar
Id: org.eclipse.persistence.jpa, Version: 2.6.0.v20140809-296a69f, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.jpa_2.6.0.v20140809-296a69f.jar
Id: org.eclipse.persistence.jpa.jpql, Version: 2.6.0.v20140809-296a69f, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.jpa.jpql_2.6.0.v20140809-296a69f.jar
Id: org.eclipse.persistence.moxy, Version: 2.6.0.v20130815-a4708b6, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.persistence.moxy_2.6.0.v20130815-a4708b6.jar
Id: org.eclipse.platform, Version: 4.6.3.v20170301-0400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.platform_4.6.3.v20170301-0400
Id: org.eclipse.platform.doc.user, Version: 4.6.1.v20160727-2009, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.platform.doc.user_4.6.1.v20160727-2009.jar
Id: org.eclipse.rcp, Version: 4.6.3.v20170301-0400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rcp_4.6.3.v20170301-0400.jar
Id: org.eclipse.recommenders.apidocs, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.apidocs_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.apidocs.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.apidocs.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.calls, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.calls_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.calls.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.calls.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.chain.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.chain.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.completion.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.completion.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.constructors, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.constructors_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.constructors.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.constructors.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.coordinates, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.coordinates_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.coordinates.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.coordinates.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.injection, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.injection_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.jayes, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.jayes_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.jayes.io, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.jayes.io_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.jdt, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.jdt_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.models, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.models_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.models.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.models.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.mylyn.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.mylyn.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.net, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.net_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.overrides, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.overrides_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.overrides.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.overrides.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.subwords.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.subwords.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.types.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.types.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.utils, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.utils_2.4.6.v20170307-1041.jar
Id: org.eclipse.recommenders.utils.rcp, Version: 2.4.6.v20170307-1041, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.recommenders.utils.rcp_2.4.6.v20170307-1041.jar
Id: org.eclipse.rse, Version: 3.5.0.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse_3.5.0.201403100950.jar
Id: org.eclipse.rse.connectorservice.dstore, Version: 3.1.301.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.connectorservice.dstore_3.1.301.201403100950.jar
Id: org.eclipse.rse.connectorservice.local, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.connectorservice.local_2.1.400.201403100950.jar
Id: org.eclipse.rse.connectorservice.ssh, Version: 2.1.300.201505220524, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.connectorservice.ssh_2.1.300.201505220524.jar
Id: org.eclipse.rse.connectorservice.telnet, Version: 1.2.300.201505220524, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.connectorservice.telnet_1.2.300.201505220524.jar
Id: org.eclipse.rse.core, Version: 3.3.100.201603151753, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.core_3.3.100.201603151753.jar
Id: org.eclipse.rse.doc.user, Version: 3.4.100.201403101646, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.doc.user_3.4.100.201403101646.jar
Id: org.eclipse.rse.dstore.security, Version: 3.0.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.dstore.security_3.0.400.201403100950.jar
Id: org.eclipse.rse.efs, Version: 2.1.401.201507172212, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.efs_2.1.401.201507172212.jar
Id: org.eclipse.rse.efs.ui, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.efs.ui_2.1.400.201403100950.jar
Id: org.eclipse.rse.files.ui, Version: 3.2.200.201507172213, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.files.ui_3.2.200.201507172213.jar
Id: org.eclipse.rse.importexport, Version: 1.2.300.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.importexport_1.2.300.201403100950.jar
Id: org.eclipse.rse.processes.ui, Version: 3.0.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.processes.ui_3.0.400.201403100950.jar
Id: org.eclipse.rse.services, Version: 3.3.0.201506120731, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.services_3.3.0.201506120731.jar
Id: org.eclipse.rse.services.dstore, Version: 3.3.0.201406041609, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.services.dstore_3.3.0.201406041609.jar
Id: org.eclipse.rse.services.files.ftp, Version: 3.0.500.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.services.files.ftp_3.0.500.201403100950.jar
Id: org.eclipse.rse.services.local, Version: 2.2.1.201507180454, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.services.local_2.2.1.201507180454.jar
Id: org.eclipse.rse.services.ssh, Version: 3.2.100.201403281521, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.services.ssh_3.2.100.201403281521.jar
Id: org.eclipse.rse.services.telnet, Version: 2.0.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.services.telnet_2.0.400.201403100950.jar
Id: org.eclipse.rse.shells.ui, Version: 3.0.500.201403271554, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.shells.ui_3.0.500.201403271554.jar
Id: org.eclipse.rse.subsystems.files.core, Version: 3.3.1.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.files.core_3.3.1.201403100950.jar
Id: org.eclipse.rse.subsystems.files.dstore, Version: 2.1.300.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.files.dstore_2.1.300.201403100950.jar
Id: org.eclipse.rse.subsystems.files.ftp, Version: 2.2.100.201601281414, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.files.ftp_2.2.100.201601281414.jar
Id: org.eclipse.rse.subsystems.files.local, Version: 2.1.300.201403251512, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.files.local_2.1.300.201403251512.jar
Id: org.eclipse.rse.subsystems.files.ssh, Version: 2.1.300.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.files.ssh_2.1.300.201403100950.jar
Id: org.eclipse.rse.subsystems.processes.core, Version: 3.1.300.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.processes.core_3.1.300.201403100950.jar
Id: org.eclipse.rse.subsystems.processes.dstore, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.processes.dstore_2.1.400.201403100950.jar
Id: org.eclipse.rse.subsystems.processes.local, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.processes.local_2.1.400.201403100950.jar
Id: org.eclipse.rse.subsystems.processes.shell.linux, Version: 1.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.processes.shell.linux_1.1.400.201403100950.jar
Id: org.eclipse.rse.subsystems.shells.core, Version: 3.1.300.201403271554, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.shells.core_3.1.300.201403271554.jar
Id: org.eclipse.rse.subsystems.shells.dstore, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.shells.dstore_2.1.400.201403100950.jar
Id: org.eclipse.rse.subsystems.shells.local, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.shells.local_2.1.400.201403100950.jar
Id: org.eclipse.rse.subsystems.shells.ssh, Version: 2.1.400.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.shells.ssh_2.1.400.201403100950.jar
Id: org.eclipse.rse.subsystems.shells.telnet, Version: 1.2.300.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.subsystems.shells.telnet_1.2.300.201403100950.jar
Id: org.eclipse.rse.ui, Version: 3.3.300.201610252046, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.ui_3.3.300.201610252046.jar
Id: org.eclipse.rse.useractions, Version: 1.1.500.201403100950, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.rse.useractions_1.1.500.201403100950.jar
Id: org.eclipse.search, Version: 3.11.1.v20161113-1700, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.search_3.11.1.v20161113-1700.jar
Id: org.eclipse.swt, Version: 3.105.3.v20170228-0512, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.swt_3.105.3.v20170228-0512.jar
Id: org.eclipse.swt.cocoa.macosx.x86_64, Version: 3.105.3.v20170228-0512, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.swt.cocoa.macosx.x86_64_3.105.3.v20170228-0512.jar
Id: org.eclipse.team.core, Version: 3.8.0.v20160418-1534, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.team.core_3.8.0.v20160418-1534.jar
Id: org.eclipse.team.ui, Version: 3.8.0.v20160518-1906, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.team.ui_3.8.0.v20160518-1906.jar
Id: org.eclipse.text, Version: 3.6.0.v20160503-1849, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.text_3.6.0.v20160503-1849.jar
Id: org.eclipse.tm.terminal.connector.local, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.connector.local_4.2.0.201609191434.jar
Id: org.eclipse.tm.terminal.connector.process, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.connector.process_4.2.0.201609191434.jar
Id: org.eclipse.tm.terminal.connector.serial, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.connector.serial_4.2.0.201609191434.jar
Id: org.eclipse.tm.terminal.connector.ssh, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.connector.ssh_4.2.0.201609191434.jar
Id: org.eclipse.tm.terminal.connector.telnet, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.connector.telnet_4.2.0.201609191434.jar
Id: org.eclipse.tm.terminal.control, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.control_4.2.0.201609191434.jar
Id: org.eclipse.tm.terminal.view.core, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.view.core_4.2.0.201609191434.jar
Id: org.eclipse.tm.terminal.view.ui, Version: 4.2.0.201609191434, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.tm.terminal.view.ui_4.2.0.201609191434.jar
Id: org.eclipse.ui, Version: 3.108.1.v20160929-1045, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui_3.108.1.v20160929-1045.jar
Id: org.eclipse.ui.browser, Version: 3.5.2.v20161114-0210, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.browser_3.5.2.v20161114-0210.jar
Id: org.eclipse.ui.cheatsheets, Version: 3.5.0.v20160504-0839, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.cheatsheets_3.5.0.v20160504-0839.jar
Id: org.eclipse.ui.cocoa, Version: 1.1.100.v20151202-1450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.cocoa_1.1.100.v20151202-1450.jar
Id: org.eclipse.ui.console, Version: 3.6.201.v20161107-0337, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.console_3.6.201.v20161107-0337.jar
Id: org.eclipse.ui.editors, Version: 3.10.1.v20161106-1856, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.editors_3.10.1.v20161106-1856.jar
Id: org.eclipse.ui.externaltools, Version: 3.3.100.v20160518-1858, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.externaltools_3.3.100.v20160518-1858.jar
Id: org.eclipse.ui.forms, Version: 3.7.1.v20161220-1635, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.forms_3.7.1.v20161220-1635.jar
Id: org.eclipse.ui.ide, Version: 3.12.3.v20170119-0935, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.ide_3.12.3.v20170119-0935.jar
Id: org.eclipse.ui.ide.application, Version: 1.1.101.v20160829-0827, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.ide.application_1.1.101.v20160829-0827.jar
Id: org.eclipse.ui.intro, Version: 3.5.2.v20161116-1147, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.intro_3.5.2.v20161116-1147.jar
Id: org.eclipse.ui.intro.quicklinks, Version: 1.0.0.v20160515-0255, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.intro.quicklinks_1.0.0.v20160515-0255.jar
Id: org.eclipse.ui.intro.universal, Version: 3.3.1.v20160829-1558, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.intro.universal_3.3.1.v20160829-1558.jar
Id: org.eclipse.ui.monitoring, Version: 1.1.2.v20170203-1115, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.monitoring_1.1.2.v20170203-1115.jar
Id: org.eclipse.ui.navigator, Version: 3.6.101.v20161006-1120, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.navigator_3.6.101.v20161006-1120.jar
Id: org.eclipse.ui.navigator.resources, Version: 3.5.101.v20161006-0640, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.navigator.resources_3.5.101.v20161006-0640.jar
Id: org.eclipse.ui.net, Version: 1.3.0.v20160426-1633, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.net_1.3.0.v20160426-1633.jar
Id: org.eclipse.ui.themes, Version: 1.1.300.v20161107-1827, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.themes_1.1.300.v20161107-1827
Id: org.eclipse.ui.trace, Version: 1.0.400.v20160509-1055, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.trace_1.0.400.v20160509-1055.jar
Id: org.eclipse.ui.views, Version: 3.8.102.v20170111-0801, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.views_3.8.102.v20170111-0801.jar
Id: org.eclipse.ui.views.log, Version: 1.2.1.v20160829-0826, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.views.log_1.2.1.v20160829-0826.jar
Id: org.eclipse.ui.views.properties.tabbed, Version: 3.7.0.v20160310-0903, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.views.properties.tabbed_3.7.0.v20160310-0903.jar
Id: org.eclipse.ui.workbench, Version: 3.108.3.v20170216-1539, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.workbench_3.108.3.v20170216-1539.jar
Id: org.eclipse.ui.workbench.texteditor, Version: 3.10.1.v20160818-1626, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.ui.workbench.texteditor_3.10.1.v20160818-1626.jar
Id: org.eclipse.update.configurator, Version: 3.3.400.v20160506-0750, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.update.configurator_3.3.400.v20160506-0750.jar
Id: org.eclipse.userstorage, Version: 1.0.1.v20170201-1648, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.userstorage_1.0.1.v20170201-1648.jar
Id: org.eclipse.userstorage.ui, Version: 1.0.1.v20170201-1648, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.userstorage.ui_1.0.1.v20170201-1648.jar
Id: org.eclipse.wst.command.env, Version: 1.0.500.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.command.env_1.0.500.v201505131719.jar
Id: org.eclipse.wst.command.env.core, Version: 1.0.300.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.command.env.core_1.0.300.v201505131719.jar
Id: org.eclipse.wst.command.env.doc.user, Version: 1.5.400.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.command.env.doc.user_1.5.400.v201309242123.jar
Id: org.eclipse.wst.command.env.infopop, Version: 1.0.200.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.command.env.infopop_1.0.200.v201309242123.jar
Id: org.eclipse.wst.command.env.ui, Version: 1.1.200.v201503231435, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.command.env.ui_1.1.200.v201503231435.jar
Id: org.eclipse.wst.common.core, Version: 1.2.0.v200908251833, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.core_1.2.0.v200908251833.jar
Id: org.eclipse.wst.common.emf, Version: 1.2.500.v201701191735, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.emf_1.2.500.v201701191735.jar
Id: org.eclipse.wst.common.emfworkbench.integration, Version: 1.2.101.v201107081800, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.emfworkbench.integration_1.2.101.v201107081800.jar
Id: org.eclipse.wst.common.environment, Version: 1.0.400.v200912181831, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.environment_1.0.400.v200912181831.jar
Id: org.eclipse.wst.common.frameworks, Version: 1.2.200.v201304241450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.frameworks_1.2.200.v201304241450.jar
Id: org.eclipse.wst.common.frameworks.ui, Version: 1.2.400.v201504292002, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.frameworks.ui_1.2.400.v201504292002.jar
Id: org.eclipse.wst.common.infopop, Version: 1.0.300.v201309101952, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.infopop_1.0.300.v201309101952.jar
Id: org.eclipse.wst.common.modulecore, Version: 1.2.500.v201701032135, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.modulecore_1.2.500.v201701032135.jar
Id: org.eclipse.wst.common.modulecore.ui, Version: 1.0.300.v201505072128, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.modulecore.ui_1.0.300.v201505072128.jar
Id: org.eclipse.wst.common.project.facet.core, Version: 1.4.300.v201111030423, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.project.facet.core_1.4.300.v201111030423.jar
Id: org.eclipse.wst.common.project.facet.ui, Version: 1.4.600.v201505072140, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.project.facet.ui_1.4.600.v201505072140.jar
Id: org.eclipse.wst.common.snippets, Version: 1.2.300.v201602270217, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.snippets_1.2.300.v201602270217.jar
Id: org.eclipse.wst.common.ui, Version: 1.1.500.v200911182011, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.ui_1.1.500.v200911182011.jar
Id: org.eclipse.wst.common.uriresolver, Version: 1.2.200.v201505132009, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.common.uriresolver_1.2.200.v201505132009.jar
Id: org.eclipse.wst.css.core, Version: 1.1.900.v201603171933, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.css.core_1.1.900.v201603171933.jar
Id: org.eclipse.wst.css.ui, Version: 1.0.1001.v201608060346, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.css.ui_1.0.1001.v201608060346.jar
Id: org.eclipse.wst.doc.user, Version: 1.2.0.v201309112106, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.doc.user_1.2.0.v201309112106.jar
Id: org.eclipse.wst.dtd.core, Version: 1.1.700.v201211012112, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.dtd.core_1.1.700.v201211012112.jar
Id: org.eclipse.wst.dtd.ui, Version: 1.0.801.v201308100602, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.dtd.ui_1.0.801.v201308100602.jar
Id: org.eclipse.wst.dtd.ui.infopop, Version: 1.0.400.v201309112106, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.dtd.ui.infopop_1.0.400.v201309112106.jar
Id: org.eclipse.wst.dtdeditor.doc.user, Version: 1.0.700.v201208081537, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.dtdeditor.doc.user_1.0.700.v201208081537.jar
Id: org.eclipse.wst.html.core, Version: 1.2.1.v201608061844, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.html.core_1.2.1.v201608061844.jar
Id: org.eclipse.wst.html.ui, Version: 1.0.1101.v201608060430, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.html.ui_1.0.1101.v201608060430.jar
Id: org.eclipse.wst.html.ui.infopop, Version: 1.0.201.v201409111852, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.html.ui.infopop_1.0.201.v201409111852.jar
Id: org.eclipse.wst.internet.cache, Version: 1.0.701.v201510130022, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.internet.cache_1.0.701.v201510130022.jar
Id: org.eclipse.wst.internet.monitor.core, Version: 1.0.600.v201309182039, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.internet.monitor.core_1.0.600.v201309182039.jar
Id: org.eclipse.wst.internet.monitor.ui, Version: 1.0.700.v201309182039, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.internet.monitor.ui_1.0.700.v201309182039.jar
Id: org.eclipse.wst.jsdt.chromium, Version: 0.5.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium_0.5.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.chromium.debug, Version: 0.4.0.v201605131737, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.debug_0.4.0.v201605131737.jar
Id: org.eclipse.wst.jsdt.chromium.debug.core, Version: 0.5.200.v201701261810, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.debug.core_0.5.200.v201701261810.jar
Id: org.eclipse.wst.jsdt.chromium.debug.js, Version: 0.1.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.debug.js_0.1.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.chromium.debug.jsdtbridge, Version: 0.5.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.debug.jsdtbridge_0.5.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.chromium.debug.ui, Version: 0.6.200.v201701261810, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.debug.ui_0.6.200.v201701261810.jar
Id: org.eclipse.wst.jsdt.chromium.wip.eclipse, Version: 0.5.200.v201610212001, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.wip.eclipse_0.5.200.v201610212001.jar
Id: org.eclipse.wst.jsdt.chromium.wipbackend.dev, Version: 0.5.200.v201610212001, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.wipbackend.dev_0.5.200.v201610212001.jar
Id: org.eclipse.wst.jsdt.chromium.wipbackend.protocol_1_0, Version: 0.5.200.v201610212001, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.chromium.wipbackend.protocol_1_0_0.5.200.v201610212001.jar
Id: org.eclipse.wst.jsdt.core, Version: 2.0.200.v201612211424, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.core_2.0.200.v201612211424.jar
Id: org.eclipse.wst.jsdt.debug.core, Version: 3.2.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.debug.core_3.2.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.debug.crossfire, Version: 1.0.500.v201505071819, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.debug.crossfire_1.0.500.v201505071819.jar
Id: org.eclipse.wst.jsdt.debug.rhino, Version: 1.0.500.v201605251607, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.debug.rhino_1.0.500.v201605251607.jar
Id: org.eclipse.wst.jsdt.debug.rhino.debugger, Version: 1.0.600.v201604292217, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.debug.rhino.debugger_1.0.600.v201604292217.jar
Id: org.eclipse.wst.jsdt.debug.rhino.ui, Version: 1.0.500.v201604292217, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.debug.rhino.ui_1.0.500.v201604292217.jar
Id: org.eclipse.wst.jsdt.debug.transport, Version: 1.0.300.v201502261613, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.debug.transport_1.0.300.v201502261613.jar
Id: org.eclipse.wst.jsdt.debug.ui, Version: 1.0.600.v201605311817, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.debug.ui_1.0.600.v201605311817.jar
Id: org.eclipse.wst.jsdt.doc, Version: 2.0.200.v201610220243, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.doc_2.0.200.v201610220243.jar
Id: org.eclipse.wst.jsdt.js.bower, Version: 1.0.200.v201610220243, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.bower_1.0.200.v201610220243.jar
Id: org.eclipse.wst.jsdt.js.cli, Version: 1.0.0.v201605192332, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.cli_1.0.0.v201605192332.jar
Id: org.eclipse.wst.jsdt.js.common, Version: 1.0.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.common_1.0.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.js.grunt, Version: 1.0.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.grunt_1.0.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.js.gulp, Version: 1.0.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.gulp_1.0.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.js.node, Version: 1.0.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.node_1.0.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.js.node.common, Version: 1.0.0.v201605131737, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.node.common_1.0.0.v201605131737.jar
Id: org.eclipse.wst.jsdt.js.npm, Version: 1.0.200.v201610211901, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.js.npm_1.0.200.v201610211901.jar
Id: org.eclipse.wst.jsdt.manipulation, Version: 1.0.601.v201602241911, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.manipulation_1.0.601.v201602241911.jar
Id: org.eclipse.wst.jsdt.nashorn.extension, Version: 1.0.2.v201610280128, Location: initial@reference:file:../../../../../.p2/pool/plugins/org.eclipse.wst.jsdt.nashorn.extension_1.0.2.v201610280128.jar
Id: org.eclipse.wst.jsdt.support.firefox, Version: 1.0.501.v201602241911, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.support.firefox_1.0.501.v201602241911.jar
Id: org.eclipse.wst.jsdt.support.ie, Version: 1.0.601.v201602241911, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.support.ie_1.0.601.v201602241911.jar
Id: org.eclipse.wst.jsdt.ui, Version: 2.0.200.v201612151739, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.ui_2.0.200.v201612151739.jar
Id: org.eclipse.wst.jsdt.web.core, Version: 1.0.801.v201602241914, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.web.core_1.0.801.v201602241914.jar
Id: org.eclipse.wst.jsdt.web.support.jsp, Version: 1.0.600.v201307151913, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.web.support.jsp_1.0.600.v201307151913.jar
Id: org.eclipse.wst.jsdt.web.ui, Version: 1.0.801.v201602241914, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.jsdt.web.ui_1.0.801.v201602241914.jar
Id: org.eclipse.wst.json.bower.core, Version: 1.0.0.v201605150457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.bower.core_1.0.0.v201605150457.jar
Id: org.eclipse.wst.json.bower.ui, Version: 1.0.0.v201605201503, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.bower.ui_1.0.0.v201605201503.jar
Id: org.eclipse.wst.json.core, Version: 1.0.2.v201612232230, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.core_1.0.2.v201612232230.jar
Id: org.eclipse.wst.json.eslint.core, Version: 1.0.0.v201605150457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.eslint.core_1.0.0.v201605150457.jar
Id: org.eclipse.wst.json.eslint.ui, Version: 1.0.0.v201605201503, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.eslint.ui_1.0.0.v201605201503.jar
Id: org.eclipse.wst.json.jshint.core, Version: 1.0.0.v201605150457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.jshint.core_1.0.0.v201605150457.jar
Id: org.eclipse.wst.json.jshint.ui, Version: 1.0.0.v201605201503, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.jshint.ui_1.0.0.v201605201503.jar
Id: org.eclipse.wst.json.npm.core, Version: 1.0.0.v201605150457, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.npm.core_1.0.0.v201605150457.jar
Id: org.eclipse.wst.json.npm.ui, Version: 1.0.0.v201605201503, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.npm.ui_1.0.0.v201605201503.jar
Id: org.eclipse.wst.json.schemaprocessor, Version: 1.0.100.v201612232230, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.schemaprocessor_1.0.100.v201612232230.jar
Id: org.eclipse.wst.json.ui, Version: 1.0.1.v201612232230, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.json.ui_1.0.1.v201612232230.jar
Id: org.eclipse.wst.server.core, Version: 1.9.0.v201610211907, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.core_1.9.0.v201610211907.jar
Id: org.eclipse.wst.server.discovery, Version: 1.3.0.v201606030549, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.discovery_1.3.0.v201606030549.jar
Id: org.eclipse.wst.server.http.core, Version: 1.0.300.v201606081655, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.http.core_1.0.300.v201606081655.jar
Id: org.eclipse.wst.server.http.ui, Version: 1.0.400.v201309182039, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.http.ui_1.0.400.v201309182039.jar
Id: org.eclipse.wst.server.preview, Version: 1.1.400.v201703062119, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.preview_1.1.400.v201703062119.jar
Id: org.eclipse.wst.server.preview.adapter, Version: 1.1.300.v201606081655, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.preview.adapter_1.1.300.v201606081655.jar
Id: org.eclipse.wst.server.ui, Version: 1.5.307.v201611072017, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.ui_1.5.307.v201611072017.jar
Id: org.eclipse.wst.server.ui.doc.user, Version: 1.1.600.v201309182117, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.ui.doc.user_1.1.600.v201309182117.jar
Id: org.eclipse.wst.server.ui.infopop, Version: 1.1.200.v201309182117, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.server.ui.infopop_1.1.200.v201309182117.jar
Id: org.eclipse.wst.sse.core, Version: 1.1.1000.v201608061842, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.sse.core_1.1.1000.v201608061842.jar
Id: org.eclipse.wst.sse.doc.user, Version: 1.1.100.v201208081537, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.sse.doc.user_1.1.100.v201208081537.jar
Id: org.eclipse.wst.sse.ui, Version: 1.3.500.v201605120129, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.sse.ui_1.3.500.v201605120129.jar
Id: org.eclipse.wst.sse.ui.infopop, Version: 1.0.300.v201309112106, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.sse.ui.infopop_1.0.300.v201309112106.jar
Id: org.eclipse.wst.standard.schemas, Version: 1.0.700.v201304171715, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.standard.schemas_1.0.700.v201304171715.jar
Id: org.eclipse.wst.validation, Version: 1.2.700.v201508251749, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.validation_1.2.700.v201508251749.jar
Id: org.eclipse.wst.validation.infopop, Version: 1.0.300.v201309101952, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.validation.infopop_1.0.300.v201309101952.jar
Id: org.eclipse.wst.validation.ui, Version: 1.2.500.v201310231452, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.validation.ui_1.2.500.v201310231452.jar
Id: org.eclipse.wst.web, Version: 1.1.800.v201312041437, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.web_1.1.800.v201312041437.jar
Id: org.eclipse.wst.web.ui, Version: 1.1.601.v201602221748, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.web.ui_1.1.601.v201602221748.jar
Id: org.eclipse.wst.web.ui.infopop, Version: 1.0.300.v200805140206, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.web.ui.infopop_1.0.300.v200805140206.jar
Id: org.eclipse.wst.webtools.doc.user, Version: 1.0.500.v201208081537, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.webtools.doc.user_1.0.500.v201208081537.jar
Id: org.eclipse.wst.ws, Version: 1.1.400.v201503231435, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.ws_1.1.400.v201503231435.jar
Id: org.eclipse.wst.ws.explorer, Version: 1.0.900.v201612121628, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.ws.explorer_1.0.900.v201612121628.jar
Id: org.eclipse.wst.ws.infopop, Version: 1.0.400.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.ws.infopop_1.0.400.v201309242123.jar
Id: org.eclipse.wst.ws.parser, Version: 1.0.600.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.ws.parser_1.0.600.v201505131719.jar
Id: org.eclipse.wst.ws.service.policy, Version: 1.0.450.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.ws.service.policy_1.0.450.v201505131719.jar
Id: org.eclipse.wst.ws.service.policy.ui, Version: 1.0.500.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.ws.service.policy.ui_1.0.500.v201505131719.jar
Id: org.eclipse.wst.ws.ui, Version: 1.1.300.v201503231435, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.ws.ui_1.1.300.v201503231435.jar
Id: org.eclipse.wst.wsdl, Version: 1.2.400.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.wsdl_1.2.400.v201505131719.jar
Id: org.eclipse.wst.wsdl.ui, Version: 1.2.800.v201510282151, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.wsdl.ui_1.2.800.v201510282151.jar
Id: org.eclipse.wst.wsdl.ui.doc.user, Version: 1.0.850.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.wsdl.ui.doc.user_1.0.850.v201309242123.jar
Id: org.eclipse.wst.wsdl.validation, Version: 1.1.700.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.wsdl.validation_1.1.700.v201505131719.jar
Id: org.eclipse.wst.wsi, Version: 1.0.600.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.wsi_1.0.600.v201505131719.jar
Id: org.eclipse.wst.wsi.ui, Version: 1.0.600.v201505131719, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.wsi.ui_1.0.600.v201505131719.jar
Id: org.eclipse.wst.wsi.ui.doc.user, Version: 1.0.750.v201309242123, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.wsi.ui.doc.user_1.0.750.v201309242123.jar
Id: org.eclipse.wst.xml.core, Version: 1.1.1001.v201702270442, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.core_1.1.1001.v201702270442.jar
Id: org.eclipse.wst.xml.ui, Version: 1.1.700.v201604272318, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.ui_1.1.700.v201604272318.jar
Id: org.eclipse.wst.xml.ui.infopop, Version: 1.0.400.v201309112106, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.ui.infopop_1.0.400.v201309112106.jar
Id: org.eclipse.wst.xml.xpath.core, Version: 1.3.1.v201509231858, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.xpath.core_1.3.1.v201509231858.jar
Id: org.eclipse.wst.xml.xpath.ui, Version: 1.1.102.v201509231858, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.xpath.ui_1.1.102.v201509231858.jar
Id: org.eclipse.wst.xml.xpath2, Version: 1.1.0.v201309251557, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.xpath2_1.1.0.v201309251557.jar
Id: org.eclipse.wst.xml.xpath2.processor, Version: 2.1.101.v201409111854, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.xpath2.processor_2.1.101.v201409111854.jar
Id: org.eclipse.wst.xml.xpath2.processor.doc.user, Version: 2.0.0.v201209212251, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.xpath2.processor.doc.user_2.0.0.v201209212251.jar
Id: org.eclipse.wst.xml.xpath2.wtptypes, Version: 2.0.0.v201208081543, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xml.xpath2.wtptypes_2.0.0.v201208081543.jar
Id: org.eclipse.wst.xmleditor.doc.user, Version: 1.0.700.v201208081537, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xmleditor.doc.user_1.0.700.v201208081537.jar
Id: org.eclipse.wst.xsd.core, Version: 1.1.900.v201401141857, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsd.core_1.1.900.v201401141857.jar
Id: org.eclipse.wst.xsd.ui, Version: 1.2.600.v201511240159, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsd.ui_1.2.600.v201511240159.jar
Id: org.eclipse.wst.xsdeditor.doc.user, Version: 1.0.800.v201208081537, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsdeditor.doc.user_1.0.800.v201208081537.jar
Id: org.eclipse.wst.xsl, Version: 1.2.0.v201309251559, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl_1.2.0.v201309251559.jar
Id: org.eclipse.wst.xsl.core, Version: 1.1.301.v201405151730, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.core_1.1.301.v201405151730.jar
Id: org.eclipse.wst.xsl.debug.ui, Version: 1.0.302.v201304240928, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.debug.ui_1.0.302.v201304240928.jar
Id: org.eclipse.wst.xsl.doc, Version: 1.0.100.v201309251559, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.doc_1.0.100.v201309251559.jar
Id: org.eclipse.wst.xsl.exslt.core, Version: 1.0.0.v201005240422, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.exslt.core_1.0.0.v201005240422.jar
Id: org.eclipse.wst.xsl.exslt.ui, Version: 1.0.0.v201006012004, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.exslt.ui_1.0.0.v201006012004.jar
Id: org.eclipse.wst.xsl.jaxp.debug, Version: 1.0.300.v201304102131, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.jaxp.debug_1.0.300.v201304102131.jar
Id: org.eclipse.wst.xsl.jaxp.debug.ui, Version: 1.0.200.v201103081755, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.jaxp.debug.ui_1.0.200.v201103081755.jar
Id: org.eclipse.wst.xsl.jaxp.launching, Version: 1.0.300.v201304102131, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.jaxp.launching_1.0.300.v201304102131.jar
Id: org.eclipse.wst.xsl.launching, Version: 1.1.0.v201304240928, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.launching_1.1.0.v201304240928.jar
Id: org.eclipse.wst.xsl.saxon, Version: 1.0.200.v201103081755, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.saxon_1.0.200.v201103081755.jar
Id: org.eclipse.wst.xsl.ui, Version: 1.1.301.v201304222136, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.ui_1.1.301.v201304222136.jar
Id: org.eclipse.wst.xsl.xalan, Version: 1.0.100.v201208081544, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wst.xsl.xalan_1.0.100.v201208081544.jar
Id: org.eclipse.wtp.epp.package.capabilities, Version: 1.3.0.v201005102000, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wtp.epp.package.capabilities_1.3.0.v201005102000.jar
Id: org.eclipse.wtp.epp.package.jee.intro, Version: 1.3.0.v201006142040, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wtp.epp.package.jee.intro_1.3.0.v201006142040.jar
Id: org.eclipse.wtp.javascript.capabilities, Version: 1.0.100.v201005102000, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wtp.javascript.capabilities_1.0.100.v201005102000.jar
Id: org.eclipse.wtp.jee.capabilities, Version: 1.0.100.v201005102000, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wtp.jee.capabilities_1.0.100.v201005102000.jar
Id: org.eclipse.wtp.web.capabilities, Version: 1.0.100.v201005102000, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wtp.web.capabilities_1.0.100.v201005102000.jar
Id: org.eclipse.wtp.xml.capabilities, Version: 1.0.100.v201005102000, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.wtp.xml.capabilities_1.0.100.v201005102000.jar
Id: org.eclipse.xsd, Version: 2.12.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.xsd_2.12.0.v20160526-0356.jar
Id: org.eclipse.xsd.edit, Version: 2.8.0.v20160526-0356, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.xsd.edit_2.8.0.v20160526-0356.jar
Id: org.eclipse.zest.core, Version: 1.5.300.201606061308, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.zest.core_1.5.300.201606061308.jar
Id: org.eclipse.zest.layouts, Version: 1.1.300.201606061308, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.eclipse.zest.layouts_1.1.300.201606061308.jar
Id: org.hamcrest.core, Version: 1.3.0.v201303031735, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.hamcrest.core_1.3.0.v201303031735.jar
Id: org.jdom, Version: 1.1.1.v201101151400, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.jdom_1.1.1.v201101151400.jar
Id: org.json, Version: 1.0.0.v201011060100, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.json_1.0.0.v201011060100.jar
Id: org.jsoup, Version: 1.7.2.v201411291515, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.jsoup_1.7.2.v201411291515.jar
Id: org.junit, Version: 4.12.0.v201504281640, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.junit_4.12.0.v201504281640
Id: org.mozilla.javascript, Version: 1.7.5.v201504281450, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.mozilla.javascript_1.7.5.v201504281450.jar
Id: org.objectweb.asm, Version: 5.0.1.v201404251740, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.objectweb.asm_5.0.1.v201404251740.jar
Id: org.objectweb.asm.tree, Version: 5.0.1.v201404251740, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.objectweb.asm.tree_5.0.1.v201404251740.jar
Id: org.reactivestreams.reactive-streams, Version: 1.0.0.release, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.reactivestreams.reactive-streams_1.0.0.release.jar
Id: org.sat4j.core, Version: 2.3.5.v201308161310, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.sat4j.core_2.3.5.v201308161310.jar
Id: org.sat4j.pb, Version: 2.3.5.v201404071733, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.sat4j.pb_2.3.5.v201404071733.jar
Id: org.slf4j.api, Version: 1.7.2.v20121108-1250, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.slf4j.api_1.7.2.v20121108-1250.jar
Id: org.slf4j.impl.log4j12, Version: 1.7.2.v20131105-2200, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.slf4j.impl.log4j12_1.7.2.v20131105-2200.jar
Id: org.sonatype.m2e.mavenarchiver, Version: 0.17.2.201606141937-signed-20160830073346, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.sonatype.m2e.mavenarchiver_0.17.2.201606141937-signed-20160830073346.jar
Id: org.springframework.aop, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.aop_4.3.0.20160611-RELEASE.jar
Id: org.springframework.beans, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.beans_4.3.0.20160611-RELEASE.jar
Id: org.springframework.context, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.context_4.3.0.20160611-RELEASE.jar
Id: org.springframework.context.support, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.context.support_4.3.0.20160611-RELEASE.jar
Id: org.springframework.core, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.core_4.3.0.20160611-RELEASE.jar
Id: org.springframework.data.core, Version: 1.11.4.20160223-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.data.core_1.11.4.20160223-RELEASE.jar
Id: org.springframework.expression, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.expression_4.3.0.20160611-RELEASE.jar
Id: org.springframework.ide.eclipse, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.aeri, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.aeri_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.aop.core, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.aop.core_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.aop.ui, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.aop.ui_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.aop.ui.matcher, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.aop.ui.matcher_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.batch, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.batch_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.core, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.core_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.core.autowire, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.core.autowire_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.core.metadata, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.core.metadata_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.mylyn, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.mylyn_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.ui, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.ui_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.ui.autowire, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.ui.autowire_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.ui.editor, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.ui.editor_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.ui.graph, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.ui.graph_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.ui.livegraph, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.ui.livegraph_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.ui.refactoring, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.ui.refactoring_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.beans.ui.search, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.beans.ui.search_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.bestpractices, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.bestpractices_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.boot, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.boot_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.boot.dash, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.boot.dash_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.boot.launch, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.boot.launch_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.boot.properties.editor, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.boot.properties.editor_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.boot.properties.editor.yaml, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.boot.properties.editor.yaml_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.boot.templates, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.boot.templates_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.boot.wizard, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.boot.wizard_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.buildship, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.buildship_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.buildship20, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.buildship20_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.cloudfoundry.manifest.editor, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.cloudfoundry.manifest.editor_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.config.core, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.config.core_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.config.graph, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.config.graph_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.config.ui, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.config.ui_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.core, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.core_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.data.core, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.data.core_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.doc, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.doc_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.editor.support, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.editor.support_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.gradle, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.gradle_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.imports, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.imports_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.integration, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.integration_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.maven, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.maven_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.metadata, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.metadata_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.mylyn, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.mylyn_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.quickfix, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.quickfix_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.security, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.security_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.ui, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.ui_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.webflow.core, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.webflow.core_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.webflow.ui, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.webflow.ui_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.webflow.ui.editor, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.webflow.ui.editor_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.webflow.ui.graph, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.webflow.ui.graph_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.ide.eclipse.wizard, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.ide.eclipse.wizard_3.8.4.201703310634-RELEASE.jar
Id: org.springframework.jdbc, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.jdbc_4.3.0.20160611-RELEASE.jar
Id: org.springframework.jms, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.jms_4.3.0.20160611-RELEASE.jar
Id: org.springframework.orm, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.orm_4.3.0.20160611-RELEASE.jar
Id: org.springframework.oxm, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.oxm_4.3.0.20160611-RELEASE.jar
Id: org.springframework.transaction, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.transaction_4.3.0.20160611-RELEASE.jar
Id: org.springframework.web, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.web_4.3.0.20160611-RELEASE.jar
Id: org.springframework.web.servlet, Version: 4.3.0.20160611-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springframework.web.servlet_4.3.0.20160611-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.cloudfoundry.client, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.cloudfoundry.client_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.cloudfoundry.client.v2, Version: 3.8.4.201703310634-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.cloudfoundry.client.v2_3.8.4.201703310634-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.completions, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.completions_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.configurator, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.configurator_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.content.core, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.content.core_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.core, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.core_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.frameworks.core, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.frameworks.core_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.frameworks.ui, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.frameworks.ui_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.livexp, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.livexp_3.8.4.201703310458-RELEASE.jar
Id: org.springsource.ide.eclipse.commons.ui, Version: 3.8.4.201703310458-RELEASE, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.springsource.ide.eclipse.commons.ui_3.8.4.201703310458-RELEASE.jar
Id: org.tukaani.xz, Version: 1.3.0.v201308270617, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.tukaani.xz_1.3.0.v201308270617.jar
Id: org.uddi4j, Version: 2.0.5.v200805270300, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.uddi4j_2.0.5.v200805270300.jar
Id: org.w3c.css.sac, Version: 1.3.1.v200903091627, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.w3c.css.sac_1.3.1.v200903091627.jar
Id: org.w3c.dom.events, Version: 3.0.0.draft20060413_v201105210656, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.w3c.dom.events_3.0.0.draft20060413_v201105210656.jar
Id: org.w3c.dom.smil, Version: 1.0.1.v200903091627, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.w3c.dom.smil_1.0.1.v200903091627.jar
Id: org.w3c.dom.svg, Version: 1.1.0.v201011041433, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.w3c.dom.svg_1.1.0.v201011041433.jar
Id: org.yaml.snakeyaml, Version: 1.14.0.v201604211500, Location: reference:file:/Users/m134910/.p2/pool/plugins/org.yaml.snakeyaml_1.14.0.v201604211500.jar

*** Security Configuration:
Providers (10): 

 Provider: SUN, Version: 1.8, Class: sun.security.provider.Sun
  Description: SUN (DSA key/parameter generation; DSA signing; SHA-1, MD5 digests; SecureRandom; X.509 certificates; JKS & DKS keystores; PKIX CertPathValidator; PKIX CertPathBuilder; LDAP, Collection CertStores, JavaPolicy Policy; JavaLoginConfig Configuration)
  Services (30):
   Service: MessageDigest, Algorithm: SHA-512, Class: sun.security.provider.SHA5$SHA512
    Aliases: 2.16.840.1.101.3.4.2.3
   Service: Configuration, Algorithm: JavaLoginConfig, Class: sun.security.provider.ConfigFile$Spi
   Service: Signature, Algorithm: NONEwithDSA, Class: sun.security.provider.DSA$RawDSA
    Aliases: RawDSA
    Attributes:
      KeySize: 1024
      SupportedKeyClasses: java.security.interfaces.DSAPublicKey|java.security.interfaces.DSAPrivateKey
   Service: CertPathBuilder, Algorithm: PKIX, Class: sun.security.provider.certpath.SunCertPathBuilder
    Attributes:
      ImplementedIn: Software
      ValidationAlgorithm: RFC3280
   Service: CertStore, Algorithm: LDAP, Class: sun.security.provider.certpath.ldap.LDAPCertStore
    Attributes:
      ImplementedIn: Software
      LDAPSchema: RFC2587
   Service: CertificateFactory, Algorithm: X.509, Class: sun.security.provider.X509Factory
    Aliases: X509
    Attributes:
      ImplementedIn: Software
   Service: MessageDigest, Algorithm: SHA, Class: sun.security.provider.SHA
    Aliases: SHA1
    Attributes:
      ImplementedIn: Software
   Service: KeyStore, Algorithm: DKS, Class: sun.security.provider.DomainKeyStore$DKS
   Service: MessageDigest, Algorithm: SHA-384, Class: sun.security.provider.SHA5$SHA384
    Aliases: 2.16.840.1.101.3.4.2.2
   Service: SecureRandom, Algorithm: NativePRNG, Class: sun.security.provider.NativePRNG
   Service: Signature, Algorithm: SHA224withDSA, Class: sun.security.provider.DSA$SHA224withDSA
    Aliases: 2.16.840.1.101.3.4.3.1
    Attributes:
      KeySize: 2048
      SupportedKeyClasses: java.security.interfaces.DSAPublicKey|java.security.interfaces.DSAPrivateKey
   Service: KeyPairGenerator, Algorithm: DSA, Class: sun.security.provider.DSAKeyPairGenerator
    Aliases: OID.1.2.840.10040.4.1
    Attributes:
      ImplementedIn: Software
      KeySize: 2048
   Service: KeyStore, Algorithm: JKS, Class: sun.security.provider.JavaKeyStore$DualFormatJKS
    Attributes:
      ImplementedIn: Software
   Service: SecureRandom, Algorithm: NativePRNGBlocking, Class: sun.security.provider.NativePRNG$Blocking
   Service: KeyStore, Algorithm: CaseExactJKS, Class: sun.security.provider.JavaKeyStore$CaseExactJKS
   Service: MessageDigest, Algorithm: SHA-256, Class: sun.security.provider.SHA2$SHA256
    Aliases: 2.16.840.1.101.3.4.2.1
   Service: CertStore, Algorithm: com.sun.security.IndexedCollection, Class: sun.security.provider.certpath.IndexedCollectionCertStore
    Attributes:
      ImplementedIn: Software
   Service: KeyFactory, Algorithm: DSA, Class: sun.security.provider.DSAKeyFactory
    Aliases: OID.1.2.840.10040.4.1
    Attributes:
      ImplementedIn: Software
   Service: MessageDigest, Algorithm: SHA-224, Class: sun.security.provider.SHA2$SHA224
    Aliases: 2.16.840.1.101.3.4.2.4
   Service: SecureRandom, Algorithm: SHA1PRNG, Class: sun.security.provider.SecureRandom
    Attributes:
      ImplementedIn: Software
   Service: CertPathValidator, Algorithm: PKIX, Class: sun.security.provider.certpath.PKIXCertPathValidator
    Attributes:
      ImplementedIn: Software
      ValidationAlgorithm: RFC3280
   Service: CertStore, Algorithm: Collection, Class: sun.security.provider.certpath.CollectionCertStore
    Attributes:
      ImplementedIn: Software
   Service: MessageDigest, Algorithm: MD5, Class: sun.security.provider.MD5
    Attributes:
      ImplementedIn: Software
   Service: AlgorithmParameters, Algorithm: DSA, Class: sun.security.provider.DSAParameters
    Aliases: OID.1.2.840.10040.4.1
    Attributes:
      ImplementedIn: Software
   Service: Policy, Algorithm: JavaPolicy, Class: sun.security.provider.PolicySpiFile
   Service: MessageDigest, Algorithm: MD2, Class: sun.security.provider.MD2
   Service: Signature, Algorithm: SHA1withDSA, Class: sun.security.provider.DSA$SHA1withDSA
    Aliases: DSAWithSHA1
    Attributes:
      ImplementedIn: Software
      KeySize: 1024
      SupportedKeyClasses: java.security.interfaces.DSAPublicKey|java.security.interfaces.DSAPrivateKey
   Service: Signature, Algorithm: SHA256withDSA, Class: sun.security.provider.DSA$SHA256withDSA
    Aliases: 2.16.840.1.101.3.4.3.2
    Attributes:
      KeySize: 2048
      SupportedKeyClasses: java.security.interfaces.DSAPublicKey|java.security.interfaces.DSAPrivateKey
   Service: AlgorithmParameterGenerator, Algorithm: DSA, Class: sun.security.provider.DSAParameterGenerator
    Aliases: OID.1.2.840.10040.4.1
    Attributes:
      ImplementedIn: Software
      KeySize: 2048
   Service: SecureRandom, Algorithm: NativePRNGNonBlocking, Class: sun.security.provider.NativePRNG$NonBlocking

 Provider: SunRsaSign, Version: 1.8, Class: sun.security.rsa.SunRsaSign
  Description: Sun RSA signature provider
  Services (9):
   Service: Signature, Algorithm: SHA512withRSA, Class: sun.security.rsa.RSASignature$SHA512withRSA
    Aliases: 1.2.840.113549.1.1.13
    Attributes:
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey
   Service: Signature, Algorithm: MD5withRSA, Class: sun.security.rsa.RSASignature$MD5withRSA
    Aliases: OID.1.2.840.113549.1.1.4
    Attributes:
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey
   Service: Signature, Algorithm: SHA1withRSA, Class: sun.security.rsa.RSASignature$SHA1withRSA
    Aliases: OID.1.2.840.113549.1.1.5
    Attributes:
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey
   Service: KeyFactory, Algorithm: RSA, Class: sun.security.rsa.RSAKeyFactory
    Aliases: 1.2.840.113549.1.1
   Service: Signature, Algorithm: SHA384withRSA, Class: sun.security.rsa.RSASignature$SHA384withRSA
    Aliases: 1.2.840.113549.1.1.12
    Attributes:
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey
   Service: KeyPairGenerator, Algorithm: RSA, Class: sun.security.rsa.RSAKeyPairGenerator
    Aliases: 1.2.840.113549.1.1
   Service: Signature, Algorithm: SHA256withRSA, Class: sun.security.rsa.RSASignature$SHA256withRSA
    Aliases: 1.2.840.113549.1.1.11
    Attributes:
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey
   Service: Signature, Algorithm: MD2withRSA, Class: sun.security.rsa.RSASignature$MD2withRSA
    Aliases: 1.2.840.113549.1.1.2
    Attributes:
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey
   Service: Signature, Algorithm: SHA224withRSA, Class: sun.security.rsa.RSASignature$SHA224withRSA
    Aliases: 1.2.840.113549.1.1.14
    Attributes:
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey

 Provider: SunEC, Version: 1.8, Class: sun.security.ec.SunEC
  Description: Sun Elliptic Curve provider (EC, ECDSA, ECDH)
  Services (10):
   Service: Signature, Algorithm: SHA512withECDSA, Class: sun.security.ec.ECDSASignature$SHA512
    Aliases: 1.2.840.10045.4.3.4
    Attributes:
      ImplementedIn: Software
      SupportedKeyClasses: java.security.interfaces.ECPublicKey|java.security.interfaces.ECPrivateKey
   Service: AlgorithmParameters, Algorithm: EC, Class: sun.security.ec.ECParameters
    Aliases: 1.2.840.10045.2.1
    Attributes:
      SupportedCurves: [secp112r1,1.3.132.0.6]|[secp112r2,1.3.132.0.7]|[secp128r1,1.3.132.0.28]|[secp128r2,1.3.132.0.29]|[secp160k1,1.3.132.0.9]|[secp160r1,1.3.132.0.8]|[secp160r2,1.3.132.0.30]|[secp192k1,1.3.132.0.31]|[secp192r1,NIST P-192,X9.62 prime192v1,1.2.840.10045.3.1.1]|[secp224k1,1.3.132.0.32]|[secp224r1,NIST P-224,1.3.132.0.33]|[secp256k1,1.3.132.0.10]|[secp256r1,NIST P-256,X9.62 prime256v1,1.2.840.10045.3.1.7]|[secp384r1,NIST P-384,1.3.132.0.34]|[secp521r1,NIST P-521,1.3.132.0.35]|[X9.62 prime192v2,1.2.840.10045.3.1.2]|[X9.62 prime192v3,1.2.840.10045.3.1.3]|[X9.62 prime239v1,1.2.840.10045.3.1.4]|[X9.62 prime239v2,1.2.840.10045.3.1.5]|[X9.62 prime239v3,1.2.840.10045.3.1.6]|[sect113r1,1.3.132.0.4]|[sect113r2,1.3.132.0.5]|[sect131r1,1.3.132.0.22]|[sect131r2,1.3.132.0.23]|[sect163k1,NIST K-163,1.3.132.0.1]|[sect163r1,1.3.132.0.2]|[sect163r2,NIST B-163,1.3.132.0.15]|[sect193r1,1.3.132.0.24]|[sect193r2,1.3.132.0.25]|[sect233k1,NIST K-233,1.3.132.0.26]|[sect233r1,NIST B-233,1.3.132.0.27]|[sect239k1,1.3.132.0.3]|[sect283k1,NIST K-283,1.3.132.0.16]|[sect283r1,NIST B-283,1.3.132.0.17]|[sect409k1,NIST K-409,1.3.132.0.36]|[sect409r1,NIST B-409,1.3.132.0.37]|[sect571k1,NIST K-571,1.3.132.0.38]|[sect571r1,NIST B-571,1.3.132.0.39]|[X9.62 c2tnb191v1,1.2.840.10045.3.0.5]|[X9.62 c2tnb191v2,1.2.840.10045.3.0.6]|[X9.62 c2tnb191v3,1.2.840.10045.3.0.7]|[X9.62 c2tnb239v1,1.2.840.10045.3.0.11]|[X9.62 c2tnb239v2,1.2.840.10045.3.0.12]|[X9.62 c2tnb239v3,1.2.840.10045.3.0.13]|[X9.62 c2tnb359v1,1.2.840.10045.3.0.18]|[X9.62 c2tnb431r1,1.2.840.10045.3.0.20]
      ImplementedIn: Software
      KeySize: 256
   Service: Signature, Algorithm: SHA384withECDSA, Class: sun.security.ec.ECDSASignature$SHA384
    Aliases: 1.2.840.10045.4.3.3
    Attributes:
      ImplementedIn: Software
      SupportedKeyClasses: java.security.interfaces.ECPublicKey|java.security.interfaces.ECPrivateKey
   Service: Signature, Algorithm: NONEwithECDSA, Class: sun.security.ec.ECDSASignature$Raw
    Attributes:
      ImplementedIn: Software
      SupportedKeyClasses: java.security.interfaces.ECPublicKey|java.security.interfaces.ECPrivateKey
   Service: Signature, Algorithm: SHA1withECDSA, Class: sun.security.ec.ECDSASignature$SHA1
    Aliases: 1.2.840.10045.4.1
    Attributes:
      ImplementedIn: Software
      KeySize: 256
      SupportedKeyClasses: java.security.interfaces.ECPublicKey|java.security.interfaces.ECPrivateKey
   Service: KeyPairGenerator, Algorithm: EC, Class: sun.security.ec.ECKeyPairGenerator
    Aliases: 1.2.840.10045.2.1
    Attributes:
      ImplementedIn: Software
      KeySize: 256
   Service: KeyFactory, Algorithm: EC, Class: sun.security.ec.ECKeyFactory
    Aliases: 1.2.840.10045.2.1
    Attributes:
      ImplementedIn: Software
   Service: KeyAgreement, Algorithm: ECDH, Class: sun.security.ec.ECDHKeyAgreement
    Attributes:
      ImplementedIn: Software
      SupportedKeyClasses: java.security.interfaces.ECPublicKey|java.security.interfaces.ECPrivateKey
   Service: Signature, Algorithm: SHA256withECDSA, Class: sun.security.ec.ECDSASignature$SHA256
    Aliases: 1.2.840.10045.4.3.2
    Attributes:
      ImplementedIn: Software
      SupportedKeyClasses: java.security.interfaces.ECPublicKey|java.security.interfaces.ECPrivateKey
   Service: Signature, Algorithm: SHA224withECDSA, Class: sun.security.ec.ECDSASignature$SHA224
    Aliases: 1.2.840.10045.4.3.1
    Attributes:
      ImplementedIn: Software
      SupportedKeyClasses: java.security.interfaces.ECPublicKey|java.security.interfaces.ECPrivateKey

 Provider: SunJSSE, Version: 1.8, Class: com.sun.net.ssl.internal.ssl.Provider
  Description: Sun JSSE provider(PKCS12, SunX509/PKIX key/trust factories, SSLv3/TLSv1/TLSv1.1/TLSv1.2)
  Services (16):
   Service: Signature, Algorithm: MD5andSHA1withRSA, Class: sun.security.ssl.RSASignature
   Service: SSLContext, Algorithm: Default, Class: sun.security.ssl.SSLContextImpl$DefaultSSLContext
   Service: KeyManagerFactory, Algorithm: SunX509, Class: sun.security.ssl.KeyManagerFactoryImpl$SunX509
   Service: Signature, Algorithm: MD5withRSA, Class: sun.security.rsa.RSASignature$MD5withRSA
    Aliases: OID.1.2.840.113549.1.1.4
   Service: Signature, Algorithm: SHA1withRSA, Class: sun.security.rsa.RSASignature$SHA1withRSA
    Aliases: OID.1.2.840.113549.1.1.5
   Service: KeyFactory, Algorithm: RSA, Class: sun.security.rsa.RSAKeyFactory
    Aliases: 1.2.840.113549.1.1
   Service: TrustManagerFactory, Algorithm: SunX509, Class: sun.security.ssl.TrustManagerFactoryImpl$SimpleFactory
   Service: KeyStore, Algorithm: PKCS12, Class: sun.security.pkcs12.PKCS12KeyStore
   Service: SSLContext, Algorithm: TLS, Class: sun.security.ssl.SSLContextImpl$TLSContext
    Aliases: SSL
   Service: KeyPairGenerator, Algorithm: RSA, Class: sun.security.rsa.RSAKeyPairGenerator
    Aliases: 1.2.840.113549.1.1
   Service: SSLContext, Algorithm: TLSv1, Class: sun.security.ssl.SSLContextImpl$TLS10Context
    Aliases: SSLv3
   Service: Signature, Algorithm: MD2withRSA, Class: sun.security.rsa.RSASignature$MD2withRSA
    Aliases: 1.2.840.113549.1.1.2
   Service: SSLContext, Algorithm: TLSv1.2, Class: sun.security.ssl.SSLContextImpl$TLS12Context
   Service: KeyManagerFactory, Algorithm: NewSunX509, Class: sun.security.ssl.KeyManagerFactoryImpl$X509
    Aliases: PKIX
   Service: SSLContext, Algorithm: TLSv1.1, Class: sun.security.ssl.SSLContextImpl$TLS11Context
   Service: TrustManagerFactory, Algorithm: PKIX, Class: sun.security.ssl.TrustManagerFactoryImpl$PKIXFactory
    Aliases: X509

 Provider: SunJCE, Version: 1.8, Class: com.sun.crypto.provider.SunJCE
  Description: SunJCE Provider (implements RSA, DES, Triple DES, AES, Blowfish, ARCFOUR, RC2, PBE, Diffie-Hellman, HMAC)
  Services (131):
   Service: SecretKeyFactory, Algorithm: PBKDF2WithHmacSHA512, Class: com.sun.crypto.provider.PBKDF2Core$HmacSHA512
   Service: KeyGenerator, Algorithm: Blowfish, Class: com.sun.crypto.provider.BlowfishKeyGenerator
   Service: Mac, Algorithm: HmacPBESHA1, Class: com.sun.crypto.provider.HmacPKCS12PBESHA1
    Attributes:
      SupportedKeyFormats: RAW
   Service: KeyGenerator, Algorithm: HmacSHA512, Class: com.sun.crypto.provider.KeyGeneratorCore$HmacSHA2KG$SHA512
    Aliases: 1.2.840.113549.2.11
   Service: AlgorithmParameters, Algorithm: GCM, Class: com.sun.crypto.provider.GCMParameters
   Service: Cipher, Algorithm: PBEWithHmacSHA1AndAES_128, Class: com.sun.crypto.provider.PBES2Core$HmacSHA1AndAES_128
   Service: KeyGenerator, Algorithm: SunTlsMasterSecret, Class: com.sun.crypto.provider.TlsMasterSecretGenerator
    Aliases: SunTls12MasterSecret
   Service: AlgorithmParameters, Algorithm: PBES2, Class: com.sun.crypto.provider.PBES2Parameters$General
    Aliases: 1.2.840.113549.1.5.13
   Service: Cipher, Algorithm: DES, Class: com.sun.crypto.provider.DESCipher
    Attributes:
      SupportedKeyFormats: RAW
      SupportedPaddings: NOPADDING|PKCS5PADDING|ISO10126PADDING
      SupportedModes: ECB|CBC|PCBC|CTR|CTS|CFB|OFB|CFB8|CFB16|CFB24|CFB32|CFB40|CFB48|CFB56|CFB64|OFB8|OFB16|OFB24|OFB32|OFB40|OFB48|OFB56|OFB64
   Service: Cipher, Algorithm: AES_192/CBC/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES192_CBC_NoPadding
    Aliases: OID.2.16.840.1.101.3.4.1.22
   Service: Cipher, Algorithm: Blowfish, Class: com.sun.crypto.provider.BlowfishCipher
    Attributes:
      SupportedKeyFormats: RAW
      SupportedPaddings: NOPADDING|PKCS5PADDING|ISO10126PADDING
      SupportedModes: ECB|CBC|PCBC|CTR|CTS|CFB|OFB|CFB8|CFB16|CFB24|CFB32|CFB40|CFB48|CFB56|CFB64|OFB8|OFB16|OFB24|OFB32|OFB40|OFB48|OFB56|OFB64
   Service: SecretKeyFactory, Algorithm: PBKDF2WithHmacSHA1, Class: com.sun.crypto.provider.PBKDF2Core$HmacSHA1
    Aliases: 1.2.840.113549.1.5.12
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA512AndAES_128, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA512AndAES_128
   Service: AlgorithmParameters, Algorithm: PBEWithMD5AndTripleDES, Class: com.sun.crypto.provider.PBEParameters
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA384AndAES_128, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA384AndAES_128
   Service: AlgorithmParameters, Algorithm: PBEWithSHA1AndRC2_40, Class: com.sun.crypto.provider.PBEParameters
    Aliases: 1.2.840.113549.1.12.1.6
   Service: Cipher, Algorithm: PBEWithHmacSHA256AndAES_128, Class: com.sun.crypto.provider.PBES2Core$HmacSHA256AndAES_128
   Service: Cipher, Algorithm: RC2, Class: com.sun.crypto.provider.RC2Cipher
    Attributes:
      SupportedPaddings: NOPADDING|PKCS5PADDING|ISO10126PADDING
      SupportedKeyFormats: RAW
      SupportedModes: ECB|CBC|PCBC|CTR|CTS|CFB|OFB|CFB8|CFB16|CFB24|CFB32|CFB40|CFB48|CFB56|CFB64|OFB8|OFB16|OFB24|OFB32|OFB40|OFB48|OFB56|OFB64
   Service: Cipher, Algorithm: AES_256/OFB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES256_OFB_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.43
   Service: AlgorithmParameters, Algorithm: PBEWithSHA1AndDESede, Class: com.sun.crypto.provider.PBEParameters
    Aliases: 1.2.840.113549.1.12.1.3
   Service: Cipher, Algorithm: AES_128/GCM/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES128_GCM_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.6
   Service: AlgorithmParameters, Algorithm: PBEWithSHA1AndRC4_128, Class: com.sun.crypto.provider.PBEParameters
    Aliases: 1.2.840.113549.1.12.1.1
   Service: Cipher, Algorithm: PBEWithHmacSHA224AndAES_256, Class: com.sun.crypto.provider.PBES2Core$HmacSHA224AndAES_256
   Service: KeyGenerator, Algorithm: HmacSHA1, Class: com.sun.crypto.provider.HmacSHA1KeyGenerator
    Aliases: OID.1.2.840.113549.2.7
   Service: Cipher, Algorithm: AES, Class: com.sun.crypto.provider.AESCipher$General
    Aliases: Rijndael
    Attributes:
      SupportedKeyFormats: RAW
      SupportedPaddings: NOPADDING|PKCS5PADDING|ISO10126PADDING
      SupportedModes: ECB|CBC|PCBC|CTR|CTS|CFB|OFB|CFB8|CFB16|CFB24|CFB32|CFB40|CFB48|CFB56|CFB64|OFB8|OFB16|OFB24|OFB32|OFB40|OFB48|OFB56|OFB64|GCM|CFB72|CFB80|CFB88|CFB96|CFB104|CFB112|CFB120|CFB128|OFB72|OFB80|OFB88|OFB96|OFB104|OFB112|OFB120|OFB128
   Service: AlgorithmParameters, Algorithm: PBEWithSHA1AndRC4_40, Class: com.sun.crypto.provider.PBEParameters
    Aliases: 1.2.840.113549.1.12.1.2
   Service: Mac, Algorithm: HmacSHA384, Class: com.sun.crypto.provider.HmacCore$HmacSHA384
    Aliases: 1.2.840.113549.2.10
    Attributes:
      SupportedKeyFormats: RAW
   Service: Cipher, Algorithm: DESede, Class: com.sun.crypto.provider.DESedeCipher
    Aliases: TripleDES
    Attributes:
      SupportedKeyFormats: RAW
      SupportedPaddings: NOPADDING|PKCS5PADDING|ISO10126PADDING
      SupportedModes: ECB|CBC|PCBC|CTR|CTS|CFB|OFB|CFB8|CFB16|CFB24|CFB32|CFB40|CFB48|CFB56|CFB64|OFB8|OFB16|OFB24|OFB32|OFB40|OFB48|OFB56|OFB64
   Service: Mac, Algorithm: HmacSHA224, Class: com.sun.crypto.provider.HmacCore$HmacSHA224
    Aliases: OID.1.2.840.113549.2.8
    Attributes:
      SupportedKeyFormats: RAW
   Service: KeyFactory, Algorithm: DiffieHellman, Class: com.sun.crypto.provider.DHKeyFactory
    Aliases: 1.2.840.113549.1.3.1
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA384AndAES_256, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA384AndAES_256
   Service: Cipher, Algorithm: AES_256/CFB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES256_CFB_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.44
   Service: Cipher, Algorithm: PBEWithMD5AndDES, Class: com.sun.crypto.provider.PBEWithMD5AndDESCipher
    Aliases: 1.2.840.113549.1.5.3
   Service: AlgorithmParameters, Algorithm: DESede, Class: com.sun.crypto.provider.DESedeParameters
    Aliases: TripleDES
   Service: Cipher, Algorithm: PBEWithHmacSHA512AndAES_256, Class: com.sun.crypto.provider.PBES2Core$HmacSHA512AndAES_256
   Service: Mac, Algorithm: HmacSHA512, Class: com.sun.crypto.provider.HmacCore$HmacSHA512
    Aliases: 1.2.840.113549.2.11
    Attributes:
      SupportedKeyFormats: RAW
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA256AndAES_256, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA256AndAES_256
   Service: Cipher, Algorithm: AES_128/CBC/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES128_CBC_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.2
   Service: Cipher, Algorithm: AES_256/ECB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES256_ECB_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.41
   Service: SecretKeyFactory, Algorithm: PBEWithSHA1AndRC4_128, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithSHA1AndRC4_128
    Aliases: 1.2.840.113549.1.12.1.1
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA1AndAES_128, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA1AndAES_128
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA256AndAES_128, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA256AndAES_128
   Service: Mac, Algorithm: HmacMD5, Class: com.sun.crypto.provider.HmacMD5
    Attributes:
      SupportedKeyFormats: RAW
   Service: Cipher, Algorithm: AESWrap_192, Class: com.sun.crypto.provider.AESWrapCipher$AES192
    Aliases: OID.2.16.840.1.101.3.4.1.25
   Service: Mac, Algorithm: SslMacMD5, Class: com.sun.crypto.provider.SslMacCore$SslMacMD5
    Attributes:
      SupportedKeyFormats: RAW
   Service: Mac, Algorithm: HmacSHA1, Class: com.sun.crypto.provider.HmacSHA1
    Aliases: OID.1.2.840.113549.2.7
    Attributes:
      SupportedKeyFormats: RAW
   Service: KeyGenerator, Algorithm: DES, Class: com.sun.crypto.provider.DESKeyGenerator
   Service: Mac, Algorithm: SslMacSHA1, Class: com.sun.crypto.provider.SslMacCore$SslMacSHA1
    Attributes:
      SupportedKeyFormats: RAW
   Service: Cipher, Algorithm: PBEWithMD5AndTripleDES, Class: com.sun.crypto.provider.PBEWithMD5AndTripleDESCipher
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA224AndAES_128, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA224AndAES_128
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA224AndAES_256, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA224AndAES_256
   Service: Mac, Algorithm: PBEWithHmacSHA384, Class: com.sun.crypto.provider.PBMAC1Core$HmacSHA384
    Attributes:
      SupportedKeyFormats: RAW
   Service: SecretKeyFactory, Algorithm: DES, Class: com.sun.crypto.provider.DESKeyFactory
   Service: Mac, Algorithm: PBEWithHmacSHA224, Class: com.sun.crypto.provider.PBMAC1Core$HmacSHA224
    Attributes:
      SupportedKeyFormats: RAW
   Service: KeyGenerator, Algorithm: RC2, Class: com.sun.crypto.provider.KeyGeneratorCore$RC2KeyGenerator
   Service: SecretKeyFactory, Algorithm: PBKDF2WithHmacSHA256, Class: com.sun.crypto.provider.PBKDF2Core$HmacSHA256
   Service: Cipher, Algorithm: AES_256/GCM/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES256_GCM_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.46
   Service: Cipher, Algorithm: PBEWithHmacSHA384AndAES_128, Class: com.sun.crypto.provider.PBES2Core$HmacSHA384AndAES_128
   Service: SecretKeyFactory, Algorithm: DESede, Class: com.sun.crypto.provider.DESedeKeyFactory
    Aliases: TripleDES
   Service: Cipher, Algorithm: ARCFOUR, Class: com.sun.crypto.provider.ARCFOURCipher
    Aliases: RC4
    Attributes:
      SupportedKeyFormats: RAW
      SupportedPaddings: NOPADDING
      SupportedModes: ECB
   Service: Cipher, Algorithm: AESWrap_128, Class: com.sun.crypto.provider.AESWrapCipher$AES128
    Aliases: 2.16.840.1.101.3.4.1.5
   Service: KeyGenerator, Algorithm: AES, Class: com.sun.crypto.provider.AESKeyGenerator
    Aliases: Rijndael
   Service: KeyGenerator, Algorithm: HmacSHA256, Class: com.sun.crypto.provider.KeyGeneratorCore$HmacSHA2KG$SHA256
    Aliases: OID.1.2.840.113549.2.9
   Service: Mac, Algorithm: PBEWithHmacSHA512, Class: com.sun.crypto.provider.PBMAC1Core$HmacSHA512
    Attributes:
      SupportedKeyFormats: RAW
   Service: KeyGenerator, Algorithm: SunTls12Prf, Class: com.sun.crypto.provider.TlsPrfGenerator$V12
   Service: Cipher, Algorithm: RSA, Class: com.sun.crypto.provider.RSACipher
    Attributes:
      SupportedPaddings: NOPADDING|PKCS1PADDING|OAEPPADDING|OAEPWITHMD5ANDMGF1PADDING|OAEPWITHSHA1ANDMGF1PADDING|OAEPWITHSHA-1ANDMGF1PADDING|OAEPWITHSHA-224ANDMGF1PADDING|OAEPWITHSHA-256ANDMGF1PADDING|OAEPWITHSHA-384ANDMGF1PADDING|OAEPWITHSHA-512ANDMGF1PADDING
      SupportedModes: ECB
      SupportedKeyClasses: java.security.interfaces.RSAPublicKey|java.security.interfaces.RSAPrivateKey
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA512AndAES_128, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA512AndAES_128
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA1AndAES_128, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA1AndAES_128
   Service: Cipher, Algorithm: PBEWithSHA1AndRC4_128, Class: com.sun.crypto.provider.PKCS12PBECipherCore$PBEWithSHA1AndRC4_128
    Aliases: 1.2.840.113549.1.12.1.1
   Service: KeyGenerator, Algorithm: ARCFOUR, Class: com.sun.crypto.provider.KeyGeneratorCore$ARCFOURKeyGenerator
    Aliases: RC4
   Service: Cipher, Algorithm: PBEWithHmacSHA1AndAES_256, Class: com.sun.crypto.provider.PBES2Core$HmacSHA1AndAES_256
   Service: AlgorithmParameters, Algorithm: PBEWithSHA1AndRC2_128, Class: com.sun.crypto.provider.PBEParameters
    Aliases: 1.2.840.113549.1.12.1.5
   Service: KeyGenerator, Algorithm: SunTlsPrf, Class: com.sun.crypto.provider.TlsPrfGenerator$V10
   Service: AlgorithmParameters, Algorithm: DiffieHellman, Class: com.sun.crypto.provider.DHParameters
    Aliases: 1.2.840.113549.1.3.1
   Service: Mac, Algorithm: PBEWithHmacSHA1, Class: com.sun.crypto.provider.PBMAC1Core$HmacSHA1
    Attributes:
      SupportedKeyFormatS: RAW
   Service: KeyGenerator, Algorithm: HmacMD5, Class: com.sun.crypto.provider.HmacMD5KeyGenerator
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA512AndAES_256, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA512AndAES_256
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA384AndAES_256, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA384AndAES_256
   Service: Cipher, Algorithm: PBEWithHmacSHA256AndAES_256, Class: com.sun.crypto.provider.PBES2Core$HmacSHA256AndAES_256
   Service: Cipher, Algorithm: AESWrap, Class: com.sun.crypto.provider.AESWrapCipher$General
    Attributes:
      SupportedPaddings: NOPADDING
      SupportedKeyFormats: RAW
      SupportedModes: ECB
   Service: AlgorithmParameters, Algorithm: OAEP, Class: com.sun.crypto.provider.OAEPParameters
   Service: SecretKeyFactory, Algorithm: PBEWithSHA1AndRC2_40, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithSHA1AndRC2_40
    Aliases: 1.2.840.113549.1.12.1.6
   Service: Cipher, Algorithm: AES_192/CFB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES192_CFB_NoPadding
    Aliases: OID.2.16.840.1.101.3.4.1.24
   Service: Cipher, Algorithm: AES_192/OFB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES192_OFB_NoPadding
    Aliases: OID.2.16.840.1.101.3.4.1.23
   Service: Cipher, Algorithm: PBEWithSHA1AndRC2_40, Class: com.sun.crypto.provider.PKCS12PBECipherCore$PBEWithSHA1AndRC2_40
    Aliases: 1.2.840.113549.1.12.1.6
   Service: Cipher, Algorithm: PBEWithHmacSHA224AndAES_128, Class: com.sun.crypto.provider.PBES2Core$HmacSHA224AndAES_128
   Service: KeyGenerator, Algorithm: SunTlsKeyMaterial, Class: com.sun.crypto.provider.TlsKeyMaterialGenerator
    Aliases: SunTls12KeyMaterial
   Service: SecretKeyFactory, Algorithm: PBEWithSHA1AndDESede, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithSHA1AndDESede
    Aliases: 1.2.840.113549.1.12.1.3
   Service: Cipher, Algorithm: AES_256/CBC/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES256_CBC_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.42
   Service: KeyPairGenerator, Algorithm: DiffieHellman, Class: com.sun.crypto.provider.DHKeyPairGenerator
    Aliases: 1.2.840.113549.1.3.1
   Service: SecretKeyFactory, Algorithm: PBEWithSHA1AndRC2_128, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithSHA1AndRC2_128
    Aliases: 1.2.840.113549.1.12.1.5
   Service: Cipher, Algorithm: PBEWithSHA1AndDESede, Class: com.sun.crypto.provider.PKCS12PBECipherCore$PBEWithSHA1AndDESede
    Aliases: 1.2.840.113549.1.12.1.3
   Service: SecretKeyFactory, Algorithm: PBEWithSHA1AndRC4_40, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithSHA1AndRC4_40
    Aliases: 1.2.840.113549.1.12.1.2
   Service: Mac, Algorithm: HmacSHA256, Class: com.sun.crypto.provider.HmacCore$HmacSHA256
    Aliases: OID.1.2.840.113549.2.9
    Attributes:
      SupportedKeyFormats: RAW
   Service: Cipher, Algorithm: AES_192/ECB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES192_ECB_NoPadding
    Aliases: OID.2.16.840.1.101.3.4.1.21
   Service: Cipher, Algorithm: PBEWithSHA1AndRC4_40, Class: com.sun.crypto.provider.PKCS12PBECipherCore$PBEWithSHA1AndRC4_40
    Aliases: 1.2.840.113549.1.12.1.2
   Service: AlgorithmParameters, Algorithm: PBEWithMD5AndDES, Class: com.sun.crypto.provider.PBEParameters
    Aliases: 1.2.840.113549.1.5.3
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA384AndAES_128, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA384AndAES_128
   Service: AlgorithmParameters, Algorithm: DES, Class: com.sun.crypto.provider.DESParameters
   Service: KeyAgreement, Algorithm: DiffieHellman, Class: com.sun.crypto.provider.DHKeyAgreement
    Aliases: 1.2.840.113549.1.3.1
    Attributes:
      SupportedKeyClasses: javax.crypto.interfaces.DHPublicKey|javax.crypto.interfaces.DHPrivateKey
   Service: Cipher, Algorithm: PBEWithHmacSHA512AndAES_128, Class: com.sun.crypto.provider.PBES2Core$HmacSHA512AndAES_128
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA256AndAES_128, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA256AndAES_128
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA1AndAES_256, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA1AndAES_256
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA256AndAES_256, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA256AndAES_256
   Service: AlgorithmParameters, Algorithm: RC2, Class: com.sun.crypto.provider.RC2Parameters
   Service: AlgorithmParameterGenerator, Algorithm: DiffieHellman, Class: com.sun.crypto.provider.DHParameterGenerator
    Aliases: 1.2.840.113549.1.3.1
   Service: KeyGenerator, Algorithm: SunTlsRsaPremasterSecret, Class: com.sun.crypto.provider.TlsRsaPremasterSecretGenerator
    Aliases: SunTls12RsaPremasterSecret
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA224AndAES_256, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA224AndAES_256
   Service: AlgorithmParameters, Algorithm: AES, Class: com.sun.crypto.provider.AESParameters
    Aliases: Rijndael
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA224AndAES_128, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA224AndAES_128
   Service: Cipher, Algorithm: AES_128/CFB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES128_CFB_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.4
   Service: Mac, Algorithm: PBEWithHmacSHA256, Class: com.sun.crypto.provider.PBMAC1Core$HmacSHA256
    Attributes:
      SupportedKeyFormats: RAW
   Service: Cipher, Algorithm: PBEWithSHA1AndRC2_128, Class: com.sun.crypto.provider.PKCS12PBECipherCore$PBEWithSHA1AndRC2_128
    Aliases: 1.2.840.113549.1.12.1.5
   Service: Cipher, Algorithm: AES_128/OFB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES128_OFB_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.3
   Service: SecretKeyFactory, Algorithm: PBEWithMD5AndTripleDES, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithMD5AndTripleDES
   Service: SecretKeyFactory, Algorithm: PBEWithMD5AndDES, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithMD5AndDES
    Aliases: 1.2.840.113549.1.5.3
   Service: SecretKeyFactory, Algorithm: PBKDF2WithHmacSHA384, Class: com.sun.crypto.provider.PBKDF2Core$HmacSHA384
   Service: SecretKeyFactory, Algorithm: PBKDF2WithHmacSHA224, Class: com.sun.crypto.provider.PBKDF2Core$HmacSHA224
   Service: Cipher, Algorithm: PBEWithHmacSHA384AndAES_256, Class: com.sun.crypto.provider.PBES2Core$HmacSHA384AndAES_256
   Service: Cipher, Algorithm: AES_128/ECB/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES128_ECB_NoPadding
    Aliases: 2.16.840.1.101.3.4.1.1
   Service: Cipher, Algorithm: AESWrap_256, Class: com.sun.crypto.provider.AESWrapCipher$AES256
    Aliases: 2.16.840.1.101.3.4.1.45
   Service: KeyGenerator, Algorithm: HmacSHA384, Class: com.sun.crypto.provider.KeyGeneratorCore$HmacSHA2KG$SHA384
    Aliases: 1.2.840.113549.2.10
   Service: KeyGenerator, Algorithm: HmacSHA224, Class: com.sun.crypto.provider.KeyGeneratorCore$HmacSHA2KG$SHA224
    Aliases: OID.1.2.840.113549.2.8
   Service: Cipher, Algorithm: DESedeWrap, Class: com.sun.crypto.provider.DESedeWrapCipher
    Attributes:
      SupportedPaddings: NOPADDING
      SupportedKeyFormats: RAW
      SupportedModes: CBC
   Service: KeyStore, Algorithm: JCEKS, Class: com.sun.crypto.provider.JceKeyStore
   Service: Cipher, Algorithm: AES_192/GCM/NoPadding, Class: com.sun.crypto.provider.AESCipher$AES192_GCM_NoPadding
    Aliases: OID.2.16.840.1.101.3.4.1.26
   Service: AlgorithmParameters, Algorithm: PBE, Class: com.sun.crypto.provider.PBEParameters
   Service: AlgorithmParameters, Algorithm: Blowfish, Class: com.sun.crypto.provider.BlowfishParameters
   Service: SecretKeyFactory, Algorithm: PBEWithHmacSHA512AndAES_256, Class: com.sun.crypto.provider.PBEKeyFactory$PBEWithHmacSHA512AndAES_256
   Service: KeyGenerator, Algorithm: DESede, Class: com.sun.crypto.provider.DESedeKeyGenerator
    Aliases: TripleDES
   Service: AlgorithmParameters, Algorithm: PBEWithHmacSHA1AndAES_256, Class: com.sun.crypto.provider.PBES2Parameters$HmacSHA1AndAES_256

 Provider: SunJGSS, Version: 1.8, Class: sun.security.jgss.SunProvider
  Description: Sun (Kerberos v5, SPNEGO)
  Services (2):
   Service: GssApiMechanism, Algorithm: 1.3.6.1.5.5.2, Class: sun.security.jgss.spnego.SpNegoMechFactory
   Service: GssApiMechanism, Algorithm: 1.2.840.113554.1.2.2, Class: sun.security.jgss.krb5.Krb5MechFactory

 Provider: SunSASL, Version: 1.8, Class: com.sun.security.sasl.Provider
  Description: Sun SASL provider(implements client mechanisms for: DIGEST-MD5, GSSAPI, EXTERNAL, PLAIN, CRAM-MD5, NTLM; server mechanisms for: DIGEST-MD5, GSSAPI, CRAM-MD5, NTLM)
  Services (10):
   Service: SaslClientFactory, Algorithm: NTLM, Class: com.sun.security.sasl.ntlm.FactoryImpl
   Service: SaslClientFactory, Algorithm: CRAM-MD5, Class: com.sun.security.sasl.ClientFactoryImpl
   Service: SaslClientFactory, Algorithm: EXTERNAL, Class: com.sun.security.sasl.ClientFactoryImpl
   Service: SaslClientFactory, Algorithm: DIGEST-MD5, Class: com.sun.security.sasl.digest.FactoryImpl
   Service: SaslClientFactory, Algorithm: PLAIN, Class: com.sun.security.sasl.ClientFactoryImpl
   Service: SaslServerFactory, Algorithm: NTLM, Class: com.sun.security.sasl.ntlm.FactoryImpl
   Service: SaslClientFactory, Algorithm: GSSAPI, Class: com.sun.security.sasl.gsskerb.FactoryImpl
   Service: SaslServerFactory, Algorithm: CRAM-MD5, Class: com.sun.security.sasl.ServerFactoryImpl
   Service: SaslServerFactory, Algorithm: DIGEST-MD5, Class: com.sun.security.sasl.digest.FactoryImpl
   Service: SaslServerFactory, Algorithm: GSSAPI, Class: com.sun.security.sasl.gsskerb.FactoryImpl

 Provider: XMLDSig, Version: 1.8, Class: org.jcp.xml.dsig.internal.dom.XMLDSigRI
  Description: XMLDSig (DOM XMLSignatureFactory; DOM KeyInfoFactory; C14N 1.0, C14N 1.1, Exclusive C14N, Base64, Enveloped, XPath, XPath2, XSLT TransformServices)
  Services (13):
   Service: KeyInfoFactory, Algorithm: DOM, Class: org.jcp.xml.dsig.internal.dom.DOMKeyInfoFactory
   Service: TransformService, Algorithm: http://www.w3.org/TR/1999/REC-xpath-19991116, Class: org.jcp.xml.dsig.internal.dom.DOMXPathTransform
    Aliases: XPATH
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/TR/2001/REC-xml-c14n-20010315#WithComments, Class: org.jcp.xml.dsig.internal.dom.DOMCanonicalXMLC14NMethod
    Aliases: INCLUSIVE_WITH_COMMENTS
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/2000/09/xmldsig#base64, Class: org.jcp.xml.dsig.internal.dom.DOMBase64Transform
    Aliases: BASE64
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/2000/09/xmldsig#enveloped-signature, Class: org.jcp.xml.dsig.internal.dom.DOMEnvelopedTransform
    Aliases: ENVELOPED
    Attributes:
      MechanismType: DOM
   Service: XMLSignatureFactory, Algorithm: DOM, Class: org.jcp.xml.dsig.internal.dom.DOMXMLSignatureFactory
   Service: TransformService, Algorithm: http://www.w3.org/TR/2001/REC-xml-c14n-20010315, Class: org.jcp.xml.dsig.internal.dom.DOMCanonicalXMLC14NMethod
    Aliases: INCLUSIVE
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/2002/06/xmldsig-filter2, Class: org.jcp.xml.dsig.internal.dom.DOMXPathFilter2Transform
    Aliases: XPATH2
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/2001/10/xml-exc-c14n#, Class: org.jcp.xml.dsig.internal.dom.DOMExcC14NMethod
    Aliases: EXCLUSIVE
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/TR/1999/REC-xslt-19991116, Class: org.jcp.xml.dsig.internal.dom.DOMXSLTTransform
    Aliases: XSLT
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/2006/12/xml-c14n11#WithComments, Class: org.jcp.xml.dsig.internal.dom.DOMCanonicalXMLC14N11Method
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/2001/10/xml-exc-c14n#WithComments, Class: org.jcp.xml.dsig.internal.dom.DOMExcC14NMethod
    Aliases: EXCLUSIVE_WITH_COMMENTS
    Attributes:
      MechanismType: DOM
   Service: TransformService, Algorithm: http://www.w3.org/2006/12/xml-c14n11, Class: org.jcp.xml.dsig.internal.dom.DOMCanonicalXMLC14N11Method
    Attributes:
      MechanismType: DOM

 Provider: SunPCSC, Version: 1.8, Class: sun.security.smartcardio.SunPCSC
  Description: Sun PC/SC provider
  Services (1):
   Service: TerminalFactory, Algorithm: PC/SC, Class: sun.security.smartcardio.SunPCSC$Factory

 Provider: Apple, Version: 1.8, Class: apple.security.AppleProvider
  Description: Apple Provider
  Services (1):
   Service: KeyStore, Algorithm: KeychainStore, Class: apple.security.KeychainStore
```
