# Useful commands

`hadoop fs -getmerge <src> <localdst>` concatenates the files in the source directory into a single file in the destination.

`zcat <file.gz> | hdfs dfs -put - file.txt` will put the uncompressed output of `<file.gz>` into HDFS as `file.txt`.

