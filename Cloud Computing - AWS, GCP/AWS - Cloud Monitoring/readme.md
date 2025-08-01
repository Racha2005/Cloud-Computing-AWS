# ☁️ Cloud Monitoring and Alerting with AWS

This project demonstrates how to launch an EC2 instance, host a webpage, monitor the instance using AWS CloudWatch, and receive alerts via Amazon SNS when CPU usage crosses a defined threshold.

---

## 🔧 Tools and Services Used

- **Amazon EC2**
- **Amazon CloudWatch**
- **Amazon SNS (Simple Notification Service)**
- **Microsoft Clipchamp** (for video recording)
- **GitHub** (for version control and documentation)

---

## 📌 Overview

- Launched an EC2 instance in the **Mumbai region**.
- Created a security group to allow:
  - SSH access (port 22)
  - HTTP traffic (port 80)
- Deployed a simple custom HTML webpage with:
  > 🌤️ *Hello from the Cloud! Monitoring in progress!!*
- ✅ Live Site: [http://65.0.178.223](http://65.0.178.223)
- Styling includes:
  - Background image from [Wallpaperflare](https://c1.wallpaperflare.com/preview/105/785/174/sky-cloud-plane-background.jpg)
  - A square image overlaid using:
    [Google Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTczHg6yof3m1jH2XBhh4wFXymRiNk09xIzq__hyc8QSygnhmMy1vRbiP0_d-Ky4xa4HQE&usqp=CAU)

---

## 🖥️ EC2 Monitoring with CloudWatch

- Enabled **EC2 CPU Utilization monitoring**.
- Accessed metrics from:

→ CloudWatch → Metrics → EC2 → Per-Instance Metrics

 ✅ Created a visual dashboard to observe usage trends.

📊 **CloudWatch Dashboard:**  
[cloud-monitor-dashboard] - (https://ap-south-1.console.aws.amazon.com/cloudwatch/home?region=ap-south-1#dashboards/dashboard/cloud-monitor-dashboard)

---

## 🚨 Alarm & Notification Setup

- **Alarm Name:** `High Alert-Alarm`
- **Threshold:** CPU Utilization > 70%
- **Duration:** 2 consecutive evaluation periods
- **Notification via SNS Topic:** `cpu-alert-topic`
- **Email Endpoint:** `rachanathunga20@gmail.com`
- *(Confirmation required via email before it becomes active)*

📬 **Sample Notification Description:**
> "High Alert: Your EC2 instance is experiencing high CPU usage. Please investigate immediately."

---
