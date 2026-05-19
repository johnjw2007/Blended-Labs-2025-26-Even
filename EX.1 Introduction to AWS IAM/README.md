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
<img width="1261" height="573" alt="image" src="https://github.com/user-attachments/assets/6a085468-3db8-453e-9a27-74b9de21c0ff" />
<img width="1257" height="587" alt="image" src="https://github.com/user-attachments/assets/f00908bd-ab50-4b90-b8f5-4f190aabab59" />

### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1255" height="588" alt="image" src="https://github.com/user-attachments/assets/80403f0b-da53-410c-9a22-106fcd59eeee" />
<img width="1240" height="547" alt="image" src="https://github.com/user-attachments/assets/72da1cf2-3977-4c27-96d7-09430371f1f7" />
<img width="1247" height="572" alt="image" src="https://github.com/user-attachments/assets/37fa39e0-33af-41c0-a1bd-9c1cd9823e04" />

### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1258" height="572" alt="image" src="https://github.com/user-attachments/assets/baa19ef7-08d7-4d8a-b7d1-527dfa5597a8" />
<img width="1257" height="572" alt="image" src="https://github.com/user-attachments/assets/81f1dc8e-464d-4e6a-8080-477f38958b89" />
<img width="1256" height="582" alt="image" src="https://github.com/user-attachments/assets/f01a6aac-12fc-4c4f-84f1-0d74eb7c3567" />

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
**Name:** John Wilfred Thomas J W 212224040141
**Course:** Introduction to Cloud Computing  

