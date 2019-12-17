# kafka-docker

## Purpose
For testing kafka.

Meant to run on one and same docker host.

### Spins up

One Zookeeper & 2 kafka brokers.

#### Requires
Requires DNS records of kafka1 & kafka2, pointing to the IP of docker host, otherwise they will not find each other.

Guess you could also do it with host entries in /etc/hosts in the broker containers in case no local DNS service is available...

## Components
#### zookeeper
Zookeper: hostname: zookeper, port: 2181

#### Brokers
Broker1: hostname: kafka1, port: 9092

Broker2: hostname: kafka2, port: 9093

## Topics
Also creates a 'test' topic with 2 partitions and 2 replicas.

## Links
docker repo:

https://github.com/wurstmeister/kafka-docker

Some usefull compose configs to help:

https://github.com/confluentinc/cp-docker-images/tree/master/examples

/Fille
