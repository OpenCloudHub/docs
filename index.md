---
title: Home
layout: home
---

# OpenCloudHub
{: .fs-9 .mb-6 }

A master's thesis project exploring modern cloud-native MLOps platform engineering.
{: .fs-6 .fw-300 .text-grey-dk-100 .mb-8 }

---

## About This Project

OpenCloudHub is a research-driven MLOps platform being developed as part of a master's thesis in Computer Science. The project explores how to build modern, cloud-native infrastructure for machine learning workflows—bridging the gap between academic experimentation and production-ready systems.

## What We're Building

A comprehensive MLOps platform on Kubernetes that demonstrates the complete machine learning lifecycle. The platform showcases end-to-end system architecture, infrastructure-as-code, and modern DevOps practices for both traditional ML and generative AI models.

**Key Technologies:**
- **Kubernetes** - Container orchestration
- **GitOps with ArgoCD** - Deployment automation
- **MLflow** - Experiment tracking and model registry
- **KServe** - Model serving infrastructure
- **Prometheus/Grafana** - Monitoring and observability
- **Keycloak** - Authentication and authorization
- **Gateway API & Istio** - Traffic management and service mesh
- **CloudnativePG & MinIO** - Database and object storage
- **Terraform/Terragrunt** - Infrastructure as code

## Research Focus

This thesis explores several key questions:

- How do modern cloud-native technologies integrate into cohesive platforms?
- What does comprehensive Kubernetes platform engineering look like in practice?
- How do MLOps workflows drive platform requirements and design decisions?
- How can we implement security and observability from day one?

---

{: .note }
The platform is under active development. Core infrastructure components are operational in a local Kind cluster, with MLflow tracking and basic model serving capabilities working. Documentation will be expanded as the platform implementation progresses. Follow the progress in our [Project](https://github.com/orgs/OpenCloudHub/projects/4).
