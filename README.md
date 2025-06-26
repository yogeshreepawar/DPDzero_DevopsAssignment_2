
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


📌 Service 1: Golang Microservice Running 

![image](https://github.com/user-attachments/assets/af644c4f-40d2-4c29-b014-8f78176f2f83)

🟢 Terminal Output📌

📡API Endpoint Test: /ping
🔍 You visited http://localhost:8001/ping

![image](https://github.com/user-attachments/assets/40dcf6b1-2dc8-4354-acf4-dd5ce877aadb)

📡 API Endpoint Test: /hello
🔍 You visited http://localhost:8001/hello

![image](https://github.com/user-attachments/assets/ef6d2faa-dba5-445d-adcd-9802b6bf2252)


---


🐍 Service 2: Python Microservice Running (Flask)

![image](https://github.com/user-attachments/assets/18865b89-d07d-47b7-b35e-6a1e54ae820c)

🟢 Terminal Output📌

📡 API Endpoint Test: /ping
🔍 You accessed: http://localhost:8002/ping

![image](https://github.com/user-attachments/assets/cd68ae53-f3b4-47c7-af51-2fbd26893075)

📡 API Endpoint Test: /hello
🔍 You visited http://localhost:8002/hello

![image](https://github.com/user-attachments/assets/d476323e-c9d2-4c4b-afbd-295e5bbff7ec)












