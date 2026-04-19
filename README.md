# TAG Cloud Architects AWS Capstone Project
## Overview
This project is a cloud architecture capstone focused on migrating a university student 
## Problem
The original system used a single virtual machine for both the frontend and backend, whi
## Objective
Design a proof of concept in AWS that improves performance, supports growth, increases av
## Business Requirements- Deploy in US East (N. Virginia)- Use a load balancer as the single entry point- Separate web and database tiers- Support about 2,000 visitors per day- Scale automatically during traffic spikes- Maintain self-healing web infrastructure- Apply appropriate security controls- Keep costs low- Allow users to view, add, delete, and modify student records without noticeable delay
## Solution Summary
The proposed design uses

 Application Load Balancer- Amazon EC2 Auto Scaling web tier- Amazon RDS for MySQL- Amazon CloudWatch- AWS Secrets Manager
## Key Design Decisions- Two-tier architecture for better security and performance- High availability across multiple Availability Zones- Auto Scaling for dynamic capacity- Managed database service for reliability and simplicity- Secrets Manager to avoid storing database credentials on the web tier
## Repository Contents- Problem statement- Requirements documents- Design and cost modeling- AWS pricing estimate- Final presentation
## Team
TAG Cloud Architects- Terica Shepard- Alexia Hinton- Godspower Oseratin Ogunseri

## Project Evidence
This repository contains the team's class deliverables that document the full cloud arch
1. Capstone problem statement
2. Requirements gathering artifacts
3. Final design and cost modeling document
4. AWS Pricing Calculator estimate export
5. Team presentation deck

   Project Structure
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
