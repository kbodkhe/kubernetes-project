# kubernetes-project
# Kubernetes Microservices Deployment Project

## Project Overview
This project demonstrates deploying a microservices-based application on Kubernetes using production best practices.

## Technologies Used
- Kubernetes
- Docker
- kubectl
- ConfigMaps
- Horizontal Pod Autoscaler (HPA)

## Key Features
- Kubernetes Deployments for high availability
- Services for stable networking
- ConfigMaps for externalized configuration
- HPA for automatic scaling
- Resource requests and limits

## How to Deploy
```bash
kubectl apply -f namespaces/
kubectl apply -f configmaps/
kubectl apply -f deployments/
kubectl apply -f services/
kubectl apply -f hpa/
