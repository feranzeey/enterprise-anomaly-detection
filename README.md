# Enterprise Anomaly Detection & Monitoring Platform 🚀

A production-style monitoring and alerting solution built using modern observability tools.

This project demonstrates how DevOps engineers monitor infrastructure health, detect abnormal behavior, visualize metrics, and create automated alerting workflows.

---

# 🏗️ Architecture Overview

The monitoring stack includes:

- Prometheus → Metrics collection
- Grafana → Visualization & dashboards
- Node Exporter → Linux system metrics
- Loki → Log aggregation
- Alert Rules → Automated anomaly detection

Flow:

Linux Server  
⬇️  
Node Exporter  
⬇️  
Prometheus  
⬇️  
Grafana Dashboards + Alerts  
⬇️  
Incident Detection

---

# 🛠️ Technologies Used

## Monitoring
- Prometheus
- Grafana
- Node Exporter
- Loki

## Infrastructure
- Ubuntu Linux
- Virtual Machines
- Docker

## DevOps Practices
- Monitoring & Observability
- Alert Engineering
- Infrastructure Troubleshooting
- System Reliability

---

# 📊 Monitoring Implementation

## Grafana Dashboard

Created dashboards to monitor:

- CPU usage
- Memory usage
- Disk utilization
- Network activity
- System performance


![Grafana Dashboard](screenshots/grafana-dashboard.png)


---

# 🚨 Alerting System

Configured anomaly detection alerts for:

## CPU Anomaly Detection

Detects unusual CPU spikes compared to normal behavior.

![Alert Rules](screenshots/alert-rules.png)


---

## Memory Alert

Tracks abnormal memory consumption.

![Memory Alert](screenshots/memory-alert.png)


---

## Network Alert

Monitors network activity changes.

![Network Alert](screenshots/network-alert.png)


---

# 📈 Node Exporter Monitoring

Collected real-time Linux infrastructure metrics.

![Node Exporter Dashboard](screenshots/node-exporter-dashboard.png)


---

# 🔎 Log Monitoring

Integrated Loki for centralized log collection and analysis.

![Loki Added](screenshots/loki-added.png)


---

# ⚙️ Dashboard Setup

Imported and configured monitoring dashboards inside Grafana.

![Import Dashboard](screenshots/import-dashboard.png)


---

# 🧪 Testing & Validation

Tested:

✅ Metrics collection  
✅ Grafana visualization  
✅ Alert rule creation  
✅ Infrastructure monitoring  
✅ Dashboard availability  


Running services:

![All Running](screenshots/all-running.png)


---

# 🎯 Skills Demonstrated

This project demonstrates practical experience with:

- Linux administration
- Prometheus monitoring
- Grafana dashboards
- Alert configuration
- Observability practices
- Infrastructure troubleshooting
- DevOps monitoring workflows

---

# 📌 Future Improvements

- Add Slack/Email alert notifications
- Deploy monitoring stack using Docker Compose
- Add Kubernetes monitoring
- Implement automated incident response

---

# 👨🏽‍💻 Author

Dada Oluwaferanmi Emmanuel

DevOps Engineer Intern | Cloud | CI/CD | Monitoring | Automation

GitHub:
https://github.com/feranzeey

LinkedIn:
https://www.linkedin.com/in/dada-oluwaferanmi-devops