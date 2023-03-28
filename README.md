# DevOps Project - CI/CD for Containers of Vprofile Project on Kubernetes Cluster

This is a DevOps Project for [CI/CD](https://www.redhat.com/en/topics/devops/what-is-ci-cd) (_Continuous Integration and Continuous Delivery_) for _Containers_ of Vprofile Project on _Kubernetes Cluster_ using Jenkins, SonarQube, Docker, Helm and AWS Cloud.

[Link](https://github.com/durrezahmed/vprofile-project-devops) for vprofile app repository.

## Scenario - Current Situation:

- Microservices Architecture of an Application

- Containerized Application

- Continuous Code Changes

- Continuous Build and Test

- Regular Build of Container Images

- Regular Deployment Requests to Ops Team

## Problem - Issues with Current Situation:

- Operations Team incharge of Managing Containers, Gets Continuous Deployment Requests

- Manual Deployment creates Dependency

- Time Consuming

## Solution - Fix:

- Automate Build and Release Process

- Build Docker Images and Deploy Continuously as fast as the Code Commits

- Continuous Deployment

## Tools used in the Project:

- [**Jenkins**](https://www.jenkins.io/) - Continuous Integration and Continuous Delivery Server

- [**Git and GitHub**](https://github.com/) - Version Control System

- [**Maven**](https://maven.apache.org/) - Build Tool

- [**Checkstyle**](https://checkstyle.org/) - Code Analysis Tool

- [**SonarQube**](https://www.sonarsource.com/products/sonarqube/) - Code Analysis Server

- [**Docker**](https://www.docker.com/) - Build Docker Images

- [**Docker Hub**](https://hub.docker.com/) - Container Registry

- [**Kubernetes**](https://kubernetes.io/) - Container Orchestration Tool

- [**Helm**](https://helm.sh/) - Packaging and Deploying on Kubernetes

- [**AWS Cloud Platform**](https://aws.amazon.com/) - Cloud Computing Resources

## Steps:

1. Continuous Integration Setup

   - Jenkins, SonarQube and Nexus ([_vprofile-project-ci-jenkins_](https://github.com/durrezahmed/vprofile-project-ci-jenkins))

2. Store Docker Hub credentials in Jenkins

3. Setup Docker Engine in Jenkins

4. Install Plugins in Jenkins

   - Docker Pipeline

   - Docker

   - Pipeline Utility

5. Create Kubernetes Cluster with Kops

6. Install Helm in Kops VM

7. Create Helm Charts

8. Test Charts in K8s Cluster in `test` Namespace

9. Add Kops VM as Jenkins Slave

10. Write Pipeline Code (Declarative)

11. Update Git Repository with

    - Helm Charts

    - Dockerfile

    - Jenkinsfile (Pipeline Code)

12. Create Jenkins Job for Pipeline

13. Run and Test the Job
