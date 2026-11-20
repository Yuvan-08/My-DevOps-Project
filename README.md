# Automated CI/CD Pipeline & DevOps Project

A collaborative DevOps project demonstrating automated static website deployment, continuous integration, HTML quality checks, performance auditing, and GitHub Actions workflow automation.

## Overview

This project explores how DevOps practices can automate the software delivery lifecycle. It uses GitHub Actions to coordinate code validation, performance auditing, and deployment of a static website through GitHub Pages.

The project provides practical exposure to CI/CD concepts, workflow automation, and deployment management.

## Architecture

```text
Developer
   |
   v
GitHub Repository
   |
   v
GitHub Actions Workflows
   |
   +---- HTML Quality Checks
   |
   +---- Security Workflow Demonstration
   |
   +---- Lighthouse Performance Audit
   |
   +---- GitHub Pages Deployment
                |
                v
         Live Static Website
```

## Technology Stack

- **Version Control:** Git, GitHub
- **CI/CD:** GitHub Actions
- **Hosting:** GitHub Pages
- **Frontend:** HTML5
- **Quality Checks:** HTMLHint
- **Performance Testing:** Google Lighthouse CI
- **Automation:** YAML, Shell Commands

## Automated Workflows

The project contains four GitHub Actions workflows.

| Workflow | Purpose |
|---|---|
| `static.yml` | Automates deployment to GitHub Pages |
| `quality-test.yml` | Runs HTMLHint validation and custom content checks |
| `security.yml` | Demonstrates a basic security workflow; its current SAST step is simulated |
| `performance-audit.yml` | Runs Lighthouse audits against the deployed website |

### 1. Continuous Deployment

The deployment workflow:

- Triggers on pushes to the `main` branch.
- Supports manual execution.
- Configures GitHub Pages.
- Uploads the website as a deployment artifact.
- Deploys the website using GitHub Actions.

### 2. Code Quality Validation

The quality workflow:

- Installs HTMLHint.
- Checks the HTML document against selected rules.
- Performs custom string-based content checks.
- Attempts to create a GitHub issue when the workflow fails.

### 3. Security Workflow

The security workflow demonstrates the structure of a security-oriented CI/CD stage. Its current implementation uses placeholder commands rather than a real SAST or vulnerability-scanning engine.

### 4. Performance Auditing

The performance workflow:

- Targets the deployed GitHub Pages website.
- Runs Google Lighthouse CI.
- Uploads audit artifacts for inspection.

## Repository Structure

```text
My-DevOps-Project/
│
├── .github/
│   └── workflows/
│       ├── performance-audit.yml
│       ├── quality-test.yml
│       ├── security.yml
│       └── static.yml
│
├── index.html
└── README.md
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Yuvan-08/My-DevOps-Project.git
```

Navigate into the project:

```bash
cd My-DevOps-Project
```

Open `index.html` in a browser to view the static website.

## Deployment

The website is deployed through GitHub Pages.

**Live Project:**  
https://yuvan-08.github.io/My-DevOps-Project/

**GitHub Repository:**  
https://github.com/Yuvan-08/My-DevOps-Project

## Learning Outcomes

- Understanding CI/CD pipeline architecture.
- Automating deployments with GitHub Actions.
- Writing and managing YAML-based workflows.
- Integrating HTML quality validation.
- Performing Lighthouse performance audits.
- Understanding security checks within DevSecOps workflows.
- Managing static website deployment using GitHub Pages.

## Future Improvements

- Integrate a genuine SAST tool.
- Add dependency vulnerability scanning.
- Improve automated quality gates.
- Introduce Lighthouse performance thresholds.
- Improve workflow failure reporting.
- Add automated testing and deployment verification.

## Contributors

**Yuvan Kumar** — [GitHub](https://github.com/Yuvan-08)

**Manya MN** — [GitHub](https://github.com/mnmanya7-coder)

This project was collaboratively developed by both contributors, with shared participation in project development, implementation, and workflow design.

---

*Built collaboratively while exploring practical DevOps and CI/CD engineering.*
