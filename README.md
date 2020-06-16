# docker-elk
Run a simple read-to-use ELK with docker-compose

## Services
### Elasticsearch
Basic features only (xpack disabled, no trial enabled)

### Logstash
Listening on `localhost:5044` (filebeat)

### Kibana
Listening on `localhost:5601` (Kibana UI)

## Usage
```
git clone https://github.com/stefa2k/docker-elk
cd docker-elk
docker-compose up -d
```
