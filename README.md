# Ultimate DevOps Project on AWS EKS

This repository contains a multi-microservice application deployed on AWS EKS. Each microservice may be written in different programming languages, demonstrating a polyglot architecture with independent services.

# Overview

# Cluster: AWS EKS (Elastic Kubernetes Service)

# Architecture: Microservices (polyglot – multiple languages)

# Deployment Tool: ArgoCD (GitOps)

# Containerization: Docker for all services

# Routing & Networking: Kubernetes Services (ClusterIP / LoadBalancer / optional Ingress)

# CI/CD: Automatic deployments through ArgoCD monitoring the GitHub repository

# Features

Polyglot Microservices: Services written in Go, Python, Node.js, Java, etc.

Independent Services: Each microservice can be deployed, scaled, and updated independently.

Containerized: All microservices run in Docker containers.

GitOps Deployment: ArgoCD continuously monitors the repository and applies changes to the cluster automatically.

EKS Scaling: Services leverage Kubernetes features for high availability and horizontal scaling.

Environment Separation: Different namespaces or clusters can be used for dev, staging, and production.
