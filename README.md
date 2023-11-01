
🚀 **Project: Jenkins-DockerCICD 🛠️**
This project creates a CI/CD pipeline for a Flask application.

**Objective:**
Automate the deployment of a sample Flask application using Jenkins for continuous integration and continuous delivery (CI/CD) within a Dockerized environment, and host the Docker images on Docker Hub.

**Prerequisites:**
- An Ubuntu server with Jenkins and Docker installed.
- An AWS EC2 instance for hosting the Flask application.

**Step 1: Deploy the Sample Flask Application on an EC2 Server 🏃‍♂️**
1.1. Provision an EC2 instance on AWS.
1.2. Install the required dependencies, including Python and Flask, on the EC2 server.
1.3. Deploy the sample Flask application to the EC2 server.
1.4. Verify that the application is working correctly by accessing the EC2 server's public IP or domain.

**Step 2: Containerize the Application Using Docker 🐳**
2.1. Create a Dockerfile to define the application's container environment.
2.2. Build a Docker image from the Dockerfile.
2.3. Run a Docker container from the created image.
2.4. Test the containerized application to ensure it functions as expected.

**Step 3: Implement CI/CD Automation with Jenkins 🤖**
3.1. Set up a Jenkins pipeline job to automate the CI/CD process.
3.2. Configure the Jenkins job to monitor the GitHub repository where the Flask application source code resides.
3.3. Define the pipeline stages, which may include:
   - Building a Docker image
   - Running tests
   - Pushing the Docker image to Docker Hub
   - Deploying the application to the EC2 server
3.4. Integrate GitHub webhooks with Jenkins to trigger the pipeline on code changes.
3.5. Test the Jenkins pipeline to ensure it deploys changes to the EC2 server automatically.

**Step 4: Docker Hub Integration 🐋**
4.1. Create a Docker Hub account if you don't have one.
4.2. Set up Docker Hub credentials within Jenkins for pushing Docker images.
4.3. Configure the Jenkins pipeline to push the Docker image to Docker Hub as part of the CI/CD process.

🌐 **URL of Flask application:** [GitHub Repository](https://github.com/yeshwanthlm/docker-flask-demo.git)

With these steps, you'll have an automated CI/CD pipeline for your Flask application, allowing for efficient development and deployment with Jenkins, Docker, and Docker Hub integration. 🎉
