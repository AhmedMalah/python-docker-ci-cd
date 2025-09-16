# python-docker-ci-cd
# 🐳 Python + Docker + GitHub Actions CI/CD Project

This is a beginner-friendly DevOps project that demonstrates how to use **Python**, **Docker**, and **GitHub Actions GUI** to build a simple CI/CD pipeline.

## 📦 Project Overview

- A simple Python script (`app.py`) that prints a message.
- A `Dockerfile` to containerize the Python app.
- A GitHub Actions workflow (`docker.yml`) that:
  - Builds the Docker image on every push to `main`.
  - Optionally logs in to Docker Hub and pushes the image.

## 📁 Project Structure

├── app.py  
├── Dockerfile  
└── .github  
  └── workflows  
    └── docker.yml

## ⚙️ Setup Instructions

1. Clone the repo or create it on GitHub.
2. Add your Python script (`app.py`).
3. Add a `Dockerfile` to containerize the app.
4. Use GitHub Actions GUI to create a workflow file (`docker.yml`).
5. Add Docker Hub credentials as GitHub Secrets:
   - `DOCKER_USERNAME`
   - `DOCKER_PASSWORD`

## 🚀 How CI/CD Works

- **CI (Continuous Integration):** Every push to `main` triggers a workflow that builds the Docker image.
- **CD (Continuous Deployment):** If Docker credentials are set, the image is pushed to Docker Hub automatically.

## 🙌 Credits

Created by Ahmed Elmalah as part of his DevOps learning journey.

