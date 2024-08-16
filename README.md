# Docker compose that runs Elastic stack and Cribl worker
Docker compose that starts Elasticsearch and Kibana as well as Cribl Stream worker in `single` mode. 

## URLs:
Cribl: http://localhost:9000
Kibana: https://localhost:5601

## To start Elasticsearch, Kibana and Cribl Stream
```bash
$ docker compose up -d
```
## Credentials
### Cribl
admin:cribldemo
### Elastic
elastic:cribldemo

## To start Elasticsearch, Kibana, Fleet and Cribl Stream
```bash
$ docker compose --profile fleet up -d
```

## Cleanup
```bash
$ docker compose down --remove-orphans --volumes
```
