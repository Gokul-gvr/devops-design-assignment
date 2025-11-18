# DevOps Design Assignment

## 1. Overview
This project contains the architecture design, CI/CD pipeline, and documentation for deploying a UI, API, and Database in AWS.

## 2. Deliverables
- AWS Architecture Diagram (in diagrams/architecture-diagram.pdf)
- CI/CD Pipeline Diagram (in diagrams/cicd-pipeline.pdf)
- Architecture Explanation
- Security & Scaling Strategy

## 3. Architecture Components
- VPC with Public & Private Subnets
- Application Load Balancer → EC2 Auto Scaling (API)
- S3 + CloudFront (UI Hosting)
- RDS MySQL (private subnet)
- IAM, Security Groups, NACL for security
- CloudWatch, S3 Logging

## 4. CI/CD Flow
- GitHub → AWS CodePipeline → CodeBuild → S3/EC2 Deployment

