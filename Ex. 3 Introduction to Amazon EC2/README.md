# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: HARI PRIYA M
* **Register Number**: 212224240047
* **Date of Submission**: 24-08-2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow

1. Launched an Amazon EC2 instance and configured the required instance settings.
2. Configured the VPC, subnet, security group, storage, termination protection, and User Data script.
3. Started the instance and verified that it reached **Running** state with **2/2 status checks passed**.
4. Monitored the instance using status checks, CloudWatch metrics, system logs, and instance screenshots.
5. Updated the security group for HTTP access, accessed the web server, resized the instance and EBS volume, and tested stop protection.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List
<img width="1917" height="990" alt="Screenshot 2026-08-24 113250" src="https://github.com/user-attachments/assets/853a79f5-2593-4b0b-85b4-6ae6af726d1c" />


---

### Screenshot 2: SSH Connection to Instance

<img width="1258" height="658" alt="556306083-c1a51b4b-40d2-4178-8f70-cb53ccb658fa" src="https://github.com/user-attachments/assets/555455e2-b0fb-49a1-acbb-6441b94fd211" />

---

### Screenshot 3: Instance Monitoring / Status
<img width="1917" height="991" alt="Screenshot 2026-08-24 112458" src="https://github.com/user-attachments/assets/c35240db-e8c2-414a-82c8-e821a0ed7c5c" />


---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
