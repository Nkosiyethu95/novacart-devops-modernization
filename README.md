# Novacart-devops-modernization

# Project Overview

This project focuses on modernizing a manually managed application environment into a scalable, automated, and observable cloud-native platform on AWS.

The goal is to improve deployment consistency, scalability, monitoring, security, and infrastructure reliability using modern DevOps and Kubernetes practices.

# Current Challenges
Manual deployments through SSH
Downtime during updates
Scaling limitations
Inconsistent deployment processes
Limited monitoring and centralized logging

# Planned Technology Stack
Cloud & Infrastructure
AWS
Amazon VPC
Public & Private Subnets
NAT Gateway
IAM & Security Groups

# Container & Orchestration
Docker
Kubernetes
Amazon EKS
Ingress Controller
Horizontal Pod Autoscaler

# CI/CD & Automation
Jenkins
GitHub
Amazon ECR

# Monitoring & Logging
Prometheus
Grafana
Centralized Logging

# Database
PostgreSQL

# Architecture Focus Areas
Scalable cloud-native infrastructure
Automated deployments
Secure networking
Infrastructure observability
Deployment consistency
High availability & reliability

# CI/CD Workflow

GitHub → Jenkins → Docker → Amazon ECR → Amazon EKS

# Project Rollout Phases

Phase 1 — Foundation & AWS Setup
AWS networking architecture
VPC & subnet configuration
IAM & security setup
Bastion/admin access strategy

Phase 2 — Kubernetes Environment
Amazon EKS cluster setup
Kubernetes namespaces
Ingress & load balancing
Application deployments

Phase 3 — CI/CD Pipeline Automation
Jenkins pipeline integration
Automated build & deployment workflows
Docker image builds & ECR integration

Phase 4 — Monitoring & Logging
Prometheus monitoring
Grafana dashboards
Centralized logging & observability

Phase 5 — Optimization & Documentation
Cost optimization
Security hardening
Backup & rollback strategy
Final project documentation

