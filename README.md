# DevOps System Design Assignment

## Architecture Overview
This repository contains the design for a scalable cloud architecture using AWS services, including UI hosting, API backend, database, and CI/CD pipeline.

## Components Designed
1. **UI Architecture** - S3 + CloudFront for scalable frontend hosting
2. **API Architecture** - ECS Fargate for backend services  
3. **Database Architecture** - RDS PostgreSQL with high availability
4. **CI/CD Pipeline** - GitHub Actions workflow

## Diagrams
- [System Architecture](./diagrams/architecture-diagram.pdf)
- [CI/CD Pipeline](./diagrams/cicd-pipeline.pdf)

## Design Decisions
- **Scalability**: Horizontal scaling with load balancers and auto-scaling groups
- **Security**: VPC isolation, security groups, and secrets management
- **Availability**: Multi-AZ deployment and automated failover
- **Maintenance**: Fully managed services where possible
