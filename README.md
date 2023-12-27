### A Pipeline for Continuous Delivery to DockerHub Using GitHub Actions
This repository is used to set up a pipeline that includes a basic Node.js app. When a push is made to this repository, the Dockerfile is built and the image is pushed to the Docker registry.

### Setting Up the Pipeline
1. Clone the repository.
2. Set up secret variables for this repository in GitHub:  
2.1. DOCKER_USERNAME  
2.2. DOCKER_PASSWORD  
2.3. DOCKER_IMAGE  
3. Make a change to a file and push it to GitHub. This will trigger a build and publish it to DockerHub.

