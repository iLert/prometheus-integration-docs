# Prometheus alert manager integrations

This setup is a resource that has been used as a sample for our [ilert documentation](https://docs.ilert.com/).

## Getting started

### Requirements

* [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Docker Desktop](https://www.docker.com/products/docker-desktop/)
* an [ilert account](https://app.ilert.com/signup)

### Setup & run

* clone this repository `git clone git@github.com:iLert/prometheus-integration-docs.git`
* move to repository directory `cd prometheus-integration-docs`
* start docker setup `docker-compose up -d`

## Integrations

### Mimir

[Mimir](https://grafana.com/oss/mimir/) is an open source, horizontally scalable, highly available multi-tenant, long-term storage for [Prometheus](https://prometheus.io/) metrics.

> You can find our integration guide under https://docs.ilert.com/integrations/mimir

### Cortex

[Cortex](https://cortexmetrics.io/) is a [CNCF](https://cncf.io) incubation project used in several production systems including [Amazon Managed Service for Prometheus (AMP)](https://aws.amazon.com/prometheus/) and it provides horizontally scalable, highly available, multi-tenant, long term storage for [Prometheus](https://prometheus.io/).

> You can find our integration guide under https://docs.ilert.com/integrations/cortex

### Loki

[Loki](https://grafana.com/oss/loki/) is a horizontally scalable, highly available, multi-tenant log aggregation system inspired by [Prometheus](https://prometheus.io/).

> You can find our integration guide under https://docs.ilert.com/integrations/loki
