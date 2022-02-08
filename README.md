# Apache Kafka in Python

A bootstarp project for Apache Kafka in python that helps to setup kafka, producing and consuming data using python script.

***
- Source code for the Apache Kafka in Python YouTube series
- Video Links:
  
    - [1: How to Install Kafka Using Docker](https://www.youtube.com/watch?v=4xFZ_iTZLTs)
    - [2: Apache Kafka From the Shell](https://www.youtube.com/watch?v=FlAlz8guJeM)
    - 3: Writing Consumers and Producers in Python
  
- Article Links:
  
    - [1: How to Install Kafka Using Docker](https://betterdatascience.com/how-to-install-apache-kafka-using-docker-the-easy-way/)
    - [2: Apache Kafka From the Shell](https://betterdatascience.com/master-the-kafka-shell-in-5-minutes-topics-producers-and-consumers-explained/)
    - 3: Writing Consumers and Producers in Python


### How to run

- Make sure you have Zookeeper and Kafka installed (Video/Article 1)
- Execute in separate Terminal windows:

Create Topic,

```
kafka-topics.sh --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic messages
```

Producer,

```
python3 producer.py


Consumer,

```
python3 consumer.py
```


```