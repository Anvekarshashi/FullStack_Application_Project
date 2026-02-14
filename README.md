End-to-End CI/CD Pipeline for PostgreSQL Stack Application

Designed and implemented a fully automated CI/CD pipeline for a PostgreSQL-based full-stack application using Jenkins,Docker and Kubernetes deployed on Amezon Web Services.

The pipline automates source code integration, Docker image creation, database containeization, and Kubernetes deployment with secure configuration management.


# Project Overview
Built a production-ready CI/CD workflow for an application using:

* Backend: Node.js/ Express
* Frontend: React
* Database: PostgreSQL
* CI/CD: Jenkins
* Containerization: Docker
* Orchestration: Kubernetes
* Cloud: AWS EC2

# CI/CD Workflow
1. Developer pushes code to GitHub
2. Jenkins pipeline triggers automatically
3. Application build & dependency installation
4. Docker images built for frontend, backend
5. PosrgreSQL container configured
6. Images pushed to Docker Hub
7. Kubernetes Deployment & service applied
8. Application exposed using NodePort

# Key Implementations

* Created mult-stage Dockerfiles for optimized image size
* Configured Jenkins Declarative Pipeline (Build -> Test -> Docker -> Deploy)
* Secured AWS Infrastructure using IAM roles and Security Groups.

# Kubernetes Components Used

* Namespace
* Deployment
* Service(ClusterIP & NodePort)

# Security & Reliablity

* Encrypted database credentials using Kubernetes Secrets
* Implemented role-based access control (RBAC)

# Outcome
* Automated full deployment lifecycle
* Reduced manual deployment effort by 70%
