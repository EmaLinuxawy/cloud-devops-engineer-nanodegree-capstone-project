[![CircleCI](https://circleci.com/gh/EmaLinuxawy/cloud-devops-engineer-nanodegree-capstone-project/tree/master.svg?style=svg)](https://circleci.com/gh/EmaLinuxawy/cloud-devops-engineer-nanodegree-capstone-project/tree/master)
# cloud-devops-engineer-nanodegree-capstone-project
[This is Repo URL for Reviewier](https://github.com/EmaLinuxawy/cloud-devops-engineer-nanodegree-capstone-project)

My Capstone Project for Udacity's Cloud DevOps Engineer Nanodegree

## The application: ML Microservices

I used project-ml-microservice-kubernetes from the last Udacity project to deploy it in this infrastructure

## Automation of the project 
I used CircleCI to deploy this infrastructure with the ML application

1. Install application
2. Lint the code
3. Build a Docker image
4. Push the container to the Docker Registry
6. Create the Kubernetes configuration file
7. Deploy the application to AWS EKS cluster

In the end, the app is deployed to the cluster and accessible to users.

## Infrastructure
i used bash commands inside create-eks.sh file to create EKS Cluster using [eksctl](https://eksctl.io/), Then i run it locally because EKS cluster takes about 15mins to be ready.