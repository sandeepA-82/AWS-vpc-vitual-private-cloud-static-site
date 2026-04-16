# AWS-vpc-vitual-private-cloud-static-site
It is a mini project to host a web site in the cloud servers and providing the security to the webpage by using VPC (Virtual private cloud) service which is provided by AWS(amazon web services).

 AWS VPC Static Website Hosting 

Project Overview
This project demonstrates hosting a static website on AWS using a secure VPC architecture.  
The website is served using Python's built-in HTTP server.

 Architecture Components:-

- VPC (Virtual Private Cloud)
- Public and Private Subnets
- Internet Gateway (IGW)
- NAT Gateway
- EC2 Instance (Private Subnet)
- Security Groups
- Application Load Balancer  (ELB)

Architecture Flow:-

User → Load Balancer → EC2 (Private Subnet) → Python HTTP Server

 Security Design:-

- EC2 instance (Virtual servers) is placed in a **private subnet**
- No direct public access to EC2
- All incoming traffic goes through Load Balancer (knows as elastic load balencer)
- NAT Gateway enables outbound internet access


How to Run Locally:-

1. Navigate to website folder:

    OR

Basically we turn ON  the EC2 servers, and  we will access the site using the "public IP adderss" EC2 instance and use "http:public_IP:port_number".


