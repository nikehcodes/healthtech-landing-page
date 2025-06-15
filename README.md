# 🏥 HealthTech Innovations

## 🚀 Project Overview

**HealthTech Innovations** is a dynamic cloud-deployed landing page showcasing how technology can transform the future of healthcare. This project serves as a technical prototype to demonstrate both frontend and cloud engineering capabilities to potential investors and collaborators.

---

## 👤 Author

**Nikeh Codes**  
Cloud Engineer | Registered Nurse  
AltSchool ID: ALT/SOE/024/2406

---

## 💡 Project Title

**The Future of HealthTech Innovations**

---

## ✨ Short Pitch

We envision a future where technology revolutionizes access to quality healthcare. Through AI integration and smart systems, HealthTech Innovations bridges the gap between patients and providers, enabling faster diagnosis, streamlined workflows, and better outcomes. Our solution is designed by healthcare professionals for real-world transformation.

---

## 📜 Features

- Responsive landing page built with **HTML** and enhanced with **Tailwind CSS**
- Deployed on **DigitalOcean** with **Ubuntu**
- **Nginx** web server configuration
- Secured with **Let's Encrypt SSL (HTTPS)**
- Custom domain setup with **DuckDNS**
- Includes interactive design, animations, and professional branding
- GitHub version control and documentation

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS  
- **Cloud Provider**: DigitalOcean  
- **OS**: Ubuntu 22.04  
- **Web Server**: Nginx  
- **SSL**: Let's Encrypt with Certbot  
- **Version Control**: Git & GitHub  

---

## 🌐 Public Access

- **Domain**: [https://healthtech.duckdns.org](https://healthtech.duckdns.org)  
- **IP Address**: `165.232.109.97`  

---

## 🧱 Project Structure

healthtech-landing-page/
├── index.html # Main landing page
├── README.md # Project documentation
├── assets/ # Images & media files
│ └── screenshot.png 



---

## 📸 Screenshot

![Landing Page](./assets/screenshot.png)

---

## 📦 Server Deployment Steps

### 1. Provisioning the Server
- Created a Droplet on DigitalOcean using Ubuntu 22.04

### 2. Web Server Setup
- Installed and tested **Nginx**:
  ```bash
  sudo apt update
  sudo apt install nginx
  sudo systemctl start nginx


3. Domain Setup
Created a free domain using DuckDNS

Set up A record pointing to the server IP

4. SSL Setup
Installed Certbot:

bash
Copy code

sudo apt install certbot python3-certbot-nginx
Configured HTTPS:

bash
Copy code
sudo certbot --nginx -d healthtech.duckdns.org
5. Project Deployment
Placed index.html and image files in /var/www/html/

Restarted Nginx:

```bash

sudo systemctl restart nginx

Initialized Git in project folder:

bash
Copy code
git init
git remote add origin https://github.com/nikehcodes/healthtech-landing-page.git
git add .
git commit -m "Deployed landing page with hospital and tech theme"
git push -u origin main

🔗 Submission Details
GitHub Repository: https://github.com/nikehcodes/healthtech-landing-page

Live Demo: https://healthtech.duckdns.org

AltSchool ID: ALT/SOE/024/2406

