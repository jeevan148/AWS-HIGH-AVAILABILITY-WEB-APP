# AWS-HIGH-AVAILABILITY-WEB-APP
Highly Available Web Application using AWS EC2, IAM,VPC,ALB and S3

Highly Available Web Application using AWS
Project Overview

This project demonstrates the deployment of a Highly Available Web Application using AWS cloud services.

AWS Services Used
Amazon EC2 – Web Server Hosting
Application Load Balancer (ALB) – Distributes incoming traffic
Amazon S3 – Stores static files like index.html
VPC - creates multiple subnets in multiple AZ
Nginx – Web Server
Architecture
Two EC2 instances are deployed.
Nginx is installed on both EC2 instances.
Application Load Balancer distributes incoming traffic.
S3 stores static website assets.
Health checks monitor EC2 instance availability.
Project Implementation
Created an S3 bucket.
Uploaded index.html files to S3.
Launched two EC2 instances.
Installed and configured Nginx.
Deployed HTML pages on both EC2 instances.
Created an Application Load Balancer.
Registered both EC2 instances in the Target Group.
Tested Load Balancing and High Availability.
Testing
Verified website access through ALB DNS.
Tested both EC2 instances.
Stopped one EC2 instance and verified that the website remained accessible through the other healthy instance.
Result

Successfully deployed a Highly Available Web Application using AWS EC2, ALB, S3 and Nginx.
