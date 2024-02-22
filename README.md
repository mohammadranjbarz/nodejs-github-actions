# My Node.js App

This is a Node.js application, automated with GitHub Actions for CI/CD and containerized using Docker.

## Getting Started

These instructions will cover usage information for the docker container created by the CI/CD pipeline of this project.

### Prerequisites

Ensure you have Docker installed on your system. For installation instructions, see: [Get Docker](https://docs.docker.com/get-docker/).

### Using the Docker Container

The Docker image for this project is built and pushed to the GitHub Container Registry on every update to the main branch. To use the image, follow these steps:

1. **Pull the Docker Image**

   ```bash
   docker pull ghcr.io/mohammadranjbarz/nodejs-github-actions:main
   ‍‍‍```

2. **Run the Docker Container**

   ```bash
   docker run -d -p 3000:3000 ghcr.io/mohammadranjbarz/nodejs-github-actions:main
   ```

3. **Browse application**

   Open your browser and navigate to `http://localhost:3000` to see the application running.

