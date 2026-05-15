# Flask DevOps App 🚀

Containerized Flask API with CI/CD Pipeline

## Tech Stack
- Python + Flask
- Docker
- GitHub Actions (CI/CD)
- DockerHub

## Architecture
git push → GitHub Actions → Docker build → DockerHub

## Run locally
docker pull cloud6devops/flask-devops-app:latest
docker run -p 5000:5000 cloud6devops/flask-devops-app:latest

## Endpoints
- GET / → returns app info
- GET /health → returns health status
