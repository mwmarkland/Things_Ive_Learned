# Kafka

## Input from a file/shell script to a kafka producer.
This is just a preliminary idea.
```
Well, based on the link you gave on how to use the shell kafka producer with an input file, you can do the same with your output. You can redirect the output to a file and then use the producer. 
Pay attention that I used >> in order to append to the file and not to overwrite it.
For example:
#!/bin/bash
FILES=/path/to/*
for f in $FILES
do
  tcpdump -r netflow.pcap >> /tmp/tcpdump_output.txt
done
kafka-console-produce.sh --broker-list localhost:9092 --topic my_topic
--new-producer < /tmp/tcpdump_output.txt
```
