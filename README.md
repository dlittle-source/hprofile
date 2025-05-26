![Alt text](image.png)

**Project: CI/CD Workflow with GitHub Actions**

**Overview:**
In this project, I developed a **fully automated CI/CD pipeline** using **GitHub Actions** to deploy a dynamic web application. The workflow integrates **Docker**, **AWS ECS Fargate**, and several AWS services to deliver a streamlined, scalable, and secure deployment process. I implemented variables throughout the project to enhance flexibility and reusability, and leveraged GitHub Marketplace to integrate additional tools that extended the project's capabilities.

**Deployment Steps:**

1. **GitHub Secrets:**
   - Configured **GitHub Secrets** to securely store sensitive credentials such as **AWS access keys**, **RDS endpoint**, and **SonarCloud token**, preventing hardcoding and enhancing 
     repository security.

2. **SonarCloud Integration:**
   - Integrated **SonarCloud** for continuous static code analysis and configured a custom Quality Gate to enable early detection of        bugs, vulnerabilities, and code smells 
     throughout the CI/CD pipeline.

3. **Virtual Private Cloud (VPC):**
   - Provisioned a **VPC** with **3 public subnets** distributed across **two Availability Zones** to ensure high availability, scalability, and fault tolerance.

4. **Security Groups:**
   - Created **Security Groups** to define inbound and outbound traffic rules, functioning as firewalls to protect EC2 instances and      other AWS resources.
