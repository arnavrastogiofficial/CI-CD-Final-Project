# CI/CD Final Project

## Project Name
CI/CD Final Project

## Project Overview
This project demonstrates the implementation of Continuous Integration (CI) and Continuous Delivery/Deployment (CD) using GitHub Actions and OpenShift Pipelines.

## Objectives
- Automate code linting using Flake8.
- Run unit tests using Nose.
- Configure a CI workflow using GitHub Actions.
- Create Tekton tasks for cleanup and unit testing.
- Build and deploy the application using OpenShift Pipelines.
- Verify that the deployed application runs successfully on port 8000.

## Technologies Used
- Python
- Flask
- Git and GitHub
- GitHub Actions
- Flake8
- Nose
- Tekton
- OpenShift Pipelines
- Buildah

## Project Components
- `.github/workflows/workflow.yml` — GitHub Actions CI workflow.
- `.tekton/tasks.yml` — Tekton cleanup and testing tasks.
- `requirements.txt` — Python dependencies.
- `service/` — Application source code.
- `tests/` — Unit tests.

## Application Status
The application is expected to run on port 8000 after successful deployment.

## Author
Arnav Rastogi
