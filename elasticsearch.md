# Notes

Much of the initial take on this topic is coming from *Elasticsearch:
The Definitive Guide* from O'Reilly.

## Overview

Elasticsearch is a distributed document store; it stores/retrieves
complex data structures serialized as JSON documents in real time.

All data in every field in a document is indexed by default.

## Vocabulary

**node** -- A running instance of Elasticsearch. 

**cluster** -- A group of *nodes* with the same `cluster.name` working
together to share data and provide failover and scale.

**master node** -- One node in the cluster which manages cluster-wide
changes.

**Index (n)** -- A place to store related documents. Technically a
logical namespace that points to one or more physical *shards*. The
number of primary shards is fixed at index creation.

**Index (v)** -- To store a document in an index so it can be
retrieved and querried. Like an `INSERT` in SQL. Indexing replaces
existing copies with new copies.

**Inverted Index** -- an index (like a B-Tree index in Relational)
that allows searching and improves search speeds. Fields without an
inverted index are not searchable.

**shards** -- conatiners into which documents are partitioned which
can be spread across multiple nodes. These are balanced across the
nodes in a cluster to spread the indexing and search load. These are
also duplicated to provide redundancy. Technically a single instances
of Lucene, so each shard is a complete search engine in itself. Shards
can be *primary* or *replica*. Each document belongs to a single
primary shard. Replicas are just copies of primary shards.

**Document** -- a top-level, or root object that is serialized into
JSON and stored in Elasticsearch under a unique ID. Consists of both
data and metadata fields. Documments are **immutable**; udating an
existing document is done by reindexing or replacing it.

I found this diagram to be useful:

```
Relational DB => Databases => Tables => Rows      => Columns.
Elasticsearch => Indices   => Types  => Documents => Fields.
```

A *cluster* can contain multiple *indices* which in turn contain
multipe *types* which hold multiple *documents* each having multiple
*fields*.

Index is **highly overloaded** in Elasticsearch.

## Behavior

Users may talk to any node in the cluster; each node knows where each
document lives and can forward the request to the nodes that hold the
data. The node communicated with manages the process of gathering up
the response to return to the user.

Because each shard is a full search engine, you can horizontally scale
your cluster so that each shard is on a single machine and it will
consume all the resources.
