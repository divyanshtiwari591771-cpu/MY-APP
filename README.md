# Flask App with GitHub Actions CI

This project demonstrates a simple Python Flask application integrated with
a Continuous Integration (CI) pipeline using GitHub Actions.

The main goal of this project is to understand how CI pipelines automate
code validation whenever changes are pushed to a repository.

## Tech Stack
- Python
- Flask
- Git & GitHub
- GitHub Actions (CI)

## Features
- Automatically triggers CI pipeline on every push to the main branch
- Sets up a Linux-based GitHub runner
- Installs dependencies from requirements.txt
- Validates the Flask application

## CI/CD Workflow Explanation
- Code is pushed to GitHub
- GitHub Actions workflow is triggered
- Python environment is set up
- Dependencies are installed
- Application is validated

Currently, Continuous Integration (CI) is implemented.
Deployment (CD) will be added in the next phase using Docker and cloud services.


## Project Structure
.
├── app.py
├── requirements.txt
└── .github
└── workflows
└── ci-cd.yml


## What I Learned
- Basics of CI/CD concepts
- Writing GitHub Actions workflows
- Automating application checks
- Using Git and GitHub effectively
