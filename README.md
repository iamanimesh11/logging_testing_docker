# 🔥 Real-Time Logging & Monitoring System (Loki + Grafana + Streamlit)

## 📌 Project Overview
This project provides a **real-time logging system** using:
- **Loki** for log aggregation 📥
- **Promtail** for collecting logs 📡
- **Grafana** for visualization 📊
- **Streamlit** for an interactive UI to explore logs 🖥️

🔹 All components run inside **Docker containers** for easy setup and deployment.

---

## 🚀 Getting Started

### **1️⃣ Install Docker & Docker Compose**
Ensure you have **Docker** and **Docker Compose** installed:
- [Download Docker](https://www.docker.com/get-started)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

To verify:
docker -v
docker-compose -v 


### **2️⃣ Clone the Repository**

git clone https://github.com/your-username/logging-system.git
cd logging-system

### **3️⃣Run Project**
docker-compose up --build

✅ This will:

Start Loki on http://localhost:3100
Start Grafana on http://localhost:3000
Start Streamlit UI on http://localhost:8501

To run in background:
docker-compose up -d

### **4️⃣ Open Streamlit**
Open: http://localhost:8501


