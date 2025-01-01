# **CI-CD-Project**

## **Overview**
This project demonstrates the deployment of a **Golang application** to **Kubernetes (K8s)** in **EKS (Elastic Kubernetes Service)** clusters using a CI/CD pipeline. The repository contains details about the Go application, Docker files, and deployment configurations.

---

## **Key Components**
| **Component**          | **Details**                                  |
|-------------------------|----------------------------------------------|
| **Programming Language**| Golang                                       |
| **Containerization**    | Docker                                       |
| **Orchestration**       | Kubernetes (K8s)                             |
| **Deployment Platform** | Amazon EKS                                   |
| **Pipeline**            | GitHub Actions                               |

---

## **How to Explore This Repository**
📂 **Repository Structure**:
1. **Code**:
   - The Go application source code is located in the main directory of the repository.

2. **CI/CD Pipeline**:
   - GitHub Actions workflows for building and deploying the application.

3. **Docker**:
   - Dockerfile for containerizing the Go application.

4. **Kubernetes Deployment**:
   - YAML files for deploying the application to Kubernetes in Amazon EKS.

5. **Access**:
   - Visit the repository for the full project details: [Go Web App Repository](https://github.com/saikumartmv/go-web-app/actions)

---

## **Graphical Workflow Representation**
<div align="center">
  <h3>🚀 CI/CD Workflow</h3>
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
    <img src="https://github.com/user-attachments/assets/43da644e-52b9-47b8-bb43-e63befb6d294" alt="Pipeline Setup" width="30%" title="Step 1: CI/CD Pipeline Setup"/>
    <span style="font-size: 30px; font-weight: bold;">➔</span>
    <img src="https://github.com/user-attachments/assets/2ceb0db3-223a-49ae-aeb1-f967b7fb11ba" alt="Dockerized Application" width="30%" title="Step 2: Containerization with Docker"/>
    <span style="font-size: 30px; font-weight: bold;">➔</span>
    <img src="https://github.com/user-attachments/assets/a5b4d058-e285-4c52-a237-eb8cff6b85e9" alt="Deployment in EKS" width="30%" title="Step 3: Deployment in EKS"/>
  </div>
  <p style="font-style: italic; font-weight: bold; margin-top: 10px;">This diagram represents the CI/CD process for deploying a Golang application to Kubernetes in Amazon EKS.</p>
</div>

---

## **Steps and Screenshots**

### **1. GitHub Actions Pipeline**
- This screenshot illustrates the setup of the CI/CD pipeline using GitHub Actions for building and deploying the Go application.

![GitHub Actions Pipeline](https://github.com/user-attachments/assets/43da644e-52b9-47b8-bb43-e63befb6d294)

---

### **2. Dockerized Application**
- The application is containerized using Docker, as shown in the following screenshot.

![Dockerized Application](https://github.com/user-attachments/assets/2ceb0db3-223a-49ae-aeb1-f967b7fb11ba)

---

### **3. Kubernetes Deployment YAML**
- The YAML file for deploying the application to Kubernetes in Amazon EKS is created and validated.

![Kubernetes Deployment YAML](https://github.com/user-attachments/assets/a5b4d058-e285-4c52-a237-eb8cff6b85e9)

---

### **4. Deployment Success**
- The deployment is successfully executed in EKS, as depicted in this screenshot.

![Deployment Success](https://github.com/user-attachments/assets/8272a17a-c224-4ac6-be3e-7696d0322fa2)

---

### **5. Application Status in EKS**
- The application status in EKS is monitored and displayed, confirming successful deployment and scaling.

![Application Status](https://github.com/user-attachments/assets/37c5f311-03c8-4f35-855c-1133713faad4)

---

### **6. Live Application in EKS**
- The live application is accessible in the Kubernetes cluster and can be verified from the screenshot below.

![Live Application](https://github.com/user-attachments/assets/fe23df05-326a-4db3-9cc4-819ce10a6539)

---

## **Conclusion**
This repository provides a complete example of deploying a Golang application using a CI/CD pipeline integrated with Kubernetes in Amazon EKS. It demonstrates containerization with Docker, YAML-based deployment configurations, and automated workflows using GitHub Actions.
Visit the repository to explore more: [Go Web App Repository](https://github.com/saikumartmv/go-web-app/actions)






