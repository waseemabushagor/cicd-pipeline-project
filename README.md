# CI/CD Pipeline Project

CI/CD pipeline to deploy a SAMPLE NodeJs app "train schedule"

## To Run The App

 run the build like this:

    ./gradlew build

 run the app with:

    ./gradlew npm_start

Once running, app is accessible on http://localhost:8080


## CI/CD Pipeline Project -
Built a fully automated CI/CD Pipeline to deploy a Nodejs app. Git was used as source control management for all code. Changes to code triggered a pipeline script created in Jenkins to automate:

•	Build Automation of app using Gradle

•	Building of a Docker Image of the app and pushing the new image to GitHub.

•	Deployment of the app Docker image using Kubernetes

Sample Nodejs App is used. Each section can be its own mini project but when combined it creates a CI/CD pipeline with the pipeline as code. Sections can be divided into
1.	Source Control Management - Git Basics
2.	Build Automation (Gradle)
3.	Continuous Integration (Jenkins)
4.	Continuous Delivery (Jenkins Pipeline)
5.	Containerization (Docker)
6.	Container Orchestration (Kubernetes)
7.	Continuous Deployment (All + Github Webhooks)

## Rough Notes
See https://github.com/waseemabushagor/cicd-pipeline-project/blob/master/cicdproject.pdf for Rough Notes



















