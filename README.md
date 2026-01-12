# AWS EC2 Docker Deployment

This project demonstrates how to deploy a Dockerized web application on an AWS EC2 instance.

## 🚀 Tech Stack
- AWS EC2
- Docker
- Docker Compose
- Nginx
- Ubuntu Server

## 📦 What this project does
- Runs a web application inside a Docker container
- Exposes it via port 80
- Uses Docker Compose for orchestration
- Deployed on a public EC2 instance

## 🛠️ How to run
```bash
docker-compose up -d

Access via EC2 public IP:
http://<EC2_PUBLIC_IP>
