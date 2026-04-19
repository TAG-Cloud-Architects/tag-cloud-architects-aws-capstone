# TAG Cloud Architects AWS Capstone Project
## Overview
This project is a cloud architecture capstone focused on migrating a university student 
## Problem
The current system the university is using is University’s current student records web application is running on a single-tier, on-premise virtual machine, where both the frontend and backend are hosted together. This setup is causing:

Performance issues (slow response times)
Availability problems (downtime during peak admissions periods)
Scalability limitations (cannot handle spikes in traffic)
Security and reliability risks (single point of failure)
## Objective
Design and implement a proof of concept (POC) by migrating the application to the Amazon Web Services within 8 weeks, with goals to:

Improve performance and availability during peak usage
Enable scalability to handle fluctuating workloads
Adopt a multi-tier, cloud-native architecture (separating frontend, backend, database)
Leverage AWS best practices (e.g., load balancing, auto scaling, managed services)
Enhance security and fault tolerance
Optimize costs while supporting future growth
## Solution Summary
**Proposed AWS Architecture Components**
Application Load Balancer – Distributes incoming traffic across multiple instances for high availability and fault tolerance
Amazon EC2 Auto Scaling (Web/Application Tier) – Dynamically adjusts the number of instances based on demand
Amazon RDS for MySQL (Database Tier) – Provides a managed, scalable, and highly available database solution
Amazon CloudWatch – Monitors performance metrics, logs, and triggers alerts
AWS Secrets Manager – Securely stores and retrieves database credentials and other sensitive data

## Team
**TAG Cloud Architects**
-Terica Shepard
-Alexia Hinton
-Godspower Oseratin Ogunseri

## Project Evidence
This repository contains the team's class deliverables that document the full cloud arch
1. Capstone problem statement
2. Requirements gathering artifacts
3. Final design and cost modeling document
4. AWS Pricing Calculator estimate export
5. Team presentation deck

  ## Project Structure
│
├── README.md
├── LICENSE
│
├── docs/
│   ├── problem-statement/
│   │   └── Capstone_Problem_Statement.docx
│   ├── requirements/
│   │   ├── Requirements_Final.xlsx
│   │   └── TAG_Cloud_Architects_Requirements.xlsx
│   ├── design/
│   │   └── Design_and_Cost_Modeling.pdf
│   ├── estimates/
│   │   └── AWS_Estimate_TAG_Cloud_Architects.pdf
│   └── presentation/
│       └── TAG_Cloud_Architects.pptx
│
├── diagrams/
│   └── architecture-diagram.png
│
└── images/
    └── two-tier-architecture-of-student-record.png
