<h1 align="center">Kafka Producer and Consumer in Java</h1>


## Overview

A simple Java application to produce and consume messages in Kafka topics.

The NewOrderMain class produces the messages, and the EmailService, FraudDetectorService, and LogService classes consume the messages.

This application was developed during a Kafka course.

## Requirements

The application has been developed and tested to work with the following minimum requirements:

- Java 11
- Kafka 2.13-3.2.0

## Run

1 - Download Kafka from kafka.apache.org

2 - Extract the downloaded file

3 - Go to the Kafka folder

4 - Start the Zookeeper server
```
bin/zookeeper-server-start.sh config/zookeeper.properties
```

5 - Start the Kafka server
```
bin/kafka-server-start.sh config/server.properties
```

6 - Open the Java project

7 - Run the EmailService class

8 - Run the FraudDetectorService class

9 - Run the LogService class

10 - Run the NewOrderMain class to output the messages

11 - The consumed messages will be displayed in the console of the consumer classes
