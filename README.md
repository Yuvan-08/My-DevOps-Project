[![Deploy static content to Pages](https://github.com/Yuvan-08/My-DevOps-Project/actions/workflows/static.yml/badge.svg)](https://github.com/Yuvan-08/My-DevOps-Project/actions/workflows/static.yml)
# 🚀 Automated CI/CD Pipeline & Edge Deployment

**Final Year Computer Science DevOps Project**

## 📋 Project Overview
This repository demonstrates a fully functional Continuous Integration and Continuous Deployment (CI/CD) pipeline. The objective of this project is to bridge the gap between development and operations by automating the deployment lifecycle of a front-end environment. 

Instead of manual server provisioning and file transfer, this project leverages **Infrastructure as Code (IaC)** principles and cloud automation to instantly build and serve the application upon every code commit.

## 🏗️ Architecture & Workflow
The pipeline operates on a triggered automation model using **GitHub Actions**:

1. **Version Control:** Developer pushes code updates (`index.html`) to the `main` branch.
2. **Trigger:** GitHub Actions detects the push event and spins up a temporary Ubuntu runner.
3. **Build Phase:** The workflow packages the application assets.
4. **Deploy Phase:** The compiled environment is securely pushed to the GitHub Edge Network.
5. **Live Delivery:** The environment is hosted globally with 99.9% uptime and zero manual intervention.

## 🛠️ Tech Stack
* **Version Control:** Git / GitHub
* **CI/CD Orchestration:** GitHub Actions (`static.yml` workflow)
* **Hosting / Cloud:** GitHub Pages (Edge Network)
* **Frontend:** HTML5, Tailwind CSS (for rapid UI styling)

## 👨‍💻 Academic Details
* **Developer:** S Yuvan Kumar
* **USN:** 1DT23CS186
* **Institution:** Dayananda Sagar Academy of Technology and Management
* **Program:** B.E. Computer Science Engineering

---
*System continuously integrated and deployed successfully.*
