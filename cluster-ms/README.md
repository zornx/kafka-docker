# Cluster (Multiple Servers)
Server 1 (1 Zookeeper and 1 Kafka), Server 2 (1 Zookeeper and 1 Kafka), Server 3 (1 Zookeeper and 1 Kafka) and Server 4 (1 REST Proxy and 1 KSQL Server)

## Servers info
| Server | IP |
| ------ | ------ |
| Server 1 | 192.168.120.3 |
| Server 2 | 192.168.139.3 |
| Server 3 | 192.168.211.3 |
| Server 4 | localhost |

## Instructions
Run Docker Compose file:
```sh
$ docker-compose up --build
```
