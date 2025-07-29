# 🐳 Docker Zero to Hero

**A complete beginner-to-advanced Docker course**: Learn containers, images, volumes, networks, Docker Compose, and more — using real-world projects and industry best practices.

---

## Course Highlights

- **No prior Docker experience needed**
- Hands-on labs and projects in every module
- Covers Docker fundamentals to advanced topics
- Teaches real DevOps workflows and best practices
- Final project: Build, secure, and deploy a full-stack application

---

## Table of Contents

1. [Module 1: Docker Fundamentals](#-module-1-docker-fundamentals)
2. [Module 2: Building and Managing Images](#-module-2-building-and-managing-images)
3. [Module 3: Docker Networking Deep Dive](#️-module-3-docker-networking-deep-dive)
4. [Module 4: Volumes and Persistent Data](#️-module-4-volumes-and-persistent-data)
5. [Module 5: Docker Compose - Real App Orchestration](#️-module-5-docker-compose---real-app-orchestration)
6. [Module 6: Security & Best Practices](#-module-6-security--best-practices)
7. [Module 7: Debugging, Logging & Monitoring](#-module-7-debugging-logging--monitoring)
8. [Module 8: Docker Registry & Image Management](#-module-8-docker-registry--image-management)
9. [Module 9: CI/CD & Docker in DevOps Workflows](#️-module-9-cicd--docker-in-devops-workflows)
10. [Bonus Module: Docker in Production](#-bonus-module-docker-in-production)
11. [Final Capstone Project](#-final-capstone-project)
12. [Bonus Materials](#-bonus-materials)
13. [Wrap-up](#-wrap-up)

---

## Module 1: Docker Fundamentals

- What is Docker? Why Docker?
- Containers vs Virtual Machines
- Docker Architecture (Client, Daemon, Registry)
- Installing Docker (incl. Docker Desktop)
- Hello World with Docker
- Docker CLI: `run`, `ps`, `stop`, `start`, `rm`, `images`, etc.
- Understanding Docker Images vs Containers

**🧪 Lab:** Run your first containerized app (Nginx, Redis)

---

## Module 2: Building and Managing Images

- Anatomy of a Dockerfile
- Build Context and Layers
- `COPY` vs `ADD`, `CMD` vs `ENTRYPOINT`
- Using ENV variables and `ARG`s
- Multi-stage Builds
- Caching & Optimizing Build
- Image Tagging & Versioning

**📁 Project:** Containerize a Node.js app  
**🎁 Bonus:** Build a minimal Alpine-based image

---

## Module 3: Docker Networking Deep Dive

- Networking Modes: Bridge, Host, Overlay, None
- Port Mapping & Exposing
- Custom Networks
- Container Linking & DNS
- Inspecting Docker Networks

**🧪 Lab:** Connect Nginx + Express via Docker Network  
**🧠 Advanced:** Network traffic analysis between containers

---

## 🗃️ Module 4: Volumes and Persistent Data

- Volumes vs Bind Mounts
- Volume Lifecycle Management
- Backups & Restore
- Sharing Data Between Containers
- Security Best Practices

**📁 Project:** Dockerize a Node.js + PostgreSQL app

---

## Module 5: Docker Compose - Real App Orchestration

- Why Compose?
- `docker-compose.yml` Syntax & Best Practices
- Compose CLI: `up`, `down`, `logs`, `exec`, `config`
- Service Dependencies
- Environment Variable Files (`.env`)

**📁 Project:** Full-stack App with Frontend, Backend & DB  
**🎁 Bonus:** Add Redis cache to your stack

---

## 🔐 Module 6: Security & Best Practices

- Running Containers as Non-Root
- Docker Bench Security
- Image Scanning: Trivy, Snyk
- Managing Secrets
- Limiting CPU, Memory, ulimits

**🧪 Lab:** Scan & Harden a Dockerized App

---

## 🔍 Module 7: Debugging, Logging & Monitoring

- Docker Logs & Log Drivers
- Events, Stats & Inspect
- Healthchecks
- Tools: cAdvisor, sysdig, Dive
- Troubleshooting Build Failures

**🧪 Lab:** Debug a broken container setup  
**🎁 Bonus:** Monitoring with Prometheus + Grafana

---

## Module 8: Docker Registry & Image Management

- DockerHub vs Private Registries
- Tagging, Pushing, Pulling Images
- Caching & Cleanup
- Private Registry Setup
- Using GitHub Packages, ECR, GitLab Registry

**🧪 Lab:** Publish & Pull a Custom Image  
**🧠 Advanced:** Host your own Docker registry

---

## Module 9: CI/CD & Docker in DevOps Workflows

- Docker in GitHub Actions / GitLab CI / Jenkins
- Automate Build, Test, Push
- Staging Deployments with Compose
- Intro to Docker + Kubernetes

**Project:** Build CI/CD pipeline to push to DockerHub

---

## Bonus Module: Docker in Production

- Image Slimming & Optimization
- Production-Ready Dockerfiles
- Config & Secrets Management
- Detached & Restart Modes
- Real Deployment Strategies

**📁 Project:** Deploy a microservice to cloud/VPS

---

## 🎓 Final Capstone Project

Build, secure, and deploy a full-stack app:

- Frontend: React or Vue
- Backend: Express / Django / Flask
- Database: PostgreSQL or MongoDB
- Redis Cache
- Nginx Reverse Proxy
- Docker Compose Setup
- CI/CD Pipeline
- Deployed to Cloud or VPS

---

## 📎 Bonus Materials

- Docker CLI Cheat Sheet
- Ready-to-use Dockerfile Templates
- Docker Interview Prep
- Recommended Books, Blogs, and Tools

---

## Wrap-up

- Summary of Docker Skills You’ve Gained
- Advanced Learning Paths: Docker Swarm, Kubernetes
- Career Advice for DevOps, SRE, and Backend Roles

---

## 📄 License

This course and repository are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
