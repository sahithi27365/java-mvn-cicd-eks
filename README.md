# java-mvn-cicd-eks

# DESCRIPTION:
    This project demonstrates a CI/CD Workflow for maven based Java application. 
    
# TOOLS used:
  - GitHub
  - code--> scan-->SonarQube
  - maven
  - Jenkins
  - Docker image
  - ECR(Elastic Container Registry)
  - Amazon EKS.-->(creates pods) 
    
# ARCHITECTURE:

                        GitHub
                       |
                       v
                    Jenkins
                       |
              +--------+--------+
              |                 |
          Maven Build       SonarQube
              |                 |
              |          Code Quality
              |             Analysis
              |                 |
              +--------+--------+
                       |
                       v
                 Kubernetes
                       |
                       v
                  Amazon EKS
                       |
                       v
              Kubernetes Pods
                       |
                       v
                  Application
  
  
  # MY CONTRIBUTION:

- Configured Jenkins CI/CD pipeline.
- Configured Maven build and testing.
- Created and configured Amazon EKS cluster.
- Created EKS worker node groups.
- Configured Jenkins access to EKS.
- Created Kubernetes deployment configuration.
- Deployed the application to EKS.
- Troubleshot Kubernetes pod scheduling issues.
- Verified application deployment.


  # PROJECT SCREENSHOTS
   
         - Jenkins CI/CD Pipeline-(Jenkins-CICD-Pipeline-screenshot.png).
         - SonarQube Code Analysis-(SonarQube-Screenshot.png).
         - ECR -(ECR-Screenshot.png).
         - EKS -(EKS-Screenshot.png).






















              
