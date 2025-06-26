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


### 📌 Initial Commit

🟢 **Initial Commit:**  
Added **Go** and **Python** microservices with complete source code and Docker-based project structure for NGINX reverse proxy setup.



  ![1](https://github.com/user-attachments/assets/e5899b91-022f-456f-9c7e-6c2e117a2b10)
  ![2](https://github.com/user-attachments/assets/0c211b39-b1f7-494d-baf7-ddf16b97b715)

---



## 📁 Folder Structure


![14](https://github.com/user-attachments/assets/57df81fc-76b2-4b7a-820e-12a89098392b)



---

## 🐳 Running Docker Containers

🛠️ Building and Running the Services

This project uses Docker Compose to build and run the Python and Go backend services along with Nginx for reverse proxy.

To build and run the services, execute:

<h1> docker-compose up --build </h1>

![10](https://github.com/user-attachments/assets/4a5d0a81-7050-4546-854b-0ebebca3702c)


 ⚠️ Note: Nginx is mapped to port **8081** instead of **8080** because port 8080 is already used by Jenkins on this system.

The following containers are launched by this project:

![15](https://github.com/user-attachments/assets/ed23aa52-b6da-40c8-840d-69a54b8ac613)

---

📌 Service 1: Golang Microservice Running 

🟢 Terminal Output📌

📡API Endpoint Test: /ping
🔍 You visited http://localhost:8081/ping

![11](https://github.com/user-attachments/assets/37777336-b60a-47c6-a035-c779905997ba)

---


🐍 Service 2: Python Microservice Running (Flask)

🟢 Terminal Output📌

📡 API Endpoint Test: /ping
🔍 You accessed: http://localhost:8081/ping

![12](https://github.com/user-attachments/assets/1e2bd778-46f3-4377-8ea1-fd4b3fb86b5b)

---

## 🌐 Nginx Reverse Proxy Verification

After starting all services using Docker Compose, you can verify the Nginx reverse proxy by visiting:
http://localhost:8081

![13](https://github.com/user-attachments/assets/1e69ff26-31ec-4415-bd23-26a54f385c2e)


---


## 📈 Monitoring Setup (Prometheus + Grafana + cAdvisor)

This project uses **Prometheus**, **Grafana**, and **cAdvisor** to monitor containers and visualize metrics.

The following containers are launched by this project:

![Screenshot 2025-06-26 133610](https://github.com/user-attachments/assets/9028e608-a115-4d45-8f22-c07e91d75abf)


📍 After services are up, you can access:

Prometheus: http://localhost:9090

![20](https://github.com/user-attachments/assets/2e0da84c-f1ce-441b-bd86-29dd8e271627)

---

Grafana: http://localhost:3000


![17](https://github.com/user-attachments/assets/f6875b04-31d4-48d5-8358-67ea2349f932)

---


Cadvisor:http://localhost:8085

![21](https://github.com/user-attachments/assets/4b78964a-208c-413e-82ba-0cf6f50a514c)


---


✅ Project successfully integrates Nginx reverse proxy, containerized Python and Go services, and a complete monitoring stack using Prometheus, Grafana, and cAdvisor.





















