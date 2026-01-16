# 🚀 AWS CI/CD Pipeline Project

## 📌 Overview
This project demonstrates an **end-to-end CI/CD pipeline** using AWS services.  
Any code push to GitHub automatically triggers **build and deployment** to an EC2 instance ⚡.

---

## 🛠️ Services Used
- 🧩 **AWS CodePipeline** – CI/CD workflow orchestration
- 🏗️ **AWS CodeBuild** – Build and package application
- 🚀 **AWS CodeDeploy** – Deploy application to EC2
- 🖥️ **Amazon EC2** – Application hosting server
- 🗄️ **Amazon S3** – Artifact storage
- 🔐 **AWS IAM** – Role-based access control
- 🐙 **GitHub** – Source code management

---

## 🔄 CI/CD Workflow
1. 👨‍💻 Developer pushes code to GitHub
2. 🔔 AWS CodePipeline is triggered automatically
3. 🏗️ CodeBuild builds the application
4. 📦 Build artifacts are stored in S3
5. 🚀 CodeDeploy deploys files to EC2
6. 🌐 Application is served via Apache web server

---

## 📂 Project Structure
aws-ci-cd-pipeline-pruthviraj/
│
├── app/ # Application files
├── scripts/ # Deployment scripts
├── buildspec.yml # Build instructions 🏗️
├── appspec.yml # Deployment instructions 🚀
├── README.md
└── .gitignore
