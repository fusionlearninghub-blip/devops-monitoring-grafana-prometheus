# 🚀 DevOps Monitoring System

![Docker](https://img.shields.io/badge/Docker-Enabled-blue?logo=docker)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-orange?logo=prometheus)
![Grafana](https://img.shields.io/badge/Grafana-Dashboards-red?logo=grafana)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-yellow?logo=linux)


🚀 DevOps Monitoring System (Grafana + Prometheus + Node Exporter)
📌 Overview

This project demonstrates a real-time infrastructure monitoring system using industry-standard DevOps tools.

It collects system metrics from a Linux environment and visualizes them using Grafana dashboards.

This setup simulates how production systems are monitored in real companies.

🧰 Tech Stack
🐳 Docker
📊 Prometheus
📈 Grafana
🖥️ Node Exporter
🐧 Linux (Ubuntu)
🎯 Features
CPU usage monitoring
Memory usage tracking
Disk usage analysis
System-level metrics collection
Real-time visualization dashboards
Prometheus target scraping
🏗️ Architecture
Node Exporter → Prometheus → Grafana → Dashboard Visualization
⚙️ Setup Instructions
1. Clone repository
git clone https://github.com/fusionlearninghub-blip/devops-monitoring-grafana-prometheus.git
cd devops-monitoring-grafana-prometheus
2. Start services
docker-compose up -d
3. Access tools
Grafana:
http://localhost:3001
Prometheus:
http://localhost:9090
📊 Grafana Dashboards

Metrics visualized:

CPU Usage %
Memory Usage %
Disk Utilization
System Load
📸 Screenshots

Add your dashboard screenshot here

![Grafana Dashboard](screenshots/dashboard.png)
🧠 What I Learned
How monitoring systems work in production environments
How Prometheus scrapes system metrics
How Grafana visualizes real-time data
Docker multi-container architecture
Linux system metrics exposure using Node Exporter
🚀 Future Improvements
Kubernetes integration
Alerting system (email / Slack notifications)
Log aggregation (ELK stack)
CI/CD automation with GitHub Actions
👨‍💻 Author

DevOps Learning Project — Building real-world infrastructure monitoring skill
