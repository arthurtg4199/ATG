# DevOps Demo Project

This project demonstrates Docker, Kubernetes, and CI/CD with GitHub Actions.

## Features
- Dockerized application
- Kubernetes deployment manifests
- GitHub Actions pipeline for build & deploy

## How to Run
1. Clone repo
2. Build Docker image: `docker build -t myapp:latest ./docker`
3. Run locally: `docker run -p 8080:8080 myapp:latest`
4. Deploy to Kubernetes: `kubectl apply -f k8s/`
