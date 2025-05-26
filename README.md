![Alt text](image.png)

**Project: CI/CD Workflow with GitHub Actions**

**Overview:**
In this project, I developed a **fully automated CI/CD pipeline** using **GitHub Actions** to deploy a dynamic web application. The workflow integrates **Docker**, **AWS ECS Fargate**, and several AWS services to deliver a streamlined, scalable, and secure deployment process. I implemented variables throughout the project to enhance flexibility and reusability, and leveraged GitHub Marketplace to integrate additional tools that extended the project's capabilities.

**Deployment Steps:**

1. **GitHub Secrets:**
   - Configured **GitHub Secrets** to securely store sensitive credentials such as **AWS access keys**, **RDS endpoint**, and **SonarCloud token**, preventing hardcoding and enhancing 
     repository security.

2. **Private SSH Key**
   - Configured the repository to use a private SSH key for secure access.

3. **SonarCloud Integration:**
   - Integrated **SonarCloud** for continuous static code analysis and configured a custom Quality Gate to enable early detection of bugs, vulnerabilities, and code smells 
     throughout the CI/CD pipeline.

4. **Virtual Private Cloud (VPC):**
   - Provisioned a **VPC** with **3 public subnets** distributed across **two Availability Zones** to ensure high availability, scalability, and fault tolerance.

5. **Security Groups:**
   - Created **Security Groups** to define inbound and outbound traffic rules, functioning as firewalls to protect EC2 instances and other AWS resources.

6. **Availability Zones:**
   - Deployed critical infrastructure across **two Availability Zones** to achieve fault tolerance and minimize the risk of single points of failure.

7. **EC2 Instance:**
   - Launched an **EC2 instance** in a public subnet, used for **importing data into AWS RDS** during the deployment process.

8. **Docker & ECR:**
   - Built the application as a **Docker image** and pushed it to **Amazon Elastic Container Registry (ECR)** to facilitate container-based deployment.

9. **AWS ECS Fargate:**
   - Used **AWS ECS with Fargate** to run and manage the containerized application in a **serverless** environment, simplifying infrastructure management and scaling.

10. **AWS RDS:**
   - Implemented **Amazon RDS** to manage a **relational database** backend, ensuring data integrity, security, and automated maintenance for end-user data.

11. **Maven:**
    - Maven served as the primary build tool, handling the compilation, dependency management, and packaging of the Java application.

12. **AWS ELB:**
    - To efficiently manage network traffic, I deployed AWS Elastic Load Balancer to evenly distribute incoming requests across multiple targets spanning multiple Availability Zones.
