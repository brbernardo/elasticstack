# docker-elasticstack

## O que é esse projeto

Projeto para subir um ambiente de desenvolvimento do Elastic Stack (Elasticsearch, Logstash e Kibana) com Docker.

## Logstash
As configurações do logstash estão divididas em duas pastas
* Config, onde ficam as configurações do logstash, como por exemplo o arquivo pipelines.yml
* Pipeline, onde vão ser colocados os pipelines.

## Como iniciar

```
docker-compose up -d
```

Caso queira contribuir com algo só mandar um PR!