# JHipster Prometheus demo

Docker configuration inspired by https://github.com/vegasbrianc/prometheus

## Instructions

- run the docker-compose file
```
    docker-compose up -d
```
You should have a prometheus metrics endpoint avaible at [http://localhost:8080/prometheusMetrics](http://localhost:8080/prometheusMetrics).

You can access Prometheus UI at [http://localhost:9090/](http://localhost:9090/) and Grafana at [http://localhost:3000](http://localhost:3000) (credentials : admin/jhipster), further instructions [here](https://github.com/vegasbrianc/prometheus#post-configuration).