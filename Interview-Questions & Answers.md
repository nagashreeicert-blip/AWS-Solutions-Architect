# 📘 AWS Solutions Architect Interview Questions & Answers  
### *Structured by Beginner, Intermediate, and Advanced Modes*

---

## 1️⃣ Beginner Mode
**Focus:** Core AWS services, fundamental cloud concepts  

1. **Q:** What is AWS?  
   **A:** AWS (Amazon Web Services) is a cloud platform offering compute, storage, networking, and other services on-demand.

2. **Q:** Explain the difference between EC2 and S3.  
   **A:** EC2 provides virtual servers for compute, while S3 is an object storage service for storing and retrieving data.

3. **Q:** What is a VPC?  
   **A:** A Virtual Private Cloud (VPC) isolates your AWS resources in a private network with configurable subnets, routing, and security.

4. **Q:** What is IAM in AWS?  
   **A:** IAM (Identity and Access Management) allows you to manage users, roles, and permissions securely.

5. **Q:** What are security groups?  
   **A:** Security groups act as virtual firewalls for EC2 instances controlling inbound and outbound traffic.

6. **Q:** What is the difference between vertical and horizontal scaling?  
   **A:** Vertical scaling increases instance size; horizontal scaling adds more instances to distribute load.

7. **Q:** Explain the difference between public and private subnets.  
   **A:** Public subnets have internet access, private subnets are isolated and typically host backend resources.

8. **Q:** What is AWS Lambda?  
   **A:** Lambda is a serverless compute service that runs code in response to events without managing servers.

9. **Q:** What is an AWS region and availability zone?  
   **A:** A region is a geographical area with multiple availability zones (data centers) for redundancy and fault tolerance.

10. **Q:** How do you monitor AWS resources?  
    **A:** Using AWS CloudWatch for metrics, logs, and alarms to track resource performance.

---

## 2️⃣ Intermediate Mode
**Focus:** Architecture, design patterns, and service integration  

1. **Q:** What is ELB and why is it used?  
   **A:** Elastic Load Balancer distributes traffic across multiple instances to improve availability and fault tolerance.

2. **Q:** What is the difference between S3 and EBS?  
   **A:** S3 is object storage, scalable for files; EBS provides block-level storage attached to EC2 instances.

3. **Q:** How do you implement high availability in AWS?  
   **A:** Deploy resources across multiple AZs, use ELB, auto-scaling groups, and RDS Multi-AZ deployments.

4. **Q:** Explain the Well-Architected Framework.  
   **A:** It consists of five pillars: Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization.

5. **Q:** What is CloudFormation?  
   **A:** CloudFormation is Infrastructure as Code (IaC) that automates AWS resource provisioning using templates.

6. **Q:** What are AWS Route 53 and its use cases?  
   **A:** Route 53 is a DNS service for domain routing, health checks, and global traffic management.

7. **Q:** How do you secure S3 buckets?  
   **A:** Use IAM policies, bucket policies, encryption, and enable MFA delete.

8. **Q:** What is Auto Scaling?  
   **A:** Auto Scaling automatically adjusts EC2 instance count based on load or schedule to maintain performance.

9. **Q:** Difference between RDS and DynamoDB?  
   **A:** RDS is a relational database service, DynamoDB is a NoSQL, key-value, and document database.

10. **Q:** How do you implement disaster recovery in AWS?  
    **A:** Use multi-region deployments, snapshots, backups, cross-region replication, and failover strategies.

---

## 3️⃣ Advanced Mode
**Focus:** Enterprise architecture, optimization, and complex scenarios  

1. **Q:** Explain AWS Well-Architected Cost Optimization best practices.  
   **A:** Use Reserved or Spot Instances, right-size resources, implement Auto Scaling, and monitor cost using AWS Cost Explorer.

2. **Q:** How do you design a multi-region, fault-tolerant application?  
   **A:** Deploy app components in multiple regions, use Route 53 latency-based routing, replicate data, and implement failover mechanisms.

3. **Q:** How do you secure VPC resources using NACLs and security groups?  
   **A:** Security groups act at instance level; NACLs control subnet-level traffic; combine both for layered security.

4. **Q:** What is AWS Direct Connect?  
   **A:** Dedicated network connection from on-premises to AWS for low latency, secure, and consistent bandwidth.

5. **Q:** How do you manage secrets and sensitive data in AWS?  
   **A:** Use AWS Secrets Manager or AWS KMS to store, encrypt, and rotate secrets securely.

6. **Q:** What is a multi-tier architecture in AWS?  
   **A:** Separation of presentation, application, and database layers, often deployed in separate subnets with security controls.

7. **Q:** How would you migrate an on-prem application to AWS?  
   **A:** Assess dependencies, select migration strategy (rehost/replatform/refactor), migrate data, test, and optimize architecture.

8. **Q:** Explain how you would design a high-performance, low-latency solution.  
   **A:** Use caching (ElastiCache), CDN (CloudFront), database indexing, asynchronous processing, and proximity-based resources.

9. **Q:** How do you handle AWS service limits in production?  
   **A:** Monitor using CloudWatch, request limit increases, and implement decoupled architecture with retries and error handling.

10. **Q:** How do you ensure compliance and governance in AWS?  
    **A:** Apply IAM policies, encrypt data at rest/in transit, enable CloudTrail, use Config rules, and audit with AWS Artifact and Security Hub.

---

> 💡 **Tip:** Practice answers with examples from real projects or labs. This demonstrates practical knowledge, not just memorization.

