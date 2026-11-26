# Automated CI/CD Pipeline for Python Calculator

![Calculator CI/CD Pipeline](https://github.com/Sabarishwar56/calculator-ci-cd/actions/workflows/ci-cd.yml/badge.svg)

## Project Overview

This project demonstrates an automated CI/CD pipeline using GitHub Actions for a simple Python calculator application.

Whenever code is pushed to the main branch, GitHub Actions automatically performs code quality checks, runs unit tests, builds a Docker image, and pushes the image to Docker Hub.

## Technologies Used

- Python 3.12
- GitHub Actions
- Ruff
- Docker
- Docker Hub
- Unit Testing

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Division-by-zero error handling
- Automated code quality checks
- Automated unit testing
- Docker image building and publishing

## Docker Hub Image

**Docker Hub Repository:** [sabarishwar/calculator-ci-cd](https://hub.docker.com/r/sabarishwar/calculator-ci-cd)

Pull the Docker image:

```bash
docker pull sabarishwar/calculator-ci-cd:latest
```

Run the Docker container:

```bash
docker run --rm sabarishwar/calculator-ci-cd:latest
```

## CI/CD Pipeline Workflow

1. Checkout the GitHub repository.
2. Set up Python 3.12.
3. Install Ruff.
4. Run code quality checks.
5. Execute Python unit tests.
6. Log in to Docker Hub securely using GitHub Secrets.
7. Build and push the Docker image to Docker Hub.

## GitHub Repository

[View Source Code](https://github.com/Sabarishwar56/calculator-ci-cd)

## Author

Sabarishwar56
