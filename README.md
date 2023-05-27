# logstash-metricbeat

This repo contains the logstagsh config which collects the data from metricbeats and sends it to opensearch nodes. 

[Docker image repo](https://hub.docker.com/repository/docker/yogeshraj292/logstash-metricbeat)

The docker image can be run using the below command:

```
docker run --name logstash-metricsbeat -p 5044:5044 yogeshraj292/logstash-metricbeat
```
