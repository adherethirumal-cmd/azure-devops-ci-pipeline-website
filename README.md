# 🚀 Azure DevOps CI Pipeline for Web Application

## 📌 Project Overview

This project demonstrates the implementation of a Continuous Integration
(CI) pipeline using Azure DevOps for a web application hosted in a
GitHub repository.

The pipeline automatically retrieves the source code, validates the
repository contents, packages the required application files, and
publishes the generated package as a build artifact.

---

## 🎯 Objectives

- Integrate GitHub with Azure DevOps
- Implement a CI pipeline
- Automate source-code validation
- Package application files
- Publish build artifacts
- Understand Azure DevOps pipeline execution
- Gain practical experience with YAML pipelines

---

## 🏗️ Architecture

GitHub Repository
        ↓
Azure DevOps Pipeline
        ↓
Source Checkout
        ↓
Repository Validation
        ↓
Application Packaging
        ↓
Build Artifact
        ↓
Artifact Publishing

---

## 🛠️ Technologies Used

- Git
- GitHub
- Azure DevOps
- Azure Pipelines
- YAML
- Linux-based Microsoft-hosted agent
- HTML
- CSS
- JavaScript

---

## ⚙️ Methodology

### 1. Source Code Management

The web application source code was maintained in GitHub.

### 2. Pipeline Trigger

The pipeline was configured to trigger from the main branch.

### 3. Source Validation

The pipeline checks the repository contents before processing the
application.

### 4. Application Packaging

Required HTML, CSS, JavaScript and documentation files are copied
into the artifact staging directory.

### 5. Artifact Publishing

The packaged application is published as a build artifact for
subsequent deployment stages.

---

## 🔄 CI Pipeline Flow

GitHub
  ↓
Pipeline Trigger
  ↓
Checkout Source
  ↓
Validate Files
  ↓
Package Application
  ↓
Publish Artifact

---

## 📊 Results

✅ GitHub integration completed

✅ Azure DevOps CI pipeline successfully executed

✅ Source files successfully processed

✅ Application files packaged

✅ Build artifact successfully generated

✅ Build artifact successfully published

---

## 📸 Screenshots

### Azure DevOps Pipeline

![Pipeline](<img width="1907" height="792" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/6956c597-6880-4e43-aadb-8459d0c57397" />
.png)

### Build Logs

![Build Logs](screenshots/build-logs.png)<img width="1912" height="966" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/7f3f4135-deaf-45de-9729-abd5f04110d6" />


### Published Artifact

![Artifact]<img width="1917" height="965" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/998053c9-d229-4da4-8219-065294e50a91" />


---

## 🧠 Key Learnings

- Continuous Integration
- Azure DevOps Pipelines
- YAML pipeline configuration
- GitHub integration
- Build automation
- Artifact management
- Pipeline troubleshooting

---

## 🚀 Future Improvements

- Add automated testing
- Implement Continuous Deployment
- Containerize the application using Docker
- Deploy the application to cloud infrastructure
- Add monitoring and logging
