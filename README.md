# Maven Docker Jenkins CI-CD Pipeline

A complete end-to-end DevOps implementation demonstrating automated Java web application deployment using Maven build automation, WAR packaging, Docker containerization, Apache Tomcat deployment, GitHub integration, and Jenkins CI/CD pipelines.

## Features

- Maven-based WAR generation
- JSP and Tomcat web application deployment
- Dockerized Java web application hosting
- Jenkins Declarative Pipeline automation
- Automated GitHub repository cloning
- Docker image build and container deployment
- CI/CD email notifications using `emailext`
- End-to-end continuous integration workflow

## Tech Stack

- Java
- JSP
- Maven
- Apache Tomcat
- Docker
- Jenkins
- GitHub

## Pipeline Workflow

GitHub Repository
        |
        v
Jenkins Pipeline
        |
        v
Maven Build
        |
        v
WAR Packaging
        |
        v
Docker Image Build
        |
        v
Tomcat Container Deployment
        |
        v
Browser Access
