# Docker-Based Web Application Deployment on Linux

## Project Overview

This beginner DevOps project demonstrates how to build and deploy a static website using Docker, Docker Compose, and Nginx on Linux.

## Technologies Used

- Linux (Ubuntu on WSL2)
- Docker
- Docker Compose
- Dockerfile
- Nginx
- HTML
- Git and GitHub

## Project Features

- Created a static website using HTML.
- Built a custom Docker image using a Dockerfile.
- Deployed the website using Nginx.
- Configured Docker Compose using compose.yaml.
- Mapped host port 8081 to container port 80.
- Practiced starting, stopping, and monitoring containers.
- Used Docker logs to check web server activity.
- Managed project files using Git and GitHub.

## How to Run

Clone the repository:

    git clone https://github.com/Essawx/docker-web-project.git

Open the project directory:

    cd docker-web-project

Build and start the application:

    docker compose up -d --build

Check container status:

    docker compose ps

Open the website:

    http://localhost:8081

View logs:

    docker compose logs web

Stop the application:

    docker compose stop

Start the application again:

    docker compose start

Stop and remove the Compose container and network:

    docker compose down

## Learning Outcomes

- Docker image creation and container deployment.
- Nginx web server configuration.
- Docker Compose service management.
- Port mapping and container monitoring.
- Linux commands and Git version control.

## Author

Essa Khan

## GitHub Repository

https://github.com/Essawx/docker-web-project
