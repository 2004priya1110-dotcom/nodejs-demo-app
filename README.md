# Node.js CI/CD Pipeline using GitHub Actions

## Objective

This project demonstrates an automated CI/CD pipeline for a Node.js web application using GitHub Actions and Docker.

## Tools Used

- GitHub
- GitHub Actions
- Node.js
- Express.js
- Docker
- DockerHub

## CI/CD Workflow

The pipeline is triggered whenever code is pushed to the main branch.

The pipeline performs the following steps:

1. Checkout source code
2. Setup Node.js
3. Install dependencies
4. Run tests
5. Build Docker image
6. Login to DockerHub
7. Push Docker image to DockerHub

## Project Structure

```text
nodejs-demo-app/
├── .github/
│   └── workflows/
│       └── main.yml
├── .dockerignore
├── .gitignore
├── Dockerfile
├── package.json
├── package-lock.json
├── README.md
└── server.js
