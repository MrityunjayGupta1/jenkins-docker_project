# Python Application – Docker & Jenkins CI/CD

##  Project Overview

This project demonstrates how to containerize a Python application using **Docker** and automate the build and deployment process using **Jenkins CI/CD Pipeline**.

The application is developed using Python, with dependencies managed through `requirements.txt`. Docker is used to create a containerized environment, while Jenkins automates the CI/CD workflow.

##  Technologies Used

- **Python** – Application development
- **Docker** – Containerization
- **Jenkins** – Continuous Integration and Continuous Deployment
- **Git & GitHub** – Version control

##  Project Structure

```text
.
├── app.py
├── Dockerfile
├── Jenkinsfile
├── requirements.txt
└── README.md
```

##  Prerequisites

Make sure you have installed the following tools:

- Python 3.x
- Docker
- Jenkins
- Git

##  Pipeline Workflow

1. **Source Code Management:** Jenkins fetches the source code from GitHub.
2. **Build:** Docker image is created using the Dockerfile.
3. **Testing:** Application dependencies and tests are executed, if configured.
4. **Deployment:** Docker container is created and the application is deployed.

##  Key Features

- Python application development.
- Docker-based containerization.
- Automated CI/CD pipeline using Jenkins.
- Dependency management using `requirements.txt`.
- Consistent application execution environment.
