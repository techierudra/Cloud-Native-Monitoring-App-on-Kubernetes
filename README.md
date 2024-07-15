# Cloud Native Resource Monitoring Application on Kubernetes

This project demonstrates how to create a cloud-native resource monitoring application using Python, Flask, Docker, AWS ECR, and Kubernetes (EKS). Follow the steps below to get started!

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Local Deployment](#local-deployment)
- [Dockerizing the App](#dockerizing-the-app)
- [Pushing to ECR](#pushing-to-ecr)
- [Deploying to Kubernetes](#deploying-to-kubernetes)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to create a resource monitoring application using Python and Flask, containerize it with Docker, store the Docker image in AWS ECR, and deploy it to Kubernetes (EKS).

## Prerequisites

Before you begin, ensure you have the following installed:

- AWS Account with programmatic access and configured AWS CLI.
- Python 3.x and pip (Python package installer).
- Docker and Docker Compose.
- Kubernetes CLI (`kubectl`) configured to access your Kubernetes cluster.

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   cd <repository_name>
