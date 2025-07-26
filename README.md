# K8S_mini_proj
This project demonstrates how to automate the build and deployment of a simple Flask web application using:

- **GitHub Actions** to build and push a Docker image to Docker Hub
- **Docker** for containerization
- **OpenShift (Kubernetes)** to deploy the app using `Deployment` and `Service` YAML configurations

# Features

- CI/CD workflow using GitHub Actions
- Docker image built and pushed automatically to Docker Hub on `main` branch push
- Kubernetes YAMLs for creating deployments and exposing the app via a ClusterIP service
- Live application running inside an OpenShift cluster
