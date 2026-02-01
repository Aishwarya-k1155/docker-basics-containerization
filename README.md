# docker-basics-containerization
# Docker Basics – Containerizing an Application

## Objective
To understand Docker containerization by packaging and running a simple application.

## Tools Used
- Docker

## Application
A simple Flask web application that displays a message in the browser.

## Steps Performed
1. Created a Python Flask application
2. Defined dependencies using requirements.txt
3. Wrote a Dockerfile
4. Built Docker image
5. Ran container with port mapping
6. Verified output in browser
7. Inspected container details
8. Stopped and removed the container

## Commands Used
docker build -t docker-basics-app .
docker run -d -p 5000:5000 --name docker-task docker-basics-app
docker ps
docker logs docker-task
docker inspect docker-task

docker stop docker-task
docker rm docker-task

## Output
Application accessible at:
http://localhost:5000
