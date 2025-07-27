# Windows-Server-EC2-Instance-Setup-on-AWS

This repository documents my Week 3 task for the CSN Bootcamp, where I launched and secured a Windows Server EC2 instance on Amazon Web Services (AWS).

## What I Did
- Launched a new EC2 instance using **Amazon Windows Server 2019 Base AMI**
- Deployed the instance in a **public subnet**
- Configured a **security group** to allow **RDP access (port 3389)** from **only my public IP**
- Assigned a **Name tag**: `CSN-BootCamp-Week3`

## Security Best Practice
Restricted RDP access to a specific IP address to enhance security and prevent unauthorized access.

## Screenshots

![EC2 Launch](Screenshots/EC2%20Instance%20Launch.JPG)

![RDP Connection](Screenshots/remote%20desktop%20connection.png)

