# Docker-app-container
## Containerizing a Java Application with Docker
### Overview
This README will walk you through the process step-by-step, enabling you to harness the power of containerization. Containerization is a method that enables you to bundle your Java application and its dependencies into a self-contained and portable environment. This approach simplifies deployment and allows for seamless scalability.

### Why Containerization?
In this project, we leverage Docker, Docker Compose, and Docker Hub to create a Docker container for your Java application. Docker serves as a powerful tool to encapsulate your application and its dependencies, guaranteeing consistent and repeatable deployments across diverse environments. This method offers several key advantages:
1. **Efficient Resource Utilization**: Containers use minimal resources, making them ideal for microservice design. This efficient resource allocation promotes scalability and cost-effectiveness.
2. **Microservices Ready**: Containerization aligns perfectly with microservice architecture, enabling you to break down your application into smaller, manageable components.
3. **Image-Based Deployment**: Deployments are based on container images, ensuring that the exact same environment is reproduced every time you deploy. This consistency minimizes the risk of unexpected issues in different environments.
4. **Reusable and Repeatable**: Docker containers are highly reusable and can be easily replicated. This repeatability simplifies development, testing, and production workflows.


### Project Goals:

### Prerequisites
Before you start containerizing your Java application, ensure that you have the following tools installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Docker Hub](https://hub.docker.com/) (for publishing your container)



## Implementation Steps

1. **setup stack services** (from project 2)
2. **find base images from dockerhub**
3. write dockerfiles to customize images
4. write `docker-compose.yml` files for running multi containers
5. **test & host** images on dockerhub

## Architecture Overview
![Project diagram](./images/docker-app-project.jpg)

## Learning Objectives

- **Dockerfile**: Configuration file for building a Docker image of your Java application.
- **docker-compose.yml**: Configuration file for defining the services, networks, and volumes for your application.

## Detailed Steps
### Step 1: Create a VM for the Docker engine using vagrant:
we will choose 
```bash
vagrant init bento/ubuntu-22.04
```
with  RAM memory="2048"

follow instructions on [Docker Engine installation on ubuntu](https://docs.docker.com/engine/install/ubuntu/)

add vagrant user do docker group:
```bash
usermod -aG docker vagrant
```

[logout and login]
## Usage Instructions

### References and Documentation: 




