# Docker-Based Web Application Deployment on Linux

## Project Overview
This beginner DevOps project demonstrates how to build and deploy a simple static website inside a Docker container using Nginx on Linux.

## Technologies Used
- Linux (Ubuntu on WSL)
- Docker
- Dockerfile
- Nginx
- HTML

## Project Features
- Created a simple HTML website.
- Built a custom Docker image using a Dockerfile.
- Deployed the website inside an Nginx container.
- Exposed the website on port 8080.
- Practiced starting, stopping, and monitoring a container.
- Used Docker logs to check web server activity.
- Added a .dockerignore file to exclude unnecessary files from the build context.

## How to Run

Build the Docker image:

```bash
sudo docker build -t essa-web-app .
```

Start the container:

```bash
sudo docker run -d --name essa-web-container -p 8080:80 essa-web-app
```

Open the website in a browser:

http://localhost:8080

View running containers:

```bash
sudo docker ps
```

View container logs:

```bash
sudo docker logs essa-web-container
```

Stop the container:

```bash
sudo docker stop essa-web-container
```

Start the existing container again:

```bash
sudo docker start essa-web-container
```

## Learning Outcome
Learned the basics of Docker image creation, container deployment, port mapping, container management, and web server monitoring on Linux.

