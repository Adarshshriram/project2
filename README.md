# project2

# Jenkins CI/CD Pipeline Project

This project demonstrates how to **automate the build and deployment** process of a web application using **Jenkins and Docker** with a pipeline defined in a `Jenkinsfile`.

---

##  Objective

To set up a basic Jenkins pipeline that:
- Builds the application
- Runs tests
- Deploys the application using Docker

---

## Tools Used

- Jenkins
- Docker
- GitHub
- Linux 

---

## Pipeline Stages

The pipeline includes the following stages:

1. **Checkout** – Pulls code from GitHub
2. **Build** – Builds the Docker image from `Dockerfile`
3. **Test** –  Runs test commands if defined
4. **Deploy** – Runs the Docker container on a specific port

## How to Run

1. Set up Jenkins on your local/server or use a cloud instance.
2. Create a new pipeline project.
3. Point the project to this GitHub repo.
4. Jenkins will automatically run the pipeline on every commit.

## Outcome

By completing this project, 

1. Understand the basics of CI/CD using Jenkins.
2. Learn how to automate Docker-based deployments.
