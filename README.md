# 🐳 Blue-Green + Canary Deployment (Docker + NGINX)

This project demonstrates a simple **Blue-Green Deployment** with **Canary testing**, using Docker, Flask, and NGINX.

## 🔧 Tech Stack
- Python (Flask)
- Docker
- Docker Compose
- NGINX (Reverse Proxy & Load Balancer)

## 🎯 Features
- Blue = Stable Version
- Green = Canary Version (10% traffic)
- Easy local testing with `docker-compose`

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/blue-green-canary-docker.git
cd blue-green-canary-docker
docker-compose up --build
