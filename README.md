# DevOps Mega Project: From Code to Kubernetes - Building a Production-Grade DevSecOps + GitOps Platform

## A complete **production-grade DevSecOps pipeline** implementing CI/CD with security, automation, and Kubernetes deployment using **GitOps principles**.

This project demonstrates how a **3-tier MERN stack application** is deployed on **AWS EKS** using industry-standard tools.

#
### <mark>Project Deployment Flow:</mark>
![Project Flow](./Assets/DevSecOps+GitOps.gif)

#

## Tech stack used in this project:
- GitHub (Code)
- Docker (Containerization)
- Jenkins (CI)
- OWASP (Dependency check)
- SonarQube (Quality)
- Trivy (Filesystem Scan)
- ArgoCD (CD)
- Redis (Caching)
- AWS EKS (Kubernetes)
- Helm (Monitoring using grafana and prometheus)

## 🛠️ Tech Stack Used

---

### 🚀 Core DevSecOps Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jenkins/jenkins-original.svg" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="45"/>
  <img src="https://argo-cd.readthedocs.io/en/stable/assets/logo.png" height="45"/>
</p>

<p align="center">
GitHub • Jenkins • Docker • ArgoCD
</p>

---

### 🔐 Security & Code Quality

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sonarqube/sonarqube-original.svg" height="45"/>
  <img src="https://raw.githubusercontent.com/aquasecurity/trivy/main/docs/imgs/logo.png" height="45"/>
  <img src="https://owasp.org/www-project-branding/assets/images/OWASP_Logo.svg" height="45"/>
</p>

<p align="center">
OWASP Dependency Check • SonarQube • Trivy
</p>

---

### ☸️ Kubernetes & Cloud

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="45"/>
  <img src="https://helm.sh/img/helm.svg" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="45"/>
</p>

<p align="center">
AWS EKS • Helm • Redis
</p>

---

### 📊 Monitoring & Observability

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg" height="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="45"/>
</p>

<p align="center">
Prometheus • Grafana
</p>

---
### DevSecOps Architecture

![DevSecOps Architecture](./Assets/architectures.png)
---

### 🔄 CI/CD Flow

![CI/CD Flow](./Assets/flow.png)

---

🔄 CI Pipeline (Jenkins)

✔ Code Checkout
✔ Trivy Filesystem Scan
✔ OWASP Dependency Check
✔ SonarQube Code Analysis
✔ Docker Image Build
✔ Docker Push to DockerHub

🚀 CD Pipeline (GitOps with ArgoCD)

✔ Update Kubernetes Manifests
✔ Push Changes to GitHub
✔ ArgoCD Auto Sync
✔ Rolling Deployment to AWS EKS
✔ Zero Downtime Deployment

---

🧠 Key Features

✅ DevSecOps Integrated CI

✅ Automated Vulnerability Scanning

✅ GitOps Deployment Strategy

✅ Kubernetes Rolling Updates

✅ Monitoring Enabled

✅ Email Notifications

✅ Secure Credential Handling

✅ Fully Automated End-to-End Flow


## 📸 Screenshots

### CI Pipeline
![CI](https://github.com/user-attachments/assets/20542d8b-0701-43ed-b2f8-82f8ed28d053)

### CD Pipeline
![CD](https://github.com/user-attachments/assets/8fd13807-622e-45f7-af23-dcc1ba30ca5d)

### ArgoCD Deployment
<img width="1600" height="821" alt="ce20b568-bd23-49aa-b61d-627f8261567c" src="https://github.com/user-attachments/assets/a3c3d5b4-f0a2-40d3-85e7-d15fb0cb4ec2" />

<img width="1600" height="766" alt="d327e4f4-ca47-4cc9-b78f-269442647786" src="https://github.com/user-attachments/assets/cecb106a-69c0-4167-9a05-90d2df905c0d" />


<img width="1262" height="577" alt="e1d7215c-6958-48bb-bd38-c2400409bbb6" src="https://github.com/user-attachments/assets/beaa1226-1e7f-46ee-ba94-e6b544ac8508" />


## 📊 Monitoring & Observability

- Prometheus used for real-time metrics collection  
- Grafana dashboards for visualization of Kubernetes cluster and application performance  
- Monitored CPU, Memory, Pods, and Node-level metrics  
- Integrated alerting and performance tracking  

### 📸 Grafana Dashboard

<img width="1213" height="570" alt="image" src="https://github.com/user-attachments/assets/8430bfaf-0483-49d6-8021-49e78af24b88" />

<img width="1226" height="621" alt="image" src="https://github.com/user-attachments/assets/5d8f00f8-774c-4ba2-92c7-260640ee8349" />

---

## 📦 Project Flow

```text
Developer → GitHub → Jenkins (CI + Security Scan)
→ Docker Build → DockerHub → GitHub (Manifest Update)
→ ArgoCD → AWS EKS → Deployment 🚀
