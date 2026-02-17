# AWS EC2 Nginx Deployment Project

## Overview
Deployed a Linux EC2 instance on AWS and configured an Nginx web server.

## Steps Performed

1. Launched EC2 instance (Amazon Linux, t2.micro)
2. Configured Security Group:
   - SSH (Port 22)
   - HTTP (Port 80)
3. Connected using SSH (.pem key)
4. Updated server packages
5. Installed Nginx web server
6. Started Nginx service
7. Verified deployment using public IP

## Commands Used

sudo yum update -y
sudo yum install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx

## Result
Successfully hosted default Nginx page on AWS EC2 public IP.

## Learnings
- EC2 instance setup
- SSH access using key pair
- Security group configuration
- Linux package installation
- Basic web server deployment

