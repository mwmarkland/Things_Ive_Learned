# Introduction

Although entitled *Hadoop* this file contains a bunch of information
about cluster setup, especially using Ambari, and other general tools
in the Hadoop stack.

## Ambari hints/tips

- Client installs from Ambari simply do the regular "package manager"
  installs under teh covers.

- Use PostgreSQL. Additionally, make sure Ambari uses your installed
  PostgreSQL instance. *Installing using the silent option on the
  Ambari server install probably won't use your previously installed
  database but instead install its own.*
  
- When starting services in Ambari "manually" order matters. *Start
  ALL* should work as expected. If spinning things up manually you
  should always start with **Zookeeper** followed by **HDFS** followed
  by **YARN**. After that, order is less important. Getting those
  setup first ensures that the underlying infrastructure needed by
  other components is there and running.

- A service check passing in Ambari doesn't mean things are actually working.

- Install the Ambari Metrics packages.

## Namenodes

- If the NameNode RPC value (visible in the GUI) gets slow, it can
  hose the whole cluster.

- Heap on a NameNode should be 9-16Gb by default. Watch the GC times.

## YARN

- NodeManagers spin off commands. Non-kerberized jobs run as **yarn** linux user. Kerberized jobs run as the user who submitted them.

## Sqoop

- Ensure JDBC drivers for all DB types are on every node.

## Hive

Complicated piece:  SQL abstraction for Hadoop.

An underlying database (preferably PostgreSQL) stores the underlying metadata. The *Hive Metastore* lies between the user and the the database. Required for things to work.

- **Hive CLI** is a fat client. Only needs the metastore and the database. This means it is a security problem; can override all configuration parameters. **TURN THIS OFF!!**

- **HiveServer2**: jdbc, odbc work. Use **beeline** CLI. [Note](http://blog.cloudera.com/blog/2014/02/migrating-from-hive-cli-to-beeline-a-primer/).


## HCat (HCatalog)

Used by HUE and some other stuff. Builds on top of Hive Metastore.

## HBase

- Stable project with lots of knobs. 
- HBase UI very important.
- Requires Zookeeper.
- **Heap is usually key knob.** OS page cache use. Wants lots of RAM.
- Stick with the defaults to start!
- Database needs to be HA.

## Spark 

- Purely client side. Can install multiple versions easily as the code is moved about to the execution environment.

## realmd

Good choice for Active Directory integration.

## Security

### Kerberos

**ALL OR NOTHING**. All secure or nothing is secure.

Key is where the KPC lives (AD is one spot).

Need LDAP.

Need an administrator account.

LDAP needs Java CA certs, have to add LDAP AD SSL cert.

#### When setting up kerberos-env:
- Use **aes-only** encryption type.

- Don't let Ambari install or modify if you are using a third-party tool (i.e. *Centrify*).

- Make sure you match the password parameters to your organizations parameters.

- Check enable case insensitive username rules.

#### When setting up krb5-conf

- uncheck manage krb5-conf if you have something else.

**Dependency between NameNode HA and Kerberos -- MUST HAVE HA NAMENODE FIRST!**





