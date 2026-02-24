# AWS Cloud Practitioner Level Experiments

This repository contains a collection of **AWS hands-on experiments** performed at the **Cloud Practitioner** level. The goal of these exercises is to demonstrate practical knowledge and skills in  AWS services, security, storage, networking, and cost management.

## Table of Contents

1. [IAM & Security](#iam--security)  
2. [EC2 & Compute](#ec2--compute)  
3. [S3 & Storage](#s3--storage)  
4. [Networking & VPC](#networking--vpc)  
5. [Databases](#databases)  
6. [Infrastructure as Code](#infrastructure-as-code)  
7. [Application Deployment](#application-deployment)  
8. [Monitoring & Logging](#monitoring--logging)  
9. [Workflows & Automation](#workflows--automation)  
10. [Cost Management](#cost-management)

---

## IAM & Security

- Created **IAM roles** for EC2 with `AmazonS3ReadOnlyAccess`.  
- Designed **custom IAM policies** to allow listing all S3 buckets while denying deletion.  
- Viewed the **IAM Credential Report** to audit access.  
- Implemented **Service Control Policies (SCPs)** to block deletion of EC2 instances.  
- Created **IAM users** with programmatic access and S3 read-only permissions, including generating access keys.  
- Configured **Multi-Factor Authentication (MFA)** and role-based access controls.  

---

## EC2 & Compute

- Launched **Linux EC2 instances** in public subnets.  
- Created and configured **security groups** to restrict SSH (port 22) access to specific IPs.  
- Created **volumes from snapshots** and attached them to instances.  
- Used **nano and vi editors** to create and manage files on EC2.  
- Configured **Internet Gateway (IGW)** for public access to EC2 instances.  

---

## S3 & Storage

- Uploaded files to S3 and experimented with different **storage classes** (One Zone-IA, Glacier, Intelligent-Tiering).  
- Configured **bucket policies** for public read access.  
- Enabled **server access logging** to monitor bucket usage.  
- Used **Amazon Data Lifecycle Manager (DLM)** to schedule automated backups.  
- Deployed and configured **AWS Storage Gateway** (File, Volume, Tape modes) to integrate on-premises storage with AWS.  

---

## Networking & VPC

- Designed and implemented **custom VPC architecture** with subnets, route tables, and gateways.  
- Configured **network security** using Security Groups and NACLs.  
- Set up **VPC peering** and **transit gateways** for cross-VPC communication.  

---

## Databases

- Deployed and configured **RDS instances**, including backups, read replicas, and Multi-AZ setups.  
- Designed and managed **DynamoDB tables** with partition keys, sort keys, Global Secondary Indexes, and Streams for real-time processing.  

---

## Infrastructure as Code

- Created **CloudFormation templates** to deploy AWS infrastructure.  
- Implemented **nested stacks** and **cross-stack references**.  
- Managed **stack updates, rollbacks**, and CI/CD integration.  

---

## Application Deployment

- Deployed applications using **Elastic Beanstalk**.  
- Configured application environments and performed **blue-green deployments**.  
- Monitored **application health and performance**.  

---

## Monitoring & Logging

- Set up **CloudWatch** metrics, alarms, and logs for operational monitoring.  
- Built **custom dashboards** for proactive alerting and analysis.  

---

## Workflows & Automation

- Designed and implemented **complex workflows** integrating multiple AWS services.  
- Configured error handling, retries, and monitored workflow execution.  

---

## Cost Management

- Set up **budgets and cost alerts**.  
- Analyzed spending patterns and implemented **cost optimization strategies**.  

---

## Summary

These experiments demonstrate hands-on knowledge in **AWS foundational services**, covering **security, compute, storage, networking, databases, deployment, monitoring, automation, and cost management**. This repository reflects practical skills aligned with the **AWS Certified Cloud Practitioner** learning path.
