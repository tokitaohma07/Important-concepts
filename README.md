# Important-concepts


## 🔑 1. Core DevOps & SRE Concepts

DevOps Culture & Principles

CI/CD (Continuous Integration, Continuous Delivery, Continuous Deployment)

Infrastructure as Code (IaC)

Shift-Left Testing, Automation First, Immutable Infrastructure


## SRE Mindset

SLIs, SLOs, SLAs – measuring reliability

Error Budgets – deciding when to stop releases and focus on stability

Toil Reduction – automating repetitive ops tasks

Incident Response – Monitoring, alerting, postmortems


## 🖥 2. Linux & Scripting

Linux basics: ls, cd, cat, tail -f, grep, find, ps, top, systemctl

File permissions: chmod, chown, umask

Process management: kill, nohup, journalctl

Shell scripting: variables, loops, functions, cron jobs

Python for automation: file handling, subprocess calls, AWS SDK (boto3)

## 🐙 3. Version Control (Git & GitHub)

Git Basics: clone, add, commit, push, pull, merge, rebase

Branching strategy: feature branch, main branch, hotfix branch

Webhooks & GitHub Actions (if asked)

Resolving conflicts, writing good commit messages

## 🐳 4. Containerization (Docker)

Docker basics: build, run, exec, logs, inspect

Writing optimized Dockerfiles (multi-stage builds)

Using .dockerignore

Docker Compose for local multi-container setup

Pushing & pulling images from Docker Hub/ECR

## 🐳 4. Containerization (Docker)

Docker basics: build, run, exec, logs, inspect

Writing optimized Dockerfiles (multi-stage builds)

Using .dockerignore

Docker Compose for local multi-container setup

Pushing & pulling images from Docker Hub/ECR

## ☸️ 5. Container Orchestration (Kubernetes / EKS)

Key Objects: Pod, ReplicaSet, Deployment, Service, ConfigMap, Secret

Networking: ClusterIP, NodePort, LoadBalancer

Scaling: kubectl scale, HPA

Observability: kubectl logs, kubectl describe, kubectl top pod

Rolling updates & rollbacks

Helm charts for packaging applications

## ☁️ 6. Cloud (AWS Focus)

Compute: EC2, Auto Scaling, Load Balancers

Containers: EKS (Amazon Kubernetes)

Storage: S3 (buckets, versioning, lifecycle rules)

Networking: VPC basics, Security Groups, IAM roles

CI/CD: CodeBuild, CodePipeline (if used)

Monitoring: CloudWatch metrics, logs, alarms

Security: IAM policies, least privilege, MFA

## 🛠 7. CI/CD Pipelines

Jenkins Pipeline (Declarative & Scripted)

Jenkinsfile, stages, steps, post-build actions

Integrating with GitHub for automated triggers (webhooks)

Docker build & push steps

Deployments to Kubernetes (kubectl inside Jenkins)

## 🏗 8. Infrastructure as Code (IaC)

Terraform

terraform init, plan, apply, destroy

Variables, Outputs, State files

Creating EC2, VPC, S3, IAM with Terraform

Ansible

Playbooks, Inventory, Roles

Ad-hoc commands for config management

## 📊 9. Monitoring & Observability

Prometheus

Scraping metrics, writing basic PromQL queries

Grafana

Creating dashboards, setting alerts

Logging

ELK / Splunk basics (search queries, alerts)

Incident Management

On-call rotations, Root Cause Analysis (RCA)

## 🔐 10. Security & Best Practices

Managing secrets (Kubernetes Secrets, AWS SSM Parameter Store)

Image scanning (Trivy, Anchore)

Role-based access control (RBAC) in Kubernetes

SSL/TLS basics


## 🗺 DevOps + SRE Roadmap for Quick Recall

```Linux & Scripting  →  Git & GitHub  →  CI/CD (Jenkins)  →  
Docker & Images  →  Kubernetes (EKS)  →  
Terraform & Ansible (IaC)  →  
AWS Cloud (Core Services)  →  
Monitoring (Prometheus, Grafana, Splunk)  →  
SRE Concepts (SLI, SLO, Incident Mgmt)
