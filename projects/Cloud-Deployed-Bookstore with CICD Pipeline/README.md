## Cloud-Deployed Bookstore with CI/CD Pipeline

Cloud-Deployed Bookstore is a full-stack application designed to demonstrate modern cloud deployment and DevOps practices using AWS. The project focuses on building, containerizing, and deploying a scalable application using a fully managed cloud infrastructure.

---

### Project Overview
The system consists of a frontend and backend service that are containerized using Docker and deployed through AWS services. A CI/CD pipeline automates the build and deployment process, enabling continuous integration and delivery with minimal manual intervention.

---

### Architecture & Technologies

The system is built using a containerized, cloud-native architecture:

- **Amazon ECS (Fargate)**
  - Runs containerized frontend and backend services  
  - Eliminates the need to manage EC2 instances  

- **Amazon ECR**
  - Stores Docker images for both services  
  - Integrated with CI/CD pipeline for automated updates  

- **Application Load Balancer**
  - Routes traffic between frontend and backend  
  - Uses path-based routing (`/api` → backend)  

- **Amazon RDS (PostgreSQL)**
  - Managed relational database with Multi-AZ failover  
  - Ensures high availability and reliability  

- **AWS Secrets Manager**
  - Securely stores database credentials  
  - Injected into containers at runtime  

- **VPC (Networking)**
  - Public subnets for load balancer  
  - Private subnets for ECS services and database  
  - NAT Gateway for secure outbound access  

- **CI/CD Pipeline**
  - Automates build, push (ECR), and deployment (ECS)  
  - Triggered by code changes  

![Architecture Diagram](images/architecture_diagram.png)

---

### My Contributions
- Designed and implemented the AWS cloud architecture  
- Containerized application using Docker  
- Configured ECS services and task definitions  
- Set up CI/CD pipeline for automated deployments  
- Implemented secure environment configuration using Secrets Manager  
- Managed networking with VPC, subnets, and security groups  

---

### Key Features
- Fully automated CI/CD pipeline  
- Containerized microservice-style architecture  
- Scalable deployment using ECS Fargate  
- Secure credential management  
- High availability with Multi-AZ database  

---

### Key Challenges & Optimization

**Security & Networking**
- Designed private subnet architecture to isolate services  
- Used Secrets Manager to avoid hardcoding credentials  

**Cost Optimization**
- Used Fargate to avoid idle infrastructure costs  
- Implemented temporary bastion host only during database migration  

**Routing & Architecture**
- Introduced `/api` routing to support load balancer path-based routing  
- Enabled frontend and backend to function as a unified application  

---

### What I Learned
- How to design and deploy production-style cloud architectures  
- Practical experience with container orchestration using ECS  
- How CI/CD pipelines improve development efficiency and reliability  
- The importance of secure infrastructure design (VPC, secrets, isolation)  
- How to balance scalability, cost, and maintainability in cloud systems  

---

### Why This Project Matters
This project demonstrates my ability to build and deploy real-world, production-ready systems using modern cloud and DevOps practices. It highlights my strengths in system design, automation, and secure cloud architecture—key skills for a Computer Programmer Analyst working with scalable applications.
