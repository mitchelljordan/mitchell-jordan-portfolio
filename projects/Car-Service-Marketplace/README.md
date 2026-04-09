### Car Service Marketplace – Cloud Technology Project

This project was developed as the final group assignment for a Cloud Technology course. The objective was to design and deploy a scalable cloud-based application using AWS services. Working in a team of two, we built a serverless web platform that connects users with local car service providers.

# Project Overview

The application allows users to search for vehicle service providers by location and view relevant company information. It acts as a centralized portal, helping users identify and navigate to service providers based on their needs.

Architecture & Technologies

The system was designed using a serverless architecture with the following AWS services:

Amazon S3
Hosted the static frontend.
Enabled versioning to maintain file history
Applied lifecycle policies to transition older data to Glacier for cost optimization
Amazon API Gateway
Served as the entry point for client requests
Configured to handle GET requests
Implemented basic rate limiting to reduce spam and abuse
AWS Lambda
Handled backend logic by processing API requests and retrieving data from the database
Triggered via API Gateway events
Enabled clear separation between frontend and backend
Amazon DynamoDB
Used as a NoSQL database for storing company data
Partition Key: City
Sort Key: Address
Optimized for efficient location-based queries with low read capacity usage
Key Contributions & Learning
Designed and implemented a serverless architecture integrating multiple AWS services
Applied cost optimization strategies such as S3 lifecycle rules and storage tiering
Structured DynamoDB for efficient query performance
Configured API Gateway with basic security controls (rate limiting)
Gained hands-on experience with event-driven architecture using Lambda
Challenges & Growth

An earlier version of this project, attempted at the beginning of the course, was unsuccessful. We struggled with:

Implementing IAM role-based access control due to environment limitations
Lack of understanding of API Gateway and Lambda integration
Over-investing time in unsupported solutions

For the final project, we:

Refocused on achievable solutions within platform constraints
Leveraged newly learned concepts to properly integrate AWS services
Avoided unnecessary complexity and prioritized core functionality

This shift allowed us to successfully deliver a working system and demonstrate clear technical growth.

Additional Concepts Explored
Designed a prototype using SNS and SQS for a secure, email-based company submission system
Considered future expansion for full CRUD operations and more advanced filtering
Reflection

This project highlights my ability to learn from failure, adapt to technical constraints, and incrementally improve system design. It demonstrates a solid foundation in cloud development and serverless architecture.

While the system could be extended with additional features, it effectively showcases my understanding of how core AWS services interact to build scalable, efficient applications.
