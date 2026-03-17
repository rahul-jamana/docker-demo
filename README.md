# docker-demo# 🐳 Docker Python Flask App

A simple Flask app containerized using Docker.

---

## 🚀 How to Run (Step-by-Step)

### 1. Go to project folder
```bash
cd ~/docker-python-demo
docker build -t rahulllllll/docker-python-demo .

run container
docker run -d -p 5000:5000 rahulllllll/docker-python-demo

stop container
docker ps
docker stop <container_id>