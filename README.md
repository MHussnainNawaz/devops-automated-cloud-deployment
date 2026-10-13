# 🚀 Automated Cloud & CI/CD Infrastructure

[![CI/CD Pipeline](https://github.com/YOUR_GITHUB_USERNAME/devops-automated-cloud-deployment/actions/workflows/deploy.yml/badge.svg)](https://github.com/YOUR_GITHUB_USERNAME/devops-automated-cloud-deployment/actions)


![Docker](https://img.shields.io/badge/Docker-Containerized-blue?logo=docker)


![Kubernetes](https://img.shields.io/badge/Kubernetes-Ready-326ce5?logo=kubernetes)


![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy-009639?logo=nginx)


![AWS](https://img.shields.io/badge/AWS-EC2_S3_VPC-FF9900?logo=amazon-aws)


End-to-end DevOps automation project featuring CI/CD pipeline automation, containerized multi-service architecture with Docker and Nginx reverse proxy, and cloud-ready infrastructure.

---

## 📌 Architecture Design

```text
[ Git Push ] ──> [ GitHub CI/CD ]
                         │
                  (Lint, Test, Build)
                         │
                         ▼
                [ Docker Container ]
                         │
                         ▼
            [ Nginx Reverse Proxy (Port 80) ]
                         │
                         ▼
               [ Flask App (Port 5000) ]