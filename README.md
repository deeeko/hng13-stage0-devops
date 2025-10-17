# HNG13 DevOps Stage 0

## 👤 Name
Divine Akhigbe

## 💬 Slack Username
@DeeX

## 🌍 Project Description
This is my submission for HNG13 DevOps Stage 0.  
The task involves deploying a simple NGINX web server on AWS EC2 and serving a custom HTML webpage that displays my name and Slack username.

## 🚀 Server Details
- Server IP: http://13.51.150.241  
- Platform: Amazon Web Services (AWS) EC2  
- Deployed: 17/10/2025  

## 🧱 Tools Used
- AWS EC2 (Ubuntu 24.04 LTS)
- NGINX Web Server
- Nano Editor
- PuTTY for SSH access

## ⚙️ Setup Process
1. Launched an AWS EC2 Ubuntu instance  
2. Allowed inbound traffic on ports 22 (SSH) and 80 (HTTP)  
3. Installed NGINX using:
   ```bash
   sudo apt update && sudo apt install nginx -y
