# DevOps-Learning-Path
This repository is a 2 month step-by-step daily plan to get a solid understanding of everything DevOps from Foundations, to Kubernetes all the way to Reliability &amp; SRE. 

## What is DevOps? What do DevOps developers do?
- DevOps is a set of practices. It is a culture within a team or company. Many people are quick to define DevOps by lsiting off a laundry list of technologies but that's not correct at all. DevOps is the practice and those technologies are the tools that help us achieve a DevOps Environment.
- It is a combination of thing's, it's a mix of the practices and tools used to increase the delivery and deployment of software. A DevOps team tries to simplify and automate each step in the software lifecycle just to make everything faster and give developers peace of mind during lifecycle steps.
  
## What are the benefits of DevOps?
- Collaboration across teams (Devs, QA, etc.)
- Improved delivery
- Security
- Speed
- Scale
- Reliability
- Automated development cycle
- Ease of use
- Markup costs for companies on finding bugs early on

 <img width="549" height="312" alt="1_UN3_vDPpkqhznJfXO4VmvA" src="https://github.com/user-attachments/assets/c551e0c3-0969-461f-b483-d31f01a88dad" />



# Table of Contents

### WEEK 1 - Linux & Git
- [ ] [Linux](#linux)
- [ ] [Bash Scripting](#bash-scripting)
- [ ] [Git Fundamentals](#git-fundamentals)
- [ ] [Networking 101](#networking)
- [ ] [HANDS-ON EXERCISE](#hands-on-exercise)

### WEEK 2 - Docker & CI/CD
- [ ] [Docker Basics](#docker-basics)
- [ ] [Docker Compose](#docker-compose)
- [ ] [Docker registries](#docker-registries)
- [ ] [GHA Basics](#gha-basics)
- [ ] [Build a pipeline that lints/tests containerized apps](#build-a-pipeline-that-lintstests-a-containerized-app)
- [ ] [Push Image to DockerHub/Github container Registry](#push-docker-image-to-dockerhubgithub-container-registry)
- [ ] [Containerized API & CI workflow mini project](#containerized-api--ci-workflow-mini-project)

### WEEK 3 - Terraform (IaC)
- [ ] [Terraform Basics(providers, resources, variables](#terraform-basics)
- [ ] [Provision computer + netowrking in AWS/GCP/Azure](#provisioning-in-aws)
- [ ] [Manage IAM & Secrets with Terraform](#manage-iam-secrets)
- [ ] [Terraform modules + outputs](#terraform-modules)
- [ ] [Mini-Project: Reusable Terraform infra (VM + VPC)](#mini-project)
- [ ] [Review + commit configs to GitHub](#review-iac-repo-cleanup--reapply)

### WEEK 4 - Kubernetes (part 1)
- [ ] [Kubernetes Basics (pods, deployments, services)](#kubernetes-basics)
- [ ] [ConfigMaps & Secrets](#configmaps--secrets)
- [ ] [Ingress controllers(Expose app)](#ingress-controllers)
- [ ] [Helm Basics(Package chart)](#helm-basics)
- [ ] [Helm advanced (values + install chart)](#helm-advanced)
- [ ] [Deploy app to local cluster(Minikube/Kind)](#review-deploy-app-to-local-cluster)

### WEEK 5 - Kubernetes (part 2) + GitOps
- [ ] [GitOps (Flux Basics)](#flux-basics)
- [ ] [Bootstrap GitOps repo (Sync manifests from Git)](#bootstrap-gitops-repo)
- [ ] [Secrets Management (Sealed Secrets/SOPS)](#secrets-management)
- [ ] [Cloud Basics (IAM + storage + VM (AWS)](#cloud-basics)
- [ ] [GitOps on cloud cluster (deploy via Gitops to EKS/AWS)](#gitops-on-cloud-cluster)
- [ ] [Review (Gitops repo drives deployment)](#review-gitops-repo-drives-deployment)

### WEEK 6 - Monitoring & Logging
- [ ] [Prometheus Basics](#prometheus-basics)
- [ ] [Grafana dashboards](#grafana-dashboards)
- [ ] [Logging Stack (ELK)](#logging-with-elk)
- [ ] [Alerts (Prometheus Alertmanager/Grafana alerts](#prometheus-alertmanager--grafana-alerts)
- [ ] [Exporters](#exporters)
- [ ] [Review (dashoards + alerts working](#review-dashboards--alerts-working)

### WEEK 7 - SRE & Reliability
- [ ] [SLOs & SLIs](#slos--slis-define-service-objectives)
- [ ] [Incident reponse basics](#incident-response)
- [ ] [Postmortems](#postmortems)
- [ ] [Chaos Testing](#chaos-testing-kill-pod-disrupt-cluster-observe-recovery)
- [ ] [Runbooks & ops docs](#runbooks--ops-docs-write-operational-steps)
- [ ] [Review (full SRE toolkit)](#review-full-sre-toolkit)

### WEEK 8 - Capstone & Security
- [Capstone Infra (Terraform cluster + DB)](#capstone-infra)
- [Capstone CI/CD (pipeline builds & pushses image)](#capstone-cicd)
- [Capstone deploy(Helm chart to cloud cluster](#capstone-deploy)
- [Capstone GitOps (sync deploy froms Gt)](#capstone-gitops)
- [Observability (dashboards + alerts for app)](#observability)
- [Security Basics (scan Docker images(Trivy)](#security-basics)
- [IaC security (tfsec/Checkov on Terraform code)](#iac-security)
- [Documentation (README + diagrams of setup)](#documentation)
- [Final demo (present full system)](#final-demo)
  
# Linux & Git
### Linux
 - [Linux Upskill Challenge](https://linuxupskillchallenge.org/) - This was used as a guide to learn the skills required to sysadmin a remote Linux server from the command line

### Bash Scripting

### Git Fundamentals

### Networking 

### Hands On Exercise
    ---

# Docker & CI/CD
### Docker Basics

### Docker Compose

### Docker Registries

### GHA Basics

### Build a pipeline that lints/tests a containerized app

### Push Docker image to DockerHub/Github Container registry

### Containerized API & CI workflow mini project
    ---

# Terraform (IaC)
### Terraform Basics

### Provisioning In AWS

### Manage IAM Secrets

### Terraform Modules 

### Mini Project

### Review (IaC repo cleanup & reapply)
    ---

# Kubernetes (part 1)
### Kubernetes basics

### ConfigMaps & Secrets

### Ingress controllers

### Helm basics

### Helm advanced

### Review (deploy app to local cluster)
    ---

# Kubernetes (part 2) + GitOps
### Flux Basics

### Bootstrap GitOps repo

### Secrets management

### Cloud basics

### GitOps on cloud cluster

### Review (GitOps repo drives deployment)
    ---

# Monitoring & Logging

### Prometheus basics

### Grafana dashboards

### Logging with ELK

### Prometheus Alertmanager & Grafana alerts

### Exporters

### Review (dashboards + alerts working)
    ---

# SRE & Reliability

### SLOs & SLIs (define service objectives)

### Incident response

### Postmortems 

### Chaos Testing (kill pod, disrupt cluster, observe recovery)

### Runbooks & ops docs (write operational steps)

### Review (full SRE toolkit)
    ---

# CAPSTONE & Security

### Capstone infra 

### Capstone CI/CD 

### Capstone deploy

### Capstone GitOps

### Observability

### Security basics

### IaC security

### Documentation

## Final demo 




































