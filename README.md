# Monitoring and Observability



You've probably heard `Prometheus` and `Grafana` mentioned in a dozen places already, but what do they actually do? If you're not sure, don't worry, by the end of this guide, you'll have a clear, practical understanding of both, and you'll have set them up yourself.

This isn't a wall of documentation. It's a hands-on guide, built around real, runnable examples, taking you from "what is a metric" all the way to auto-discovering and monitoring an entire fleet of servers.

## Table of Contents

| # | File | What you'll learn |
| --- | --- | --- |
| 1 | [Intro](concepts/1.%20Intro.md) | What Prometheus is, and how metrics flow from a service to an alert |
| 2 | [Prometheus Setup](concepts/2.%20Prometheus%20Setup.md) | Installing Prometheus and Node Exporter, and graphing your first live metric |
| 3 | [Grafana Setup](concepts/3.%20Grafana%20Setup.md) | Installing Grafana, connecting it to Prometheus, and importing a full dashboard |
| 4 | [Monitoring Multiple Instances](concepts/4.%20Monitoring%20Multiple%20Instances.md) | Manually scraping multiple servers, and why that approach doesn't scale |
| 5 | [Service Discovery](concepts/5.%20Service%20Discovery.md) | Auto-discovering EC2 instances by tag, so Prometheus finds new servers on its own |

## Scripts

All the setup scripts used throughout this guide live in [`scripts/`](scripts):

| Script | Used in |
| --- | --- |
| [install-prometheus.sh](scripts/install-prometheus.sh) | Prometheus Setup |
| [install-grafana.sh](scripts/install-grafana.sh) | Grafana Setup |
| [install-node-exporter.sh](scripts/install-node-exporter.sh) | Service Discovery |
| [prometheus.yml](scripts/prometheus.yml) | Service Discovery (EC2 auto-discovery config) |

### Contribution

If you'd like to contribute to this guide, feel free to submit a pull request. Contributions are welcome and appreciated!

<br />

> ⭐ Star this repository if you found it useful.
