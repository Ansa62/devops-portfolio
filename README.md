# DevOps Portfolio

Hands-on projects for learning Docker and Kubernetes.

## Phase 1: Containerized website
- Custom Nginx image built from a Dockerfile
- Build: `docker build -t my-website:1.0 website/`
- Run: `docker run -d -p 8080:80 my-website:1.0`
- Open: http://localhost:8080

## Phase 2: WordPress + MariaDB
- Multi-container stack using Docker Compose
- Run: `cd wordpress && docker compose up -d`
- Open: http://localhost:8081
