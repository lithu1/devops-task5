# Task 5 – Kubernetes Deployment with Minikube

## 📌 Objective
Deploy and manage a simple Node.js application on Kubernetes using Minikube inside WSL Ubuntu.

## 🚀 Steps Performed

1. Installed Minikube and started the cluster using Docker driver
2. Created a Kubernetes Deployment with `node:14` image
3. Exposed the app via NodePort Service
4. Verified pods and services
5. Scaled the deployment from 2 to 4 replicas
6. Described deployment and logs for debugging
7. Accessed the app using `minikube service nodejs-service --url`

## 🔧 Files

- `deployment.yaml` – Deployment definition
- `service.yaml` – NodePort service definition
- `README.md` – Description of the task and setup

## ✅ Result

App deployed, scaled and accessible through Minikube's exposed service.
