# Laravel Performance Monitoring App with Docker and Prometheus

## 🚀 Overview

This is a **Dockerized Laravel application** focused on **performance monitoring and observability** during development. The goal is to provide a self-contained environment with tools like **Prometheus** for collecting metrics, and **Redis** and **MySQL** as core services.

> ⚠️ This project is a work in progress. Features like Grafana dashboards, advanced DB monitoring, and custom Laravel metrics will be added soon.

---
## 📦 Services Included

- **Laravel (PHP 8.3 runtime via Sail)** — The core application.
- **MySQL** — Primary database used by the app.
- **Redis** — Used for caching and queue management.
- **Prometheus** — For scraping performance metrics and monitoring the health of services.

## 🔧 Why This Setup Matters

Modern web applications demand **high performance**, **scalability**, and **observability**. Laravel's default development environment lacks built-in performance monitoring. This setup introduces **Prometheus** to:

- Track memory and CPU usage
- Monitor Redis and MySQL health
- Provide metrics for future Grafana dashboards
- Enable early detection of performance bottlenecks

## ✅ Why Use This?

- 🔍 **Performance Visibility**: Prometheus gives you real-time insights into your app's behavior.
- 🐳 **Reproducible Environment**: Docker ensures consistent local and production environments.
- ⚙️ **Pre-configured Services**: MySQL and Redis are integrated and ready to use.
- 📈 **Extendable**: Easily integrate Grafana or Alertmanager for better observability and alerting.

## 🧰 How to Use

### 1. Clone the Repository

```bash
    clone the repo
    cd laravel-performance-monitoring
    ./vendor/bin/sail up -d
```
