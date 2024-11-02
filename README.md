# This repo container docker compose file for Kafka and Zookeeper

# 1zookeeper 1broker

```sh
docker compose -f ./1zoo-1kafka.yaml -p kafka up -d
```

# 1zookeeper 3brokers

```sh
docker compose -f ./1zoo-3kafka.yaml -p kafka up -d
```

# 3zookeeper 3brokers

```sh
docker compose -f ./3zoo-3kafka.yaml -p kafka up -d
```
