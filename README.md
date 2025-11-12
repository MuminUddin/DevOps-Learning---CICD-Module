# DevOps-Learning—CICD-Module

## What's here? 📚
1. **Assignment 1:** Flask container build and push (Docker + GitHub Actions)
2. **Assignment 2:** CI checks for quality (linting + basic tests)

## Assignment 1 Overview
A minimal Flask app and a GitHub Actions workflow that builds a Docker image and pushes it to Docker Hub on each push to `main`.

**What it does**
- Serves a simple Flask app with a health endpoint
- Builds a container image from `app/Dockerfile`
- Pushes the image to Docker Hub as `muminuddin/my-flask-app:latest`

## Repo structure
```
.
├── app/
│ ├── app.py
│ ├── requirements.txt
│ └── dockerfile
└── .github/workflows
  └── docker-build-push.yml
```
