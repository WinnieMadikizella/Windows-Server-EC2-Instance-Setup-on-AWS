# Windows-Server-EC2-Instance-Setup-on-AWS

This repository documents my Week 3 task for the CSN Bootcamp, where I launched and secured a Windows Server EC2 instance on Amazon Web Services (AWS).

## What I Did
- Launched a new EC2 instance using **Amazon Windows Server 2019 Base AMI**
- Deployed the instance in a **public subnet**
- Configured a **security group** to allow **RDP access (port 3389)** from **only my public IP**
- Assigned a **Name tag**: `CSN-BootCamp-Week3`
- Successfully connected to the instance via **Remote Desktop Protocol (RDP)**

## Security Best Practice
To ensure secure access:
- RDP access (port 3389) was restricted to **only my personal public IP**
- No open ports were exposed to the general internet
- The instance was kept minimal using a **t2.micro** size for testing purposes

## Screenshots
### EC2 Instance Launch (AWS Console)
This shows the instance running, tagged correctly, with RDP rules limited to a specific IP.
![EC2 Launch](Screenshots/EC2%20Instance%20Launch.JPG)

### Remote Desktop Connection (Windows Server Instance)
Successful login and basic specs shown after RDP connection.
![RDP Connection](Screenshots/remote%20desktop%20connection.png)

## Why This Matters for Data Professionals
As a Data & Business Intelligence Specialist, this task bridges an important gap:
> Knowing how to analyze data is powerful, but knowing how to deploy, host, and secure the infrastructure that supports data workflows is a true force multiplier.

This foundational cloud skill supports:
- Hosting automated data pipelines or scheduled tasks
- Running reporting tools like Power BI Gateway in a cloud-hosted environment
- Understanding how cloud resources integrate with storage, databases, and analytics platforms
- Practicing DevOps thinking as part of analytics delivery

🔗 *Let’s connect on [LinkedIn](https://linkedin.com/in/https://www.linkedin.com/in/winnie-madikizella-data/)*
