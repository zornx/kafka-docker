# Single Broker (All-in-one) SSL
Server 1 (1 Zookeeper, 1 Kafka, 1 REST Proxy and 1 KSQL Server)

## Instructions
Generate the required certificates and keystores:
```sh
$ ./create-certs.sh
```
Export environment variable with certs path:
```sh
$ export KAFKA_SSL_SECRETS_DIR=$(pwd)/certs
```
Run Docker Compose file:
```sh
$ docker-compose up --build
```
