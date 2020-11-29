# SF Crime Statistics with Spark Streaming

## Objective
In this project, using a real-world dataset, extracted from Kaggle, on San Francisco crime incidents, and statistical analyses of the data will be made using Apache Spark Structured Streaming. 

## Running and Testing
Starting Zookeeper and Kafka server.

* /usr/bin/zookeeper-server-start config/zookeeper.properties
* /usr/bin/kafka-server-start config/server.properties`

Start producer_server.py and kafka_server.py:

* python producer_server.py   
* python kafka_server.py

To teste kafka server, 3 commands were tried, but none has worked. Results on log folder.