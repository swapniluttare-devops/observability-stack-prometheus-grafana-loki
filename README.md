# observability-stack-prometheus-grafana-loki
A hands-on monitoring and observability project using Prometheus for metrics and alerting, Grafana for dashboards, and Loki for log aggregation.
# End-to-End Observability with Prometheus, Grafana, and Loki

A hands-on monitoring and observability project using Prometheus for metrics
and alerting, Grafana for dashboards, and Loki for log aggregation.

## Overview

This project demonstrates a practical observability workflow:

- Collect and query metrics with Prometheus.
- Visualize monitoring data in Grafana.
- Define and test Prometheus alert rules.
- Explore centralized logs with Loki and Grafana.

## Tools

- Prometheus — metrics collection, storage, PromQL queries, and alert rules
- Grafana — dashboards and data visualization
- Loki — log aggregation and querying
- [Add other tools or exporters you used]

## What I learned

### Prometheus

- Configure Prometheus with YAML.
- Set scrape intervals and targets.
- Explore time-series metrics with PromQL.
- Define alert rules in a separate rules file.
- Create a high-CPU alert and add human-readable annotations.
- Load rule files and apply configuration changes.
- Observe alerts moving through Inactive, Pending, and Firing states.
- Simulate a condition to test an alert.

### Grafana

- Connect data sources.
- Explore metrics and logs.
- Build dashboards and panels to visualize system behavior.

### Loki

- Explore centralized log collection and querying.
- Use Grafana to investigate logs alongside metrics.

## Configuration files

- `prometheus/prometheus.yml` — Prometheus configuration
- `prometheus/alert-rules.yml` — Prometheus alert rules
- `loki/loki-config.yml` — Loki configuration, if included in this repository
- `grafana/dashboards/` — exported dashboards, if available

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/observability-stack-prometheus-grafana-loki.git
   cd observability-stack-prometheus-grafana-loki
