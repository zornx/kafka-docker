# Kafka Docker
Docker compose files for Apache Kafka with Confluent Platform docker images

## Kafka Docker Images
https://hub.docker.com/u/confluentinc

https://github.com/confluentinc/cp-docker-images

## Requirements
- docker
- docker-compose
- openssl (Only for SSL Example)
- keytool (Only for SSL Example)

## Contents
| Example | Description | SSL Example |
| ------ | ------ | ------ |
| Single Broker (All-in-one) | Server 1 (1 Zookeeper, 1 Kafka, 1 REST Proxy and 1 KSQL Server) | Yes |
| Single Broker (Multiple Servers) | Server 1 (1 Zookeeper and 1 Kafka) and Server 2 (1 REST Proxy and 1 KSQL Server)  | No |
| Cluster (All-in-one) | Server 1 (3 Zookeeper, 3 Kafka, 1 REST Proxy and 1 KSQL Server)  | No |
| Cluster (Multiple Servers) | Server 1 (1 Zookeeper and 1 Kafka), Server 2 (1 Zookeeper and 1 Kafka), Server 3 (1 Zookeeper and 1 Kafka) and Server 4 (1 REST Proxy and 1 KSQL Server) | No |

## References
https://docs.confluent.io/current/installation/docker/docs/index.html
