# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : nikkil varshan 
Reg no :212225040280 
Date :27/11/2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.

---

## Output Screenshots 
---
<img width="952" height="907" alt="Screenshot 2026-11-25 102216" src="https://github.com/user-attachments/assets/0307fe0e-6a80-41f8-8beb-36dcb20498b1" />
<img width="940" height="465" alt="Screenshot 2026-11-27 084825" src="https://github.com/user-attachments/assets/3ce4a192-6c08-43cc-87e3-e1c55573e981" />
<img width="942" height="592" alt="Screenshot 2026-11-27 085231" src="https://github.com/user-attachments/assets/8f58ac0c-98bc-4d6d-9649-1c5329e20a16" />
<img width="945" height="487" alt="Screenshot 2026-11-27 085612" src="https://github.com/user-attachments/assets/e8fc9326-acda-4f16-8453-1e313fa1ebbc" />
<img width="940" height="725" alt="Screenshot 2026-11-27 090413" src="https://github.com/user-attachments/assets/a016e45d-22da-48ab-b357-ce92415051fd" />
<img width="738" height="612" alt="Screenshot 2026-11-27 091433" src="https://github.com/user-attachments/assets/7f3ab2e7-a058-4d08-8489-e0be84c5d7ad" />
<img width="1173" height="977" alt="Screenshot 2026-11-27 091957" src="https://github.com/user-attachments/assets/0cc28212-0958-4ddb-9fef-3938b74fd2c8" />
<img width="887" height="791" alt="Screenshot 2026-11-27 092148" src="https://github.com/user-attachments/assets/958cead3-27f4-4d73-90c2-cbb2c7f5b738" />







---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
