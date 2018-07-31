> [Code on Git](https://github.com/vivek-bombatkar/ELK-Stack)


## 1. Theory
The ELK Stack is a collection of three open-source products — Elasticsearch, Logstash, and Kibana — from Elastic. 

E. Elasticsearch is a NoSQL database that is based on the Lucene search engine. 

L. Logstash is a log pipeline tool that accepts inputs from various sources, executes different transformations, and exports the data to various targets. 

K. Kibana is a visualization layer that works on top of Elasticsearch.


### Elasticsearch concept 

It's a java program which store a indexed data so that it can used for text based searches. 

- Elasticsearch stores data as document / JSON , like rows in RDBMS and this data is 'indexed'.

- document type  is like a table

- index is like a schema database

- shard - dived index over multiple chunks, distribute over nodes

- cluster - collection of shard

- replicas - copy of shards


## 2. Setup ELK on Windows 
No installation needed for Elastic technologies. Just unzip the package and modify the config if needed and run the utility.

### 2.1 https://www.elastic.co/downloads/elasticsearch 

### 2.2 https://www.elastic.co/downloads/logstash

### 2.3 https://www.elastic.co/downloads/kibana


## learning resources...

https://logz.io/blog/installing-the-elk-stack-on-windows/

https://logz.io/blog/windows-event-log-analysis/

https://github.com/elastic/elasticsearch


#### todo
http://www.noahdatatech.com/elasticsearch-for-dummies/
https://blog.webkid.io/visualize-datasets-with-elk/


