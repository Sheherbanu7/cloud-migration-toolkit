# Cloud Migration Toolkit

This repository showcases cloud migration lifecycle using enterprise DevOps practices. It simulates the complete SDLC (Software Development Life Cycle) of an application being migrated to the cloud using IaC, CI/CD, containerization, and monitoring.

> This project is for demonstration purposes.

---

## Objective
- Build a reference architecture for cloud migration
- Set up automated CI/CD pipelines
- Use multi-cloud deployment (AWS, Azure, GCP)
- Implement observability and alerts

---

## Repo Structure

| Folder        | Purpose                                  |
|---------------|-------------------------------------------|
| `src/`        | Application code (sample microservice)   |
| `docs/`       | Design documents and diagrams            |
| `iac/`        | Infrastructure as Code (Terraform, Ansible) |
| `k8s/`        | Kubernetes manifests                      |
| `monitoring/` | Dashboards, Prometheus, Grafana configs   |
| `tests/`      | Unit and integration tests               |
| `.github/`    | GitHub Actions CI/CD workflows           |

---

## Tech Stack

- Cloud: AWS, Azure, GCP
- IaC: Terraform, Ansible
- CI/CD: GitHub Actions
- Containers: Docker, Kubernetes
- Monitoring: Prometheus, Grafana, ELK Stack

---

## Architecture

![Architecture Diagram](docs/architecture-diagram.png)
