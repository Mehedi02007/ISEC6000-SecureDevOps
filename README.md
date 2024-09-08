# ISEC6000 Secure DevOps Project

This repository contains the project files for deploying the **Saleor e-commerce platform** using **Docker Compose** and **Kubernetes**. The project demonstrates the implementation of security best practices and the design of a microservices-based architecture.

## Project Overview

The **Saleor platform** is an open-source, microservices-based e-commerce platform. The project includes several core components:
- **Saleor API**: The backend service that handles e-commerce operations such as product management, orders, and users.
- **Saleor Dashboard**: An admin interface that allows store owners to manage products, orders, and users.
- **PostgreSQL**: A relational database to store data related to e-commerce functionalities.
- **Redis**: An in-memory cache used for speeding up application performance.

In this project, we focus on securely deploying and configuring the platform using **Docker Compose** on Kubernetes, while applying key security measures and scanning for vulnerabilities.

## Key Objectives
- Deploy the Saleor platform using Docker Compose and Kubernetes.
- Implement security best practices, such as running containers as non-root users and limiting resource usage.
- Perform vulnerability scanning using **Trivy** to identify and fix security issues in the Docker images.
- Create an architecture diagram that shows how the different components of the platform interact.

## Technologies Used
- **Docker Compose**: For orchestrating the deployment of Saleor services.
- **Minikube**: A tool for running Kubernetes locally.
- **Kubernetes**: For container orchestration and management of microservices.
- **Trivy**: A vulnerability scanning tool for Docker images.
- **Draw.io**: A diagramming tool used to visualize the architecture.

### Prerequisites
Make sure you have the following tools installed on your system before proceeding:
- **Docker** and **Docker Compose**
- **Minikube**
- **kubectl** (Kubernetes command-line tool)
