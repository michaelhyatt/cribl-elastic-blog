# Docker compose that runs Elastic stack and Cribl worker
Docker compose that starts Elasticsearch and Kibana as well as Cribl Stream worker in `single` mode.

## To start Elasticsearch, Kibana and Cribl Stream
```bash
$ docker compose up -d
```

## To start Elasticsearch, Kibana, Fleet and Cribl Stream
```bash
$ docker compose --profile fleet up -d
```

## Cleanup
```bash
$ docker compose down --remove-orphans
```
