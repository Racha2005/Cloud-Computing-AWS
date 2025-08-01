# 🌐 Multi-Cloud Architecture using AWS & GCP

This project demonstrates a basic multi-cloud setup where a web server hosted on AWS EC2 links to another web server hosted on GCP Compute Engine, and vice versa. The goal is to simulate cross-cloud communication between different platforms.

---

## 🔧 Tools & Services Used

AWS EC2 (Amazon Web Services)

GCP Compute Engine (Google Cloud Platform)

Apache2 Web Server

Linux (Amazon Linux 2 & Ubuntu)

HTML + CSS Styling

SSH Access

---

## 🚀 Instance Details

**✅ AWS EC2 Instance**
Key Pair: keypair-333.pem

Public IP: 13.127.202.236

Background Image:
https://wallpapers.com/images/hd/solid-light-purple-1517-x-853-rsorkyq9fivrbpam.jpg

Heading: AWS Web Server - Multi-Cloud Architecture

Link: Visit GCP Server

---

**✅ GCP Compute Engine Instance**
Public IP: 34.47.147.194

Background Image:
https://media.istockphoto.com/id/1308016132/vector/a-horizontal-empty-bright-radiant-fluorescent-neon-green-coloured-backgrounds.jpg

Heading: GCP Web Server - Multi-Cloud Architecture

Link: Visit AWS Server

---

## 🔁 Cross-Linking Architecture
AWS page links to GCP server:
🔗 http://34.47.147.194

GCP page links to AWS server:
🔗 http://13.127.202.236

This setup simulates real-world multi-cloud architecture and helps visualize how different platforms can interconnect.

---

## 📚 Key Takeaways
Provisioning EC2 and GCP VM instances

Apache web server setup on both platforms

Handling firewall, SSH access, and security groups

Cross-linking web pages between cloud providers

Using styled HTML with custom background images

---

## 🔗 Live Demo Links
🌐 AWS Web Server

🌐 GCP Web Server

---

## ⚙️ Setup Instructions
🔸 Step 1: Update & Install Apache (on both AWS and GCP VMs)
sudo apt update
sudo apt install apache2 -y
🔸 Step 2: Add index.html content
sudo nano /var/www/html/index.html

Paste the respective HTML code (see below for AWS and GCP versions)

🔸 Step 3: Restart Apache Server
sudo systemctl restart apache2

🔸 Step 4: Open your public IP in the browser
AWS: http://13.127.202.236

GCP: http://34.47.147.194

✨ Tip:
You can put these inside a collapsible section using Markdown like this:

<details> <summary>📋 Setup Commands (Click to Expand)</summary>

sudo apt update
sudo apt install apache2 -y
sudo nano /var/www/html/index.html
sudo systemctl restart apache2
</details>

---
