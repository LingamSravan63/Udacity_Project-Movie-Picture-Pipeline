# 🎬 Movie Picture Pipeline — CI/CD with GitHub Actions

A DevOps project implementing complete **Continuous Integration and Continuous Deployment (CI/CD) pipelines** for a Movie Picture application using **GitHub Actions, Docker, Amazon ECR, Amazon EKS, and Kubernetes**.

This project was developed as part of the **Udacity DevOps / ATCI learning module**.

---

## 🚀 Project Overview

The Movie Picture Pipeline demonstrates an automated DevOps workflow for both the frontend and backend applications.

The project includes:

- Continuous Integration pipelines for frontend and backend
- Continuous Deployment pipelines for frontend and backend
- Automated linting and testing
- Docker image creation
- Amazon ECR container image storage
- Amazon EKS Kubernetes deployment
- Kubernetes LoadBalancer services
- GitHub Secrets for secure configuration
- Automated workflows using GitHub Actions
- Manual workflow execution using `workflow_dispatch`

The final application is deployed on an **Amazon EKS cluster** and can be accessed through the frontend and backend LoadBalancer URLs.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| GitHub Actions | CI/CD automation |
| Docker | Application containerization |
| Amazon ECR | Docker image registry |
| Amazon EKS | Kubernetes cluster |
| Kubernetes | Application deployment and management |
| kubectl | Kubernetes command-line tool |
| Node.js / npm | Frontend development, linting and testing |
| Python | Backend application |
| GitHub Secrets | Secure credentials and configuration |

---

## 🔄 CI/CD Architecture

The overall pipeline follows this workflow:

   <img width="365" height="384" alt="image" src="https://github.com/user-attachments/assets/1fc593e4-c4aa-409b-aa81-ce66b2dd9ed8" />

---

## 🌐 Deployed Application

🎬 Frontend Application

The frontend application is deployed on Amazon EKS and exposed through an AWS LoadBalancer.
Live Frontend URL:

http://aeee494e546014c5583c11694c22aed8-104574958.us-east-1.elb.amazonaws.com

<img width="954" height="511" alt="Screenshot 2026-08-11 185107" src="https://github.com/user-attachments/assets/77e38238-01a2-4fea-b161-db22a593dfcb" />

The frontend successfully displays the movie list and movie details retrieved from the backend API.

🔗 Backend API

The backend API is deployed on Amazon EKS and exposed through an AWS LoadBalancer.

Live Backend API

http://a137eb62320fb46f5af3dc07cd07f422-201081563.us-east-1.elb.amazonaws.com/movies

<img width="960" height="512" alt="Screenshot 2026-08-11 185923" src="https://github.com/user-attachments/assets/14741cd2-b0be-496d-8fe3-69cdb87dd5a2" />


## ⚙️ GitHub Actions Workflows

The project contains four GitHub Actions workflows:

| Workflow                        | File               | Purpose                                            |
| ------------------------------- | ------------------ | -------------------------------------------------- |
| Frontend Continuous Integration | `frontend-ci.yaml` | Frontend linting, testing and Docker build         |
| Backend Continuous Integration  | `backend-ci.yaml`  | Backend linting, testing and Docker build          |
| Frontend Continuous Deployment  | `frontend-cd.yaml` | Frontend Docker build, ECR push and EKS deployment |
| Backend Continuous Deployment   | `backend-cd.yaml`  | Backend Docker build, ECR push and EKS deployment  |


## ✅ Project Verification

The following components have been successfully verified:

✅ Frontend CI workflow

✅ Backend CI workflow

✅ Frontend CD workflow

✅ Backend CD workflow

✅ Frontend Docker image

✅ Backend Docker image

✅ Amazon ECR image push

✅ Amazon EKS deployment

✅ Frontend LoadBalancer

✅ Backend LoadBalancer

✅ Frontend movie list

✅ Backend /movies API

✅ GitHub Secrets for sensitive configuration

## 👨‍💻 Author

Lingam Sravan

B.Tech — Computer Science & Engineering (AI & ML)

GitHub:
https://github.com/LingamSravan63

Project Repository:
https://github.com/LingamSravan63/Udacity_Project-Movie-Picture-Pipeline



## 🎓 Udacity Project

This project was completed as part of the Udacity DevOps / ATCI learning module.

The project demonstrates practical experience with:

Continuous Integration

Continuous Deployment

GitHub Actions

Docker

Amazon ECR

Amazon EKS

Kubernetes

Automated testing

Automated deployments
Secure secret management
