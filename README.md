# Simple Static HTML Page with CI/CD Pipeline (Live Coding lesson with SoftServe)

This repository contains a simple static HTML page project designed as a training exercise to master CI/CD skills using GitHub Actions and Docker. The project automates the build, validation, and deployment processes, providing hands-on experience with modern DevOps practices.

## Project Overview

- **HTML Page:** The core of the project is a basic static HTML page.
- **HTML Validation:** The project includes an HTML validator script that ensures the code adheres to best practices and standards. This script is executed as part of the CI pipeline.
- **CI/CD Pipeline:** The project is integrated with GitHub Actions, which automates the build and deployment processes. Every push and pull request triggers the pipeline, ensuring that only validated code is deployed.
- **Docker Integration:** The project is containerized using Docker, allowing for consistent and portable environments across development, testing, and production.

## Technologies Used

- **GitHub Actions:** For setting up a CI/CD pipeline that automates testing and deployment.
- **Node.js & npm:** Used for managing dependencies and running the HTML validator script.
- **Docker:** The project is containerized, making it easy to deploy in any environment.
- **HTML:** The static web page, which serves as the primary content of the project.

## Key Features

- **Automated CI/CD Pipeline:** Ensures that the HTML code is validated and deployed automatically.
- **Dockerized Application:** The project can be easily run in any Docker-compatible environment.
- **HTML Validation:** Ensures that the HTML code is standards-compliant before it gets deployed.

## Learning Outcomes

By working on this project, I have gained practical experience in the following areas:

- **Continuous Integration and Deployment (CI/CD):** Setting up and managing a CI/CD pipeline with GitHub Actions.
- **Docker:** Containerizing a simple web application and managing it across different environments.
- **Automation:** Automating the validation and deployment of static web pages.
- **DevOps Practices:** Implementing end-to-end automation for a web application using modern tools.

## CI/CD Workflow

The CI/CD pipeline is defined in the `.github/workflows/main.yml'