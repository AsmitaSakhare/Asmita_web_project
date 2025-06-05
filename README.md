

---

```markdown
# 🚀 Full CI/CD Pipeline with AWS

This project demonstrates a complete CI/CD pipeline using AWS services to build, test, and deploy a Java-based web application. The pipeline automates the process from pushing code to production deployment on an EC2 instance.

## 🧰 Tools & Services Used

- **AWS CodePipeline** – Orchestrates the CI/CD process
- **AWS CodeBuild** – Builds the Java web application using Maven
- **AWS CodeDeploy** – Handles deployment to EC2
- **Amazon EC2** – Hosts the web app
- **Amazon S3** – Stores build artifacts
- **AWS CloudFormation** – Automates infrastructure provisioning
- **AWS CodeArtifact** – Manages dependencies
- **AWS IAM** – Role-based access and security
- **GitHub** – Source code management
- **VS Code** – Development environment

## 📋 Project Workflow

### Step 1: EC2 Setup
- Launch an EC2 instance
- SSH using VS Code
- Install Java and Maven
- Generate a basic web app

### Step 2: Version Control
- Initialize Git and connect to GitHub
- Push web app to remote repository

### Step 3: Dependency Management
- Set up CodeArtifact for Maven dependencies
- Configure IAM roles and permissions

### Step 4: Build Stage
- Create and configure CodeBuild project
- Define `buildspec.yml` for build commands

### Step 5: Deployment Stage
- Launch infrastructure using CloudFormation
- Write deployment scripts
- Deploy the app with CodeDeploy

### Step 6: Full Pipeline
- Use CodePipeline to automate entire CI/CD process
- Connect GitHub (source), CodeBuild (build), and CodeDeploy (deploy)

## 📸 Project Screenshots
![Screenshot 2025-06-05 115254](https://github.com/user-attachments/assets/5d3db2f0-3d75-4cee-baaf-033211ff399d)

## 📍 LinkedIn Project Log

I've been documenting each day's progress of this project on LinkedIn.  
👉 [Check it out here]((https://www.linkedin.com/posts/asmitasakhare_devops-cicd-aws-activity-7336279198799466497-yfAa?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD5ElDgBhu1iIfjTnh3tuon3JIPnGPnj66E)) 

## 📦 Folder Structure

```

project-root/
│
├── src/                  # Java source files
├── buildspec.yml         # Build instructions for CodeBuild
├── appspec.yml           # Deployment config for CodeDeploy
├── cloudformation/       # Infrastructure as code scripts
├── README.md             # Project documentation

```

## ✅ Outcome

- Automated deployment process from code push to production
- Reduced manual deployment time by over 90%
- Gained hands-on experience with core AWS DevOps services

## ✨ Author

- [Asmita Sakhare]((https://www.linkedin.com/in/asmitasakhare/))
- [GitHub Profile]((https://github.com/AsmitaSakhare))

---




