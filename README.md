# 🌍 Travel Memory App — Full Stack Deployment (MERN + DevOps)

# Please refer this:  [Mern_Apllication_Deployent-on-AWS_Assignment.docx](https://github.com/JIilan-PPMCAD/TravelMemory_MERN-App_Deployement/blob/main/Mern_Apllication_Deployent-on-AWS_Assignment.docx)   for assignment

## 🚀 Project Overview

The Travel Memory application has been developed using the MERN stack. Your challenge is to deploy this application on an Amazon EC2 instance. This will provide you with hands-on experience in deploying full-stack applications, working with cloud platforms, and ensuring scalable architecture.
This project demonstrates **end-to-end deployment of a production-grade application** using modern DevOps practices on AWS.

---

## 🧠 Tech Stack

### 🔹 Frontend

* React.js
* Axios
* CSS

### 🔹 Backend

* Node.js
* Express.js
* MongoDB (Atlas)
* Mongoose

### 🔹 DevOps & Infrastructure

* AWS EC2 (Compute)
* AWS Application Load Balancer (ALB)
* Nginx (Reverse Proxy + Static Hosting)
* PM2 (Process Manager)
* Cloudflare (DNS, CDN, SSL)

---

## 🏗️ Architecture

<img width="1408" height="768" alt="Image" src="https://github.com/user-attachments/assets/2ed8ceca-99d2-4382-a8d8-33d5f8a6c181" />


---

## 🔁 Request–Response Flow

1. User sends request via browser
2. Request goes through Cloudflare (DNS + CDN + SSL)
3. Forwarded to AWS Load Balancer
4. Load Balancer distributes traffic to EC2 instances
5. Nginx:

   * Serves React frontend
   * Proxies API calls to backend
6. Node.js backend processes request
7. Data fetched from MongoDB Atlas
8. Response flows back to user via same path

---

## ⚙️ Features

* Add travel experiences
* View trip history
* Store trip details (dates, cost, places, notes)
* Responsive UI
* Backend API with MongoDB integration
* Scalable deployment with load balancing


## 🌐 Live URL

```
https://www.jilan-ppmcad.online/ 
```

## 📦 Key DevOps Concepts Demonstrated

* Infrastructure setup on AWS
* Reverse proxy using Nginx
* Load balancing with ALB
* Domain + DNS management
* SSL/TLS configuration
* Process management using PM2
* Production deployment of MERN stack

## 👤 Author

**Jilan**

---

## 💼 Project Summary

This project demonstrates the ability to:

* Deploy full-stack applications in production
* Design scalable cloud architecture
* Configure networking, DNS, and SSL
* Debug real-world infrastructure issues

---
