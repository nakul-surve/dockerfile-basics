# Dockerfile Basics

This repository explains a simple Dockerfile used to run Nginx.

## Dockerfile Explanation

FROM ubuntu:20.04  
Uses Ubuntu as the base image.

RUN apt-get update && apt-get install -y nginx  
Installs Nginx inside the image.

CMD ["nginx", "-g", "daemon off;"]  
Starts Nginx in the foreground when the container runs.

## Learning Outcome
- Understand image building steps
- Learn how services run inside containers
- Focus on clarity over complexity
