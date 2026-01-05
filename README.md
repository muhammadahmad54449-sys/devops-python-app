# DevOps Python Application 🚀

This project demonstrates a complete **DevOps foundation workflow** using a
Python Flask application. It covers containerization, orchestration, and scalable deployment.

---

## 🛠 Tech Stack

- **Python (Flask)**
- **Docker**
- **Docker Compose**
- **Kubernetes**
- **Git & GitHub**

---

## 📌 Project Features

- Dockerized Python Flask application  
- Local deployment using Docker Compose  
- Kubernetes Deployment and Service  
- Namespace-based Kubernetes setup  
- Scalable application using replicas  

---

## 📂 Project Structure
devops-python-app/
├── app.py
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── namespace.yaml
├── Deployment.yaml
├── service.yaml
└── README.md


---

## 🐳 Docker Build & Run

### Build Docker Image

```bash
docker build -t mohdahmad12870/devops-python-app:1.0 .
docker run -p 5000:5000 mohdahmad12870/devops-python-app:1.0
docker-compose up -d

kubectl apply -f namespace.yaml
kubectl apply -f Deployment.yaml
kubectl apply -f service.yaml



