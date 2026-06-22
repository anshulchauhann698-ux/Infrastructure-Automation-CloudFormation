# Infrastructure Automation using AWS CloudFormation

## Overview

This project demonstrates Infrastructure as Code (IaC) using AWS CloudFormation to automate AWS resource provisioning.

## Technologies Used

* AWS CloudFormation
* Amazon EC2
* Amazon VPC
* IAM
* Security Groups

## Features

* Automated infrastructure deployment using CloudFormation templates
* Provisioning of EC2 instances and networking resources
* Reusable and version-controlled infrastructure definitions
* Reduced manual configuration effort through Infrastructure as Code

## Project Workflow

1. Create CloudFormation stack
2. Provision AWS resources automatically
3. Deploy EC2 instance
4. Configure networking and security settings
5. Verify successful infrastructure deployment

## Learning Outcomes

* Infrastructure as Code (IaC)
* AWS resource automation
* Cloud infrastructure management
* CloudFormation template design
* Automated provisioning and deployment

## Infrastructure Diagram

```text
                    AWS Cloud
                         │
                         ▼
                 CloudFormation
                         │
                         ▼
                    Amazon VPC
                         │
                         ▼
                 Security Group
                         │
                         ▼
                  EC2 Instance
                         │
                         ▼
                   Web Server
                    (Apache)
                         │
                         ▼
                    Web Page
```

### Architecture Flow

User → Web Browser → EC2 Instance → Apache Web Server

CloudFormation automates the provisioning of VPC, Security Group, and EC2 resources through Infrastructure as Code (IaC) templates.

```
```


## Repository Structure

templates/ → CloudFormation templates

screenshots/ → Deployment screenshots

README.md → Project documentation
