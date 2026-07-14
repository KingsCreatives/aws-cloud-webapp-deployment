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

<img width="1601" height="961" alt="project 1 Tomcat drawio" <mxfile host="app.diagrams.net">
  <diagram name="AWS Architecture" id="TUeFtn19Z1ZKDR0Zw8TX">
    <mxGraphModel dx="1720" dy="1022" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="w_o_IY18bLiY0d2c7FIp-1" parent="1" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#F54749;gradientDirection=north;fillColor=#BC1356;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.users;" value="Internet Users" vertex="1">
          <mxGeometry height="60" width="60" x="620" y="20" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-2" parent="1" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;fontSize=12;" value="Developer" vertex="1">
          <mxGeometry height="50" width="140" x="20" y="80" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-3" parent="1" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#d5e8d4;strokeColor=#82b366;fontSize=12;" value="Trello (Project Mgmt)" vertex="1">
          <mxGeometry height="50" width="140" x="20" y="180" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-4" parent="1" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;fontSize=12;" value="GitHub Repository" vertex="1">
          <mxGeometry height="50" width="140" x="20" y="320" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-5" parent="1" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;fontSize=12;" value="GitHub Actions (CI/CD)" vertex="1">
          <mxGeometry height="50" width="140" x="20" y="440" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-6" parent="1" style="points=[[0,0,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0,0],[0,1,0],[0.25,1,0],[0.5,1,0],[0.75,1,0],[1,1,0],[0,0.25,0],[0,0.5,0],[0,0.75,0],[1,0.25,0],[1,0.5,0],[1,0.75,0]];outlineConnect=0;html=1;whiteSpace=wrap;fontSize=12;fontStyle=0;container=1;pointerEvents=0;collapsible=0;recursiveResize=0;shape=mxgraph.aws4.group;grIcon=mxgraph.aws4.group_aws_cloud_alt;strokeColor=#232F3E;fillColor=none;verticalAlign=top;align=left;spacingLeft=30;fontColor=#232F3E;dashed=0;" value="AWS Cloud" vertex="1">
          <mxGeometry height="900" width="1180" x="260" y="80" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-7" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#8C4FFF;gradientDirection=north;fillColor=#8C4FFF;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.route_53;" value="Amazon Route 53" vertex="1">
          <mxGeometry height="60" width="60" x="620" y="40" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-8" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#BF0816;gradientDirection=north;fillColor=#BF0816;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.certificate_manager;" value="AWS Certificate Manager" vertex="1">
          <mxGeometry height="60" width="60" x="760" y="40" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-9" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#8C4FFF;gradientDirection=north;fillColor=#8C4FFF;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.cloudfront;" value="Amazon CloudFront" vertex="1">
          <mxGeometry height="60" width="60" x="620" y="140" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-10" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#DD344C;gradientDirection=north;fillColor=#DD344C;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.waf;" value="AWS WAF" vertex="1">
          <mxGeometry height="60" width="60" x="620" y="240" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-12" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#8C4FFF;gradientDirection=north;fillColor=#8C4FFF;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.application_load_balancer;" value="Application Load Balancer" vertex="1">
          <mxGeometry height="60" width="60" x="620" y="340" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-13" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#DD344C;gradientDirection=north;fillColor=#DD344C;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.identity_and_access_management;" value="IAM Roles" vertex="1">
          <mxGeometry height="60" width="60" x="1300" y="40" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-14" parent="w_o_IY18bLiY0d2c7FIp-6" style="points=[[0,0,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0,0],[0,1,0],[0.25,1,0],[0.5,1,0],[0.75,1,0],[1,1,0],[0,0.25,0],[0,0.5,0],[0,0.75,0],[1,0.25,0],[1,0.5,0],[1,0.75,0]];outlineConnect=0;html=1;whiteSpace=wrap;fontSize=12;fontStyle=0;container=1;pointerEvents=0;collapsible=0;recursiveResize=0;shape=mxgraph.aws4.group;grIcon=mxgraph.aws4.group_vpc2;strokeColor=#248814;fillColor=none;verticalAlign=top;align=left;spacingLeft=30;fontColor=#248814;dashed=0;" value="VPC" vertex="1">
          <mxGeometry height="400" width="900" x="60" y="440" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-15" parent="w_o_IY18bLiY0d2c7FIp-14" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#8C4FFF;gradientDirection=north;fillColor=#8C4FFF;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.internet_gateway;" value="Internet Gateway" vertex="1">
          <mxGeometry height="60" width="60" x="420" y="30" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-16" parent="w_o_IY18bLiY0d2c7FIp-14" style="points=[[0,0,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0,0],[0,1,0],[0.25,1,0],[0.5,1,0],[0.75,1,0],[1,1,0],[0,0.25,0],[0,0.5,0],[0,0.75,0],[1,0.25,0],[1,0.5,0],[1,0.75,0]];outlineConnect=0;html=1;whiteSpace=wrap;fontSize=12;fontStyle=0;container=1;pointerEvents=0;collapsible=0;recursiveResize=0;shape=mxgraph.aws4.group;grIcon=mxgraph.aws4.group_security_group;strokeColor=#248814;fillColor=#E9F3E6;verticalAlign=top;align=left;spacingLeft=30;fontColor=#248814;dashed=0;" value="Availability Zone A - Public Subnet" vertex="1">
          <mxGeometry height="220" width="350" x="60" y="140" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-17" parent="w_o_IY18bLiY0d2c7FIp-16" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#ED7100;gradientDirection=north;fillColor=#ED7100;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.ec2;" value="EC2 Instance (Web Server A)" vertex="1">
          <mxGeometry height="60" width="60" x="60" y="60" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-18" parent="w_o_IY18bLiY0d2c7FIp-16" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#DD344C;gradientDirection=north;fillColor=#DD344C;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.security_group;" value="Security Group" vertex="1">
          <mxGeometry height="60" width="60" x="200" y="60" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-19" parent="w_o_IY18bLiY0d2c7FIp-14" style="points=[[0,0,0],[0.25,0,0],[0.5,0,0],[0.75,0,0],[1,0,0],[0,1,0],[0.25,1,0],[0.5,1,0],[0.75,1,0],[1,1,0],[0,0.25,0],[0,0.5,0],[0,0.75,0],[1,0.25,0],[1,0.5,0],[1,0.75,0]];outlineConnect=0;html=1;whiteSpace=wrap;fontSize=12;fontStyle=0;container=1;pointerEvents=0;collapsible=0;recursiveResize=0;shape=mxgraph.aws4.group;grIcon=mxgraph.aws4.group_security_group;strokeColor=#248814;fillColor=#E9F3E6;verticalAlign=top;align=left;spacingLeft=30;fontColor=#248814;dashed=0;" value="Availability Zone B - Public Subnet" vertex="1">
          <mxGeometry height="220" width="350" x="480" y="140" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-20" parent="w_o_IY18bLiY0d2c7FIp-19" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#ED7100;gradientDirection=north;fillColor=#ED7100;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.ec2;" value="EC2 Instance (Web Server B)" vertex="1">
          <mxGeometry height="60" width="60" x="60" y="60" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-21" parent="w_o_IY18bLiY0d2c7FIp-19" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#DD344C;gradientDirection=north;fillColor=#DD344C;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.security_group;" value="Security Group" vertex="1">
          <mxGeometry height="60" width="60" x="200" y="60" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-22" parent="w_o_IY18bLiY0d2c7FIp-14" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=#d6b656;dashed=1;fontSize=11;fontStyle=2;" value="Auto Scaling Group (min 2 instances) - spans both AZs" vertex="1">
          <mxGeometry height="30" width="630" x="150" y="380" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-23" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#7AA116;gradientDirection=north;fillColor=#7AA116;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.s3;" value="Amazon S3 (Static Assets)" vertex="1">
          <mxGeometry height="60" width="60" x="1020" y="440" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-24" parent="w_o_IY18bLiY0d2c7FIp-6" style="sketch=0;outlineConnect=0;fontColor=#232F3E;gradientColor=#E7157B;gradientDirection=north;fillColor=#E7157B;strokeColor=#ffffff;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;fontSize=11;fontStyle=0;aspect=fixed;shape=mxgraph.aws4.resourceIcon;resIcon=mxgraph.aws4.cloudwatch;" value="Amazon CloudWatch" vertex="1">
          <mxGeometry height="60" width="60" x="1020" y="600" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-25" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;" target="w_o_IY18bLiY0d2c7FIp-7" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-26" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;" target="w_o_IY18bLiY0d2c7FIp-9" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-27" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;" target="w_o_IY18bLiY0d2c7FIp-9" value="TLS Cert">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-28" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-9" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;" target="w_o_IY18bLiY0d2c7FIp-10" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-29" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-10" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;" target="w_o_IY18bLiY0d2c7FIp-12" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-31" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-12" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;" target="w_o_IY18bLiY0d2c7FIp-17" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-32" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-12" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;" target="w_o_IY18bLiY0d2c7FIp-20" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-33" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-9" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-23" value="serves static content">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-34" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-17" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-23" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-35" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-20" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-23" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-36" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-15" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#232F3E;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-12" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-37" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=10;strokeColor=#E7157B;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-12" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-38" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=10;strokeColor=#E7157B;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-17" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-39" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=10;strokeColor=#E7157B;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-20" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-40" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=10;strokeColor=#E7157B;dashed=1;" target="w_o_IY18bLiY0d2c7FIp-9" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-41" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#1a73e8;" target="w_o_IY18bLiY0d2c7FIp-3" value="manages tasks">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-42" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#1a73e8;" target="w_o_IY18bLiY0d2c7FIp-4" value="pushes code">
          <mxGeometry relative="1" x="0.4737" as="geometry">
            <mxPoint as="offset" />
            <Array as="points">
              <mxPoint x="90" y="220" />
              <mxPoint x="90" y="220" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-43" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#1a73e8;" target="w_o_IY18bLiY0d2c7FIp-5" value="triggers">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-44" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-5" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#1a73e8;exitX=1;exitY=0.5;entryX=0;entryY=0.7;" target="w_o_IY18bLiY0d2c7FIp-17" value="deploys">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="w_o_IY18bLiY0d2c7FIp-45" edge="1" parent="1" source="w_o_IY18bLiY0d2c7FIp-5" style="edgeStyle=orthogonalEdgeStyle;rounded=0;html=1;fontSize=11;strokeColor=#1a73e8;exitX=1;exitY=0.5;entryX=0;entryY=0.3;" target="w_o_IY18bLiY0d2c7FIp-20" value="deploys">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
src="https://github.com/user-attachments/assets/263203c8-bcad-4748-b1e3-22e7e5e69843" />
[project 1 Tomcat.drawio](https://github.com/user-attachments/files/29968797/project.1.Tomcat.drawio)
