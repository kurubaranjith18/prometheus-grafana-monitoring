# prometheus-grafana-monitoring

### 📄 **README.md**
```md
# Prometheus + Grafana Monitoring Stack (DevOps Portfolio)

This project sets up a complete monitoring stack using Docker Compose.  
It includes Prometheus for metrics, Grafana for dashboards, and Node Exporter for system metrics.

---

## 📁 Files Included

| File | Purpose |
|------|---------|
| `docker-compose.yml` | Starts Prometheus + Grafana + Node Exporter |
| `prometheus.yml` | Prometheus scrape config |
| `README.md` | Documentation |

---

## 🚀 How to Run

Start the monitoring stack:
```sh
docker-compose up -d
🌐 Access Dashboards
Prometheus
http://localhost:9090
Grafana
http://localhost:3000
Login:

admin / admin
Metrics available:
CPU usage

Memory

Disk I/O

Network traffic

