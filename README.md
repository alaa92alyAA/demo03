# 01-Project

Welcome to the second project in our DevOps Workshop Series!

## Overview

This installment focuses on effortlessly deploying a Java application on the Amazon Web Services (AWS) cloud platform. Utilizing a seamlessly automated pipeline orchestrated through GitHub, Jenkins, and AWS services, this project streamlines the deployment process, offering an efficient and scalable DevOps solution.

## Directories Structure

- **code directory:** Includes the source code.
- **devops directory:** Encompasses all DevOps-related work.

**Note:** The "devops" directory houses our DevOps-works.

## Getting Started

### Prerequisites

Ensure you have the following accounts set up:

- Github
- Jenkins
- AWS

### Setting up the workshop environment on your local machine:

1. Clone this repository by executing this command:

```bash
git clone https://github.com/DevOpsSquad-Org/01-Project.git
```

2. Open the cloned repo in your fav. IDE. and navigate to the `devops` directory:

```bash
cd devops
```

### Tasks to get done

1. Create a Jenkins job via the Jenkins UI.
2. Connect the Jenkins job to GitHub and AWS.
3. Deploy your Java app on AWS.
4. Document the project.

**Optimization Bonus:** For enhanced efficiency, consider configuring the Continuous Integration/Continuous Deployment (CI/CD) workflow through a Jenkinsfile rather than relying on the Jenkins user interface (UI). This approach promotes streamlined automation and version control of the build and deployment processes, offering greater transparency and reproducibility across your software development lifecycle.

Credit for the Java App: [Gamal Mohammad](https://github.com/Gamal-Mohammad/demo1.git)
