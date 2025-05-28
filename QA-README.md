# AWS Questions and Answers

## Cloud Computing Fundamentals

**Q1: What is AWS?**
A: Amazon Web Services (AWS) is a comprehensive cloud computing platform provided by Amazon. It offers a wide range of services including computing power, storage, databases, networking, analytics, machine learning, and more, delivered on-demand over the internet.

**Q2: What are the main benefits of cloud computing?**
A: The main benefits include:
- Cost efficiency (pay-as-you-use model)
- Scalability and elasticity
- High availability and reliability
- Global reach
- Security and compliance
- Innovation speed

## AWS Core Services

**Q3: What is Amazon EC2?**
A: Amazon Elastic Compute Cloud (EC2) is a web service that provides resizable compute capacity in the cloud. It allows users to launch virtual servers (instances) with various configurations of CPU, memory, storage, and networking.

**Q4: What is Amazon S3?**
A: Amazon Simple Storage Service (S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. It's designed to store and retrieve any amount of data from anywhere on the web.

**Q5: What is the difference between S3 and EBS?**
A: 
- S3 is object storage accessed via REST API, suitable for static content, backups, and data archiving
- EBS (Elastic Block Store) is block storage that attaches to EC2 instances, suitable for operating systems, databases, and file systems

## AWS Pricing and Scaling

**Q6: What is AWS Auto Scaling?**
A: AWS Auto Scaling monitors applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. It can scale EC2 instances, DynamoDB tables, and other AWS resources.

**Q7: What are the different pricing models in AWS?**
A: AWS offers several pricing models:
- On-Demand: Pay for compute capacity by the hour or second
- Reserved Instances: Commit to usage for 1-3 years for significant discounts
- Spot Instances: Bid for unused capacity at potentially lower costs
- Dedicated Hosts: Physical servers dedicated for your use

## Security and Networking

**Q8: What is AWS IAM?**
A: Identity and Access Management (IAM) is a service that helps you securely control access to AWS resources. It allows you to create and manage users, groups, roles, and permissions.

**Q9: What is a VPC in AWS?**
A: Virtual Private Cloud (VPC) is a virtual network dedicated to your AWS account. It's logically isolated from other virtual networks in the AWS cloud and allows you to launch AWS resources in a virtual network that you define.

**Q10: What is the difference between Security Groups and NACLs?**
A: 
- Security Groups operate at the instance level and act as virtual firewalls for EC2 instances
- Network Access Control Lists (NACLs) operate at the subnet level and provide an additional layer of security
- Security Groups are stateful, while NACLs are stateless

## Databases and Storage

**Q11: What is Amazon RDS?**
A: Amazon Relational Database Service (RDS) is a managed database service that makes it easy to set up, operate, and scale relational databases in the cloud. It supports multiple database engines including MySQL, PostgreSQL, MariaDB, Oracle, and SQL Server.

**Q12: What is DynamoDB?**
A: Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. It's designed for applications that need consistent, single-digit millisecond latency at any scale.

## Advanced Services

**Q13: What is AWS Lambda?**
A: AWS Lambda is a serverless computing service that runs code in response to events without provisioning or managing servers. You pay only for the compute time consumed, and Lambda automatically scales your applications.

**Q14: What is Amazon CloudFront?**
A: Amazon CloudFront is a content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds.

**Q15: What is AWS CloudFormation?**
A: AWS CloudFormation is a service that helps you model and set up your AWS resources using templates. It allows you to treat your infrastructure as code and manage related AWS resources as a single unit.

---

*This document contains essential AWS questions and answers for certification preparation and general knowledge.*
