<div align="center">

# ☁️ End-to-End AWS Cloud Web Application Deployment

### Team TomCat 🐱

**Building a Secure, Scalable & Highly Available Cloud Solution on AWS**

![AWS](https://img.shields.io/badge/AWS-Free%20Tier-orange?logo=amazonaws)
![EC2](https://img.shields.io/badge/EC2-Compute-yellow)
![S3](https://img.shields.io/badge/S3-Storage-green)
![CloudFront](https://img.shields.io/badge/CloudFront-CDN-blue)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-black?logo=github)
![Trello](https://img.shields.io/badge/Trello-Project%20Management-blue?logo=trello)

---

### 🚀 Project Status

| Phase | Status |
|:------|:------:|
| Environment Setup | 🟢 Completed |
| Infrastructure Deployment | 🟡 In Progress |
| Load Balancer | ⚪ Pending |
| CloudFront CDN | ⚪ Pending |
| CI/CD Pipeline | ⚪ Pending |

</div>

---

# 📖 Overview

This project is part of our cloud engineering practical where **Team TomCat** is designing, architecting, and deploying a production-inspired web application using **Amazon Web Services (AWS)**.

Our goal is to build a solution that is:

- 🔒 Secure
- ⚡ High Performance
- 📈 Scalable
- 🌍 Highly Available
- 💰 AWS Free Tier Friendly

Throughout this project, we are applying cloud architecture best practices while collaborating using GitHub and Trello.

---

# 🏗️ Architecture

```text
                 🌍 Users
                    │
              HTTPS Request
                    │
          ☁️ Amazon CloudFront
                    │
                    ▼
      ⚖️ Application Load Balancer
                    │
         ┌──────────┴──────────┐
         │                     │
      EC2 Instance         EC2 Instance
         │
      Web Application
         │
         ▼
     Amazon S3
 Static Assets (Images, CSS, JS)
```

---

# 🎯 Project Objectives

- Deploy a web application on AWS
- Configure secure IAM access
- Host compute resources on EC2
- Store static assets in Amazon S3
- Improve performance with CloudFront
- Secure traffic with HTTPS (ACM)
- Automate deployments with GitHub Actions
- Collaborate efficiently using GitHub and Trello

---

# 🛠️ Technology Stack

| Category | Technology |
|-----------|------------|
| Cloud Provider | AWS |
| Compute | Amazon EC2 |
| Storage | Amazon S3 |
| CDN | Amazon CloudFront |
| Load Balancing | Application Load Balancer |
| Security | IAM, ACM |
| Version Control | Git & GitHub |
| Project Management | Trello |
| Development | VS Code |

---

# 📂 Repository Structure

```text
aws-cloud-webapp-deployment/

├── docs/
├── screenshots/
├── src/
├── README.md
└── .gitignore
```

---

# 🌿 Git Workflow

```text
main
 │
 └── develop
        │
        ├── feature/setup
        ├── feature/ec2
        ├── feature/s3
        ├── feature/alb
        └── feature/cloudfront
```

---

# 👥 Team Collaboration

Our team follows a feature-based Git workflow.

1. Create a feature branch
2. Implement the task
3. Push changes
4. Open a Pull Request
5. Review and merge into `develop`
6. Merge `develop` into `main` after testing

---

# ⚙️ Environment

| Item | Value |
|------|-------|
| AWS Region | *To be Updated* |
| EC2 Instance | t2.micro |
| Operating System | Ubuntu Server |
| IDE | VS Code |
| AWS CLI | Configured |
| Git | Installed |

---

# 📸 Project Screenshots

| AWS Console | GitHub | Trello |
|-------------|---------|---------|
| 🚧 Coming Soon | 🚧 Coming Soon | 🚧 Coming Soon |

---

# 📚 Learning Outcomes

By completing this project we will gain practical experience with:

- AWS Identity & Access Management (IAM)
- Amazon EC2
- Amazon S3
- Application Load Balancer
- Amazon CloudFront
- AWS Certificate Manager
- GitHub Actions
- Cloud Networking
- Infrastructure Security
- Team Collaboration

---

# 🚀 Future Improvements

- Auto Scaling Groups
- Route 53
- AWS WAF
- CloudWatch Monitoring
- Terraform
- Docker
- Kubernetes

---

# 👨‍💻 Team TomCat

| Name | Role |
|------|------|
| Member 1 | Cloud Engineer |
| Member 2 | Cloud Engineer |
| Member 3 | Cloud Engineer |
| Member 4 | Cloud Engineer |

---

<div align="center">

### ⭐ If you find this project interesting, feel free to star the repository!

Built with ❤️ by **Team TomCat**

</div>