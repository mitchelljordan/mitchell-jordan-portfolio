## Car Service Marketplace – Cloud Technology Project

Car Service Marketplace is a cloud-native web application designed to connect users with local vehicle service providers. The system was built using AWS serverless technologies to create a scalable, cost-efficient platform.

---

### Project Overview
The application allows users to:
- Search for car service providers by location  
- View company details such as address and service information  
- Navigate to relevant providers based on their needs  

The system acts as a centralized directory for automotive services.

---

### Architecture & Technologies

The application was built using a serverless architecture:

- **Amazon S3**
  - Hosted the static frontend  
  - Enabled versioning for file history  
  - Used lifecycle policies to move older data to Glacier for cost optimization  

- **Amazon API Gateway**
  - Served as the entry point for client requests  
  - Configured for GET requests  
  - Implemented rate limiting to reduce abuse  

- **AWS Lambda**
  - Handled backend logic  
  - Processed API requests and retrieved data from the database  
  - Enabled separation between frontend and backend  

- **Amazon DynamoDB**
  - Stored company data  
  - Partition Key: City  
  - Sort Key: Address  
  - Optimized for efficient location-based queries  

![Architecture Diagram](images/diagram.png)

---

### My Contributions
- Designed and implemented the serverless architecture  
- Integrated AWS services (S3, Lambda, API Gateway, DynamoDB)  
- Structured DynamoDB for efficient query performance  
- Applied cost optimization strategies (lifecycle rules, storage tiering)  
- Configured API Gateway with basic security controls  

---

### Key Challenges & Growth

An earlier version of this project was unsuccessful due to:
- Difficulty implementing IAM role-based access control  
- Limited understanding of API Gateway and Lambda integration  
- Spending time on unsupported or overly complex solutions  

For the final version, we:
- Simplified the architecture to focus on core functionality  
- Applied newly learned cloud concepts effectively  
- Prioritized working solutions over unnecessary complexity  

This shift allowed us to successfully deploy a functional system.

---

### Additional Concepts Explored
- Designed a prototype using SNS and SQS for a secure submission system  
- Considered future expansion for full CRUD operations  
- Planned advanced filtering and dynamic features  

---

### What I Learned
- How to design and deploy serverless architectures using AWS  
- The importance of simplicity and iteration in system design  
- How core AWS services integrate to form scalable applications  
- How to troubleshoot and recover from failed implementations  

---

### Why This Project Matters
This project demonstrates my ability to design cloud-based systems, adapt to technical challenges, and deliver working solutions under constraints. It highlights my understanding of serverless architecture, scalability, and cost-efficient cloud development.
