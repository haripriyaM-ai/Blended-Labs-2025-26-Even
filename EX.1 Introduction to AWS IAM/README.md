# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**

<img width="600" height="300" alt="Screenshot 2026-08-03 165524" src="https://github.com/user-attachments/assets/8eeef7ef-adea-41a4-8fb4-cc29088008cf" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="600" height="300" alt="Screenshot 2026-08-03 164152" src="https://github.com/user-attachments/assets/77664704-026e-4660-9ee4-618411282808" />
<br><br>
<img width="600" height="300" alt="Screenshot 2026-08-03 164212" src="https://github.com/user-attachments/assets/f6317ddb-373b-4d57-82c9-30732d9d0414" />
<br><br>
<img width="600" height="300" alt="Screenshot 2026-08-03 164245" src="https://github.com/user-attachments/assets/8bbaf047-0011-49d4-b396-4fb5d33ab2b2" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**
### user-1 
<img width="600" height="300" alt="Screenshot 2026-08-03 164611" src="https://github.com/user-attachments/assets/ab524316-25e6-4c7e-979d-1c815b0260a3" />
<br><br>

### user-2

<img width="600" height="300" alt="Screenshot 2026-08-03 165128" src="https://github.com/user-attachments/assets/335c946b-2095-4b86-8196-b738e67add03" />
<br><br>

### user-3 
<img width="600" height="300" alt="Screenshot 2026-08-03 165413" src="https://github.com/user-attachments/assets/375dcf9a-1e3e-44fe-9db0-f184d0210deb" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** HARI PRIYA M\
**Reg no:** 212224240047\
**Course:** Introduction to Cloud Computing  

