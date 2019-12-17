# kafka-docker
For testing kafka.

Meant to run on one and same docker host.


### Spins up:

One Zookepper & 2 kafka brokers.

#### zookeeper
Zookeper: hostname: zookeper, port: 2181

#### Brokers
Broker1: hostname: kafka1, port: 9092

Broker2: hostname: kafka2, port: 9093

## Topics
Also creates a 'test' topic with 2 partitions and 2 replicas.

## Links
https://github.com/wurstmeister/kafka-docker

https://github.com/confluentinc/cp-docker-images/tree/master/examples
