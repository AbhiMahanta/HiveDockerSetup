# Hive Setup using Docker

To run Hive with postgresql metastore:
```
    docker-compose up -d
```

To run a PrestoDB 0.181 with Hive connector:

```
  docker-compose up -d presto-coordinator
```

This deploys a Presto server listens on port `8080`