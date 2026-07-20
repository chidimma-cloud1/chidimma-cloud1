# AWS Core Services

## Overview
AWS organizes its 200+ services into categories based on functionality. Each category solves a specific layer of infrastructure from raw computing power to artificial intelligence.

## 1. Compute
Compute services provide the processing power to run your applications.

### Amazon EC2 (Elastic Compute Cloud)
Provides secure, resizable virtual servers in the cloud with complete control over processor, storage, networking, and operating system configurations.

### AWS Lambda
A serverless compute service, you write your code, and Lambda handles everything else. You only pay for the compute time your code actually runs.

### Amazon ECS & EKS
Both are managed services for deploying, managing, and scaling containerized applications.
ECS: Favours simplicity and deep AWS integration
EKS: Uses open-source Kubernetes for flexibility and multi-cloud portability

## 2. Storage
Scalable, durable, and secure storage options for different types of data.

### Amazon S3 (Simple Storage Service)
Object storage for files, images, backups, and more — accessible from anywhere on the internet.

### Amazon EBS (Elastic Block Store)
Block-level storage that attaches directly to EC2 instances — the hard drive of your virtual server.

### Amazon Glacier
Low-cost storage is optimized for data archiving and long-term backup. Not built for speed, built for keeping things safe and cheap.

## 3. Databases
Fully managed database services that scale automatically and handle administration tasks.

### Amazon RDS (Relational Database Service)
Managed relational database supporting MySQL, PostgreSQL, Oracle, SQL Server, and Amazon Aurora.

### Amazon DynamoDB
A fast, flexible NoSQL database delivering single-digit millisecond latency at any scale.

## 4. Networking & Content Delivery
Services to securely connect your cloud resources, route traffic, and deliver content globally.

### Amazon VPC (Virtual Private Cloud)
Provision a logically isolated section of the AWS Cloud where you launch resources in a virtual network you define.

### Amazon Route 53
A highly available and scalable Domain Name System (DNS) web service.

### Amazon CloudFront
A global CDN that securely delivers data, videos, applications, and APIs to users worldwide with low latency.

## 5. Artificial Intelligence & Machine Learning
Tools that put machine learning capabilities into the hands of every developer and data scientist.

### Amazon SageMaker
A fully managed service to build, train, and deploy machine learning models at scale.

### Amazon Bedrock
A fully managed service providing API access to foundational models from leading AI companies, including Amazon's own.

## 6. Security, Identity & Compliance
Tools to protect your data, accounts, and infrastructure at every layer.

### AWS IAM (Identity and Access Management)
Securely manage access to AWS services and resources control who can access what.

### Amazon GuardDuty
Continuous security monitoring that analyzes AWS CloudTrail events and VPC Flow Logs to identify threats.

### Amazon CloudWatch
Monitoring and management service for your AWS resources and applications.

### AWS CloudFormation
Manage your entire AWS infrastructure as code defines resources in a template, and CloudFormation builds it automatically.

## Key Takeaway
Six categories, dozens of services, one theme: AWS isn't selling you servers. It's selling you the ability to stop worrying about infrastructure and focus on building.
