<div dir="ltr" align="left">

# Proposed AWS Cloud Architecture & Tech Stack

## 🏗️ System Architecture Overview
The new architecture transforms the legacy monolith into a fully stateless, containerized, and scalable cloud infrastructure on AWS.
---

## 🛠️ Technology Stack & AWS Services
- **Compute:** AWS ECS (Fargate) for Serverless Container Orchestration.
- **Database:** AWS RDS PostgreSQL (Multi-AZ for High Availability & Automated Backups).
- **Caching:** AWS ElastiCache (Redis) for Session Management & DB Query Caching.
- **Object Storage:** AWS S3 Bucket for Media Storage (Decoupled Storage).
- **CDN & Security:** AWS CloudFront + AWS WAF & Shield (DDoS Protection & SSL/TLS).
- **IaC (Infrastructure as Code):** Terraform.
- **CI/CD:** GitHub Actions (Automated Testing & Rolling Deployments).

---

## 👥 Team Work Breakdown (Execution Plan)

| Engineer Role | Responsibilities & Deliverables |
| :--- | :--- |
| **Engineer 1: App & Containers** | Dockerize React Frontend & Node.js Backend (`Dockerfile`, `docker-compose.yml`). |
| **Engineer 2: Cloud Infrastructure** | Write Infrastructure as Code (`Terraform` scripts for ECS, RDS, S3, ALB, Redis). |
| **Engineer 3: CI/CD & Automation** | Configure GitHub Actions Workflows (`.github/workflows/deploy.yml`) for Auto Deployment. |

</div>
