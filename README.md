# AWS VPC Peering Between Two EC2 Instances


---

## Project Overview

This project demonstrates communication between two Amazon EC2 instances located in different VPCs using AWS VPC Peering.

## AWS Services Used

- Amazon VPC
- Amazon EC2
- VPC Peering
- Route Tables
- Security Groups
- Internet Gateway

## Steps Performed

1. Created two VPCs with different CIDR blocks.
2. Created subnets in each VPC.
3. Launched Ubuntu EC2 instances.
4. Created and accepted a VPC Peering Connection.
5. Updated Route Tables.
6. Configured Security Groups to allow ICMP.
7. Verified connectivity using the `ping` command.

## Result

The EC2 instances successfully communicated over their private IP addresses through the VPC Peering Connection with 0% packet loss.

## Skills Demonstrated

- AWS Cloud
- Amazon EC2
- Amazon VPC
- VPC Peering
- Route Tables
- Security Groups
- Linux
- Networking

## Screenshots
<img width="860" height="208" alt="image" src="https://github.com/user-attachments/assets/bc1cc260-f8f1-489b-a877-dc3b4b539444" />
<img width="848" height="178" alt="image" src="https://github.com/user-attachments/assets/8eee6a49-8ec3-4d54-9168-8b5dd598430d" />
<img width="873" height="206" alt="image" src="https://github.com/user-attachments/assets/42fff764-fe09-4a31-99ed-e215bfb8ae4e" />
<img width="810" height="425" alt="image" src="https://github.com/user-attachments/assets/f2ed00ee-a7d0-4ae3-bfa6-9e7a7012d62e" />






