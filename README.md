# python_sample_app_docker_k8s
A simple Python app that prints a message and runs in a Kubernetes environment.

This is a simple Python application that prints a message and runs in a Docker container. The app is deployed in a Kubernetes cluster using a Deployment and Service.

- A minimal Python script (`app.py`) that prints a message and runs indefinitely.
- A Dockerfile to build the container image.
- Kubernetes deployment files to deploy the app in a Kubernetes cluster.
- Exposed via a Kubernetes NodePort service.
