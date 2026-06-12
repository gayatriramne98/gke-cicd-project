# GKE CI/CD Project

## Overview

This project demonstrates deployment of a containerized web application on Google Kubernetes Engine (GKE).

## Technologies Used

- Docker
- Google Kubernetes Engine (GKE)
- Artifact Registry
- Kubernetes
- Jenkins
- GitHub

## Project Architecture

GitHub
↓
Jenkins
↓
Docker Build
↓
Artifact Registry
↓
GKE Cluster
↓
LoadBalancer Service

## Files

- index.html
- Dockerfile
- deployment.yaml
- service.yaml
- Jenkinsfile

## Deployment Commands

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
