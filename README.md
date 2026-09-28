# DevOps Web Application

## Project Overview

This is my first DevOps deployment project. I built a simple web application and containerized it using Docker and Nginx.

## Technologies Used

- Linux / Ubuntu
- Git
- GitHub
- Docker
- Dockerfile
- Nginx
- HTML

## Project Workflow

HTML Application
→ Git
→ GitHub
→ Dockerfile
→ Docker Image
→ Docker Container
→ Nginx
→ Web Browser

## Docker Commands

Build the Docker image:

docker build -t devops-web .

Run the container:

docker run -d -p 8080:80 --name devops-web-container devops-web

## Application

The application runs on:

http://localhost:8080

## What I Learned

- Linux command line
- Git and GitHub
- Docker images and containers
- Dockerfile
- Port mapping
- Nginx web server
- Basic application deployment
