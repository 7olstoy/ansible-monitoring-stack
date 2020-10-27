ansible-monitoring-stack
========

A monitoring solution for Docker hosts and containers with [Prometheus](https://prometheus.io/), [Grafana](http://grafana.org/), [VictoriaMetrics](https://hub.docker.com/r/victoriametrics/victoria-metrics),
[NodeExporter](https://github.com/prometheus/node_exporter), [Blackbox-exporter](https://hub.docker.com/r/prom/blackbox-exporter) and alerting with [AlertManager](https://github.com/prometheus/alertmanager).

Like [this](https://github.com/A-styler/docker-compose-monitoring-stack/edit/master/README.md) solution, but without docker-compose.

Prerequisites:

* Ansible
* Docker Engine
* Python3-pip and python docker
* Additional docker network ```proxy``` with traefik