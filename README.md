# 🚀 DevOps Learning Roadmap

This repository provides a **complete DevOps learning roadmap** for beginners, covering tools, technologies, and the DevOps lifecycle in a structured way.

It is useful for:
- Learning DevOps step by step
- GitHub portfolio
- LinkedIn DevOps posts
- Interview preparation

---

## 🎯 What is DevOps?

DevOps is a combination of **Development** and **Operations** that focuses on:

- Faster software delivery  
- Automation  
- Collaboration between teams  
- Stability and scalability of systems  

---

## 🧭 DevOps Learning Roadmap (Flowchart)

> ⚠️ Note:  
> Mermaid diagrams work on **GitHub**, **GitLab**, and Markdown editors that support Mermaid.

```mermaid
flowchart TD

    %% DevOps Purpose
    A[DevOps Goal]
    A --> A1[Faster Delivery]
    A --> A2[Automation]
    A --> A3[Collaboration]
    A --> A4[Stability & Scalability]

    %% Learning Roadmap
    A --> B[DevOps Learning Roadmap]

    %% Linux Fundamentals
    B --> C[Linux Fundamentals]
    C --> C1[Linux Commands]
    C --> C2[Networking Basics]
    C --> C3[Shell Scripting]

    %% Version Control
    C --> D[Version Control System]
    D --> D1[Git]
    D --> D2[GitHub]

    %% CI/CD Automation
    D --> E[CI/CD Automation]
    E --> E1[Jenkins]
    E --> E2[GitHub Actions]

    %% Containers
    E --> F[Containers]
    F --> F1[Docker]

    %% Container Orchestration
    F --> G[Container Orchestration]
    G --> G1[Kubernetes]

    %% Cloud Platform
    G --> H[Cloud Platform]
    H --> H1[AWS EC2]
    H --> H2[AWS S3]
    H --> H3[IAM]
    H --> H4[VPC]
    H --> H5[CloudWatch]

    %% Monitoring & Logging
    H --> I[Monitoring & Logging]
    I --> I1[Prometheus]
    I --> I2[Grafana]

    %% DevOps Lifecycle
    I --> J[DevOps Lifecycle]
    J --> J1[Plan]
    J1 --> J2[Code]
    J2 --> J3[Build]
    J3 --> J4[Test]
    J4 --> J5[Release]
    J5 --> J6[Deploy]
    J6 --> J7[Operate]
    J7 --> J8[Monitor]
    J8 --> J1

    %% Outcome
    J --> K[Production Ready Systems]
    K --> L[Continuous Improvement]
