# aws-ec2-nginx-deployment

## Overview
Deployed a Linux EC2 instance on AWS and configured Nginx web server.

## Steps:

1. Created EC2 instance (t2.micro)
2. Configured security group (HTTP, SSH)
3. Connected using SSH (.pem key)
4. Installed nginx:
   sudo yum update -y
   sudo yum install nginx -y
5. Started nginx:
   sudo systemctl start nginx
6. Accessed via public IP.

## Outcome:
Successfully hosted web server on AWS EC2.
