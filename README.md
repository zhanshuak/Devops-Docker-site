# 🚀 DevOps Docker + Kubernetes Project

## 📌 Overview

This project demonstrates a complete DevOps workflow:
- Application containerization with Docker
- Local Kubernetes deployment using K3s
- CI pipeline using GitHub Actions
- Service exposure via Kubernetes NodePort

The goal is to simulate a real-world DevOps environment from development to deployment.

---

## 🏗️ Architecture

```text
Developer → GitHub → Docker Build → Kubernetes (k3s) → Service → Browser
