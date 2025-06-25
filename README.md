
<h1 align="center">🚀 <strong style="font-size:36px;">NGINX Reverse Proxy Microservices</strong> 🐳</h1>
<p align="center"><strong>Docker Compose + Golang + Python + NGINX</strong></p>
<p align="center">🔁 Path-based routing with a single port access | 💡 Clean containerized setup | ✅ Health Checks & Logs</p>

---

## 📸 Architecture Diagram

<p align="center">
  <img src="https://raw.githubusercontent.com/yourusername/yourrepo/main/assets/architecture.png" alt="Architecture" width="700">
</p>

> This diagram shows how NGINX receives incoming traffic on port `8080` and routes it to two services:
> - `/service1` → Go (Port 8001)
> - `/service2` → Python (Port 5000)


---

## 📦 Project Overview

This project demonstrates how to:

- Use **Docker Compose** to orchestrate services
- Run a **Go** and a **Python** backend in containers
- Configure an **NGINX reverse proxy** to route based on URL paths
- Enable **health checks** for production readiness
- Log **incoming requests** for observability


  ---


## 📁 Folder Structure

.
├── README.md
├── __MACOSX
│   ├── service_1
│   └── service_2
├── docker-compose.yml
├── nginx
│   ├── dockerfile
│   └── nginx.conf
├── service_1
│   ├── README.md
│   ├── dockerfile
│   └── main.go
└── service_2
    ├── README.md
    ├── app.py
    ├── dockerfile
    ├── pyproject.toml
    └── uv.lock




