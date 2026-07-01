# Enterprise Anomaly Detection System

## Project Overview

The Enterprise Anomaly Detection System is a monitoring solution built using Grafana, Prometheus, Node Exporter, Loki, and Promtail. It provides real-time infrastructure monitoring, anomaly detection, centralized log collection, and intelligent alerting for Linux servers.

This project demonstrates how enterprise organizations monitor CPU, memory, disk, network performance, and system logs to proactively detect issues before they affect production environments.

---

## Architecture

```
+-------------------+
|   Node Exporter   |
+-------------------+
          |
          v
+-------------------+
|   Prometheus      |
+-------------------+
          |
          v
+-------------------+
|    Grafana        |
+-------------------+
          ^
          |
+-------------------+
|      Loki         |
+-------------------+
          ^
          |
+-------------------+
|    Promtail       |
+-------------------+
          ^
          |
     Linux Log Files
```

---

## Features

- Real-time CPU monitoring
- Memory usage monitoring
- Disk usage monitoring
- Network traffic monitoring
- Prometheus metrics collection
- Grafana dashboards
- Centralized log aggregation with Loki
- Log collection using Promtail
- Alert rules for infrastructure anomalies
- Executive monitoring dashboard
- Historical performance trends

---

## Technologies Used

- Grafana
- Prometheus
- Node Exporter
- Loki
- Promtail
- Docker
- Docker Compose
- Linux (Ubuntu)

---

## Project Structure

```
enterprise-anomaly-detection/
│
├── docker-compose.yml
├── loki-config.yml
├── promtail-config.yml
├── README.md
└── screenshots/
    ├── dashboard.png
    ├── executive-dashboard.png
    ├── alerts.png
    ├── prometheus-targets.png
    └── grafana-home.png
```

---

## Services

| Service | Port |
|----------|------|
| Grafana | 3000 |
| Prometheus | 9090 |
| Node Exporter | 9100 |
| Loki | 3100 |
| Promtail | 9080 |

---

## Setup

### Clone the repository

```bash
git clone https://github.com/feranzeey/enterprise-anomaly-detection.git
```

### Enter the project

```bash
cd enterprise-anomaly-detection
```

### Start the monitoring stack

```bash
docker compose up -d
```

### Verify running containers

```bash
docker ps
```

---

## Access the Applications

### Grafana

```
http://localhost:3000
```

Default credentials

Username

```
admin
```

Password

```
admin
```

---

### Prometheus

```
http://localhost:9090
```

---

### Node Exporter Metrics

```
http://localhost:9100/metrics
```

---

### Loki

```
http://localhost:3100
```

---

## Alert Rules

The following infrastructure alerts were configured:

- High CPU Usage
- High Memory Usage
- High Disk Usage
- High Network Utilization

These alerts notify administrators when resource utilization exceeds defined thresholds.

---

## Dashboards

### Infrastructure Dashboard

Displays:

- CPU Usage
- Memory Usage
- Disk Usage
- Network Activity

---

### Executive Dashboard

Displays:

- Overall infrastructure health
- Resource utilization
- Performance trends
- Active alerts
- Historical metrics

---

## Screenshots

Add screenshots inside the **screenshots** folder.

Example:

```
screenshots/
```

- Grafana Dashboard
- Executive Dashboard
- Prometheus Targets
- Alert Rules
- Loki Logs

---

## Skills Demonstrated

- Infrastructure Monitoring
- Observability
- Performance Monitoring
- Alert Management
- Docker
- Docker Compose
- Linux Administration
- Prometheus Query Language (PromQL)
- Grafana Dashboard Design
- Centralized Logging

---

## Future Improvements

- Machine Learning-based anomaly detection
- Predictive capacity planning
- Slack notifications
- Email alerting
- Kubernetes monitoring
- AWS CloudWatch integration
- Grafana Cloud integration

---

## Learning Outcomes

Through this project I learned how to:

- Deploy a complete monitoring stack
- Collect system metrics using Prometheus
- Visualize infrastructure data with Grafana
- Configure infrastructure alerts
- Aggregate logs using Loki and Promtail
- Build production-style monitoring dashboards

---

## Author

**Oluwaferanmi Dada**

GitHub:
https://github.com/feranzeey

LinkedIn:
(Add your LinkedIn profile here)

---

## License

This project is for educational and portfolio purposes.