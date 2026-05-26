# ICT171 Cloud Server Project

## Student Details

**Name:** Hamdhan Ahmed  
**Student ID:** 35441645  
**GitHub Repository:** https://github.com/Hamdhan833/ICT171-Cloud-Server-Project  
**Website:** https://hamdhan.it.com/  
**Public IP Address:** 20.70.146.143  

## Project Overview

This project documents the design and deployment of a personal portfolio website hosted on a Microsoft Azure Virtual Machine using Ubuntu Linux and the Nginx web server. The website presents my academic background, technical skills, and personal profile as a Bachelor of Information Technology student.

The project demonstrates cloud server deployment, Linux server administration, web server configuration, DNS setup, HTTPS configuration, and basic scripting.

## Azure Virtual Machine Deployment

The cloud server for this project was deployed using Microsoft Azure Infrastructure as a Service (IaaS). An Ubuntu Linux Virtual Machine was created and configured to host the portfolio website.

### Azure Configuration

- Cloud Platform: Microsoft Azure
- Virtual Machine Type: Ubuntu Linux VM
- Public IP Address: 20.70.146.143
- Domain Name: https://hamdhan.it.com/
- Remote Access Method: SSH
- Web Server: Nginx

### SSH Access

The following command was used to remotely connect to the Azure virtual machine:

```bash
ssh azureuser@20.70.146.143
```

### Updating Ubuntu Packages

The following commands were used to update the Ubuntu server:

```bash
sudo apt update
sudo apt upgrade -y
```

### Installing Nginx

Nginx was installed to host the portfolio website:

```bash
sudo apt install nginx
```

### Checking Nginx Status

```bash
sudo systemctl status nginx
```

### Editing Website Files

The website files were stored inside the `/var/www/html/` directory.

```bash
cd /var/www/html
sudo nano index.html
```
