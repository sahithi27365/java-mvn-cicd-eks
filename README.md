# java-mvn-cicd-eks

# End-to-End Java CI/CD Pipeline on AWS EKS

## 📌 Project Description

This project demonstrates an end-to-end CI/CD pipeline for a Java Maven application, from source code management to deployment on Amazon EKS.

The pipeline automates application build, code quality analysis, Docker image creation, image storage in Amazon ECR, and deployment to Kubernetes running on Amazon EKS.

---

## 🛠️ Tools & Technologies Used

* **Git & GitHub** – Source code management
* **Jenkins** – CI/CD automation
* **Maven** – Application build
* **SonarQube** – Code quality analysis
* **Docker** – Application containerization
* **Amazon ECR** – Docker image repository
* **Amazon EKS** – Managed Kubernetes service
* **Kubernetes** – Application deployment and management
* **AWS EC2** – Infrastructure for the environment
* **Linux** – Server environment
* **YAML** – Kubernetes configuration

---

## 🏗️ Architecture

```text
Developer
    │
    ▼
  GitHub
    │
    ▼
 Jenkins
    │
    ├── Maven Build
    │
    ├── SonarQube Analysis
    │
    ├── Docker Build
    │
    ▼
 Amazon ECR
    │
    ▼
 Amazon EKS
    │
    ▼
 Kubernetes Pods
    │
    ▼
 Java Application
```

### CI/CD Flow

**GitHub → Jenkins → Maven → SonarQube → Docker → Amazon ECR → Amazon EKS → Kubernetes**

---

## 👩‍💻 My Contribution

* Set up the Jenkins CI/CD pipeline for the Java Maven application.
* Configured the Maven build process.
* Integrated SonarQube for code quality analysis.
* Created the Docker image for the application.
* Pushed the Docker image to Amazon ECR.
* Configured Kubernetes deployment manifests.
* Deployed the application to Amazon EKS.
* Used `kubectl` to verify the Kubernetes deployment and running resources.
* Troubleshot deployment and configuration issues during implementation.

---

## 📸 Project Screenshots

### Jenkins CI/CD Pipeline

![Jenkins CI/CD Pipeline](screenshots/Screenshot.jenkins.CICD.PIPELINE.png)

### SonarQube Analysis

![SonarQube Analysis](screenshots/Screenshot.sonarqube.png)

### Amazon ECR

![Amazon ECR](screenshots/Screenshot.ECR.png)

### Amazon EKS Nodes

![Amazon EKS Nodes](screenshots/Screenshot.EKS.Nodes.png)

---

## 🎯 Project Outcome

Successfully implemented an automated CI/CD workflow that builds, analyzes, containerizes, and deploys a Java Maven application to Kubernetes on Amazon EKS.

This project provided hands-on experience with cloud infrastructure, CI/CD automation, containerization, Kubernetes, and AWS services.
























              
