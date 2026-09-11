## Source
App is based on officially Docker-example
[dockersamples/example-voting-app](https://github.com/dockersamples/example-voting-app).
Originally describe — in [docs/ORIGINAL_README.md](docs/ORIGINAL_README.md).

This repo is a DevOps pet-project based on it: added containerization,
CI/CD, Kubernetes-manifests, Terraform for AWS and monitoring




# Voting App — DevOps Pet Project

A multi-service application for practicing DevOps workflows: from local containerization to production deployment on AWS.

## Architecture
- **vote** (Python) — voting web interface
- **redis** — vote queue
- **worker** — queue processing
- **db** (Postgres) — results storage
- **result** (Node.js) — results display

## Roadmap
- [x] Repository structure
- [ ] Docker: containerization of services
- [ ] Docker Compose: run locally
- [ ] CI: GitHub Actions
- [ ] Kubernetes (minikube/kind)
- [ ] Terraform: AWS infrastructure
- [ ] CD: Deploy to AWS
- [ ] Monitoring and logging