<div align="center">

# End-to-End Cloud Solution Design & Deployment

### Team TomCat

**A secure, scalable, and highly available AWS cloud architecture engineered for EMBER & ROOT Kitchen**

![AWS](https://img.shields.io/badge/AWS-Free%20Tier-FF9900?logo=amazonaws&logoColor=white)
![CloudFront](https://img.shields.io/badge/Amazon_CloudFront-232F3E?logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?logo=amazonec2&logoColor=white)
![S3](https://img.shields.io/badge/Amazon_S3-569A31?logo=amazons3&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?logo=trello&logoColor=white)

</div>

---

## Executive Summary

EMBER & ROOT Kitchen's legacy web infrastructure was struggling to keep pace with growing customer demand, manual deployments, single points of failure, and no defined scaling strategy left the business exposed to downtime and slow performance during peak traffic.

**Team TomCat** was engaged to re-architect this infrastructure from the ground up. The result is a production-grade AWS environment built on the Well-Architected Framework's pillars of reliability, security, performance efficiency, and cost optimization,delivered entirely within the AWS Free Tier to demonstrate that enterprise-grade architecture doesn't require enterprise-grade budgets.

This repository documents the full engineering lifecycle: architecture design, infrastructure provisioning, deployment automation, security hardening, and performance validation.

---

## The Business Problem

EMBER & ROOT Kitchen's existing web application suffered from a set of interconnected reliability and operational risks:

| Pain Point | Business Impact |
|---|---|
| Slow page load times | Poor customer experience, lost conversions |
| Downtime during traffic spikes | Missed orders, reputational damage |
| Limited scalability | Inability to grow with demand |
| Manual deployment processes | Slower release cycles, higher error risk |
| Security vulnerabilities | Exposure to data breaches and attacks |

**Objective:** Deliver a secure, highly available, horizontally scalable, and cost-efficient cloud solution that removes these constraints and positions FreshBite Kitchen for sustained growth.

---

## Engineered Solution

Team TomCat designed a multi-tier AWS architecture, engineered around the following core services:

- **Amazon EC2** — Scalable application compute
- **Amazon S3** — Durable static asset storage
- **Amazon CloudFront** — Global content delivery and edge caching
- **Application Load Balancer (ALB)** — Intelligent traffic distribution across Availability Zones
- **AWS Certificate Manager (ACM)** — Managed SSL/TLS encryption
- **AWS Identity and Access Management (IAM)** — Least-privilege access control
- **Amazon CloudWatch** — Real-time monitoring, logging, and alerting
- **GitHub Actions** — Automated CI/CD pipeline
- **Trello** — Agile project and sprint management

Together, these services form a resilient, defense-in-depth architecture spanning global content delivery, automated deployment, continuous monitoring, and multi-layered security.

---

## Solution Architecture

<div align="center">

### AWS Architecture Diagram

![FreshBite AWS Architecture](docs/architecture.png)

</div>

---

### Architecture Components

| Service | Purpose |
|---|---|
| Amazon Route 53 | DNS routing and domain management |
| AWS Certificate Manager | SSL/TLS certificate issuance and renewal |
| Amazon CloudFront | Global content delivery network (CDN) |
| AWS WAF | Web application firewall — filters malicious traffic |
| Application Load Balancer | Distributes traffic across multiple Availability Zones |
| Amazon EC2 | Hosts the core application layer |
| Amazon S3 | Stores and serves static assets |
| Amazon CloudWatch | Centralized monitoring, metrics, and logging |
| AWS IAM | Manages identities, roles, and permissions |
| GitHub Actions | Automates build, test, and deployment |
| Trello | Coordinates sprint planning and task tracking |

---

## High Availability & Fault Tolerance

The application is deployed across **multiple Availability Zones** behind an Application Load Balancer, eliminating single points of failure. If one AZ experiences an outage, traffic is automatically rerouted to healthy instances — ensuring continuity of service with no manual intervention required.

---

## Deployment Pipeline

A fully automated CI/CD workflow moves code from commit to production with no manual handoffs:

```text
Developer Push
      │
      ▼
GitHub Repository
      │
      ▼
GitHub Actions (Build & Test)
      │
      ▼
Amazon EC2 (Deploy)
      │
      ▼
Application Load Balancer (Distribute Traffic)
      │
      ▼
Amazon CloudFront (Cache & Deliver Globally)
      │
      ▼
End Users
```

---

## Technology Stack

| Category | Technology |
|---|---|
| Cloud Platform | Amazon Web Services (AWS) |
| Compute | Amazon EC2 |
| Storage | Amazon S3 |
| Content Delivery | Amazon CloudFront |
| Load Balancing | Application Load Balancer |
| Monitoring & Observability | Amazon CloudWatch |
| Security | IAM · ACM · AWS WAF |
| Version Control | Git & GitHub |
| CI/CD | GitHub Actions |
| Project Management | Trello |

---

## Project Roadmap

### Milestone 1 — Foundation & Environment Setup
- AWS account configuration and billing guardrails
- IAM users, roles, and least-privilege permissions
- AWS CLI configuration
- GitHub repository and branching strategy
- Trello board and sprint structure
- EC2 instance provisioning
- S3 bucket creation
- ACM certificate request
- Project documentation

### Milestone 2 — Application Deployment
- Deploy application to Amazon EC2
- Configure target groups for load balancing
- Configure Application Load Balancer
- Enforce HTTP → HTTPS redirection
- Upload and configure static assets in Amazon S3
- Validate application health checks

### Milestone 3 — Security Hardening & Performance Optimization
- Configure Amazon CloudFront distribution
- Restrict direct origin access (origin isolation)
- Enforce end-to-end HTTPS encryption
- Configure and tune caching policies
- Establish CloudWatch monitoring and alerting

---

## Project Status

| Component | Status |
|---|:---:|
| Environment Setup | ✅ Completed |
| Application Deployment | ✅ Completed |
| Application Load Balancer | ✅ Completed |
| Amazon S3 Integration | ✅ Completed |
| Amazon CloudFront | ✅ Completed |
| Security Hardening | 🔄 In Progress |
| CI/CD Pipeline | 🔄 In Progress |

---

## CloudFront Configuration

| Property | Configuration |
|---|---|
| Origin | Application Load Balancer |
| Viewer Protocol Policy | Redirect HTTP to HTTPS |
| Origin Protocol Policy | HTTP Only |
| SSL/TLS Certificate | AWS Certificate Manager |

### Cache Policies

| Content Type | Cache Policy |
|---|---|
| Static Assets | Managed-CachingOptimized |
| Dynamic Content | Managed-CachingDisabled |

---

## Git Branching Strategy

```text
main
│
└── develop
     ├── feature/setup
     ├── feature/ec2
     ├── feature/s3
     ├── feature/alb
     ├── feature/cloudfront
     └── feature/github-actions
```

Feature branches are merged into `develop` for integration testing before promotion to `main` for production release.

---

## Repository Structure

```text
.
├── docs/
│   └── architecture.png
├── screenshots/
├── src/
├── index.html
├── README.md
└── .gitignore
```

---

## Team TomCat

| Member | Role |
|---|---|
| David Quayartey | Team Lead |
| Samuel Kingsford Amoah | GitHub Manager |
| Emmanuel Akatse | AWS Administrator |
| Peter Nartey | Infrastructure Engineer |
| Nunoo Annah Frimpomaah | Security & Documentation |
| Salu Alhassan | CloudFront Specialist |

---

## Project Screenshots

| Component | Status |
|---|---|
| Amazon EC2 | Coming Soon |
| Amazon S3 | Coming Soon |
| Application Load Balancer | Coming Soon |
| Amazon CloudFront | Coming Soon |
| Final Deployment | Coming Soon |

---

<div align="center">

**Team TomCat**

*Building secure, scalable, and reliable cloud solutions through collaboration and engineering best practices.*

</div>
