# 🌍 Travel Memory App — Full Stack Deployment (MERN + DevOps)

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

---

## 🖥️ Local Setup

### 1. Clone Repository

```bash
git clone https://github.com/JIilan-PPMCAD/<your-username>/Travel-Memory_MERN_APP_Deployement_.git
cd Travel-Memory_MERN_APP_Deployement
```

---

### 2. Backend Setup

```bash
cd backend
npm install
```

Create `.env`:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
```

Run backend:

```bash
npm start
```
<img width="866" height="143" alt="image" src="https://github.com/user-attachments/assets/de215d99-10f8-4b44-984b-e85d76c39199" />

---

### 3. Frontend Setup

```bash
cd ../frontend
npm install
npm start


## ☁️ Deployment Steps (Summary)

### 🔹 Backend Deployment

* Hosted on EC2
* Managed using PM2
* Connected to MongoDB Atlas
`````
<img width="860" height="232" alt="image" src="https://github.com/user-attachments/assets/e9558afb-6de4-46b6-90f0-09e922d6522b" />
````

### 🔹 Frontend Deployment

* Built using `npm run build`
* Served via Nginx

### 🔹 Reverse Proxy
```
<img width="1346" height="457" alt="ngnix" src="https://github.com/user-attachments/assets/7e00d0f4-f7ba-4a72-99bf-e2562677217a" />

### 🔹 Load Balancing

* AWS Application Load Balancer
* Multiple EC2 instances for scalability
  <img width="1886" height="500" alt="image" src="https://github.com/user-attachments/assets/741f31f4-b2bd-403b-ab0b-e0201e0be723" />


#### Testing Load Balancer.
  *Stoped an EC2 instance
  <img width="1642" height="407" alt="image" src="https://github.com/user-attachments/assets/650c476d-5197-4b98-8945-f98c39146633" />

 * Browse the DNS of Load Balancer, The site should load fine.
   <img width="1587" height="835" alt="LB_working" src="https://github.com/user-attachments/assets/deff7838-60ea-4f4a-82c6-0c80857496cc" />

  

### 🔹 Domain & SSL

* Domain configured via Cloudflare
<img width="1823" height="872" alt="webapp_site" src="https://github.com/user-attachments/assets/b60a8b95-5c6f-42ad-9748-0420bf114608" />

  
* SSL enabled using:

  * Cloudflare (edge)
  * AWS ACM (origin)
<img width="1820" height="840" alt="webapp_with_https" src="https://github.com/user-attachments/assets/691c14fc-121b-4d66-b39a-0292d931f554" />


---

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
