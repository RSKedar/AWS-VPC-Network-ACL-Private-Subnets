# AWS-VPC-Network-ACL-Private-Subnets

📌 Project Explanation – AWS VPC Network ACL for Private Subnets

This project demonstrates how to configure a Network ACL (NACL) to control inbound and outbound traffic for private subnets inside a VPC using Amazon Web Services.

The main objective of this project is to understand how subnet-level security works in AWS and how Network ACL differs from Security Groups.


🛠 Tools & Services Used

Amazon VPC

Network ACL (NACL)

Private Subnets

AWS Management Console

⚙️ Environment Details

VPC CIDR: 10.0.0.0/16

Region: us-east-1

Network ACL Name: private-nacl

Private Subnets:

10.0.101.0/24 (us-east-1a)

10.0.102.0/24 (us-east-1b)

🧱 Architecture

Created a custom VPC

Created two private subnets in different Availability Zones

Created a Network ACL

Configured inbound and outbound rules

Associated the NACL with both private subnets

🔄 Implementation Steps

Created a custom VPC

Created private subnets

Created a Network ACL inside the VPC

Added inbound and outbound rules

Associated the NACL with private subnets














