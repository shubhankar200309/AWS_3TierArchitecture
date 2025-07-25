# 🌐 AWS 3‑Tier Architecture Web Application

This repository showcases the implementation of a highly available and scalable 3‑Tier Web Application architecture on Amazon Web Services (AWS).

---

## 📊 Architecture Diagram:

![Untitled video - Made with Clipchamp](https://github.com/user-attachments/assets/3d404197-99f3-4c42-89a8-3033847a5c90)

---

## 🚀 Key Features:
- Auto Scaling Groups for both Web and App tiers
- Internal and External Load Balancers for efficient traffic distribution
- Amazon S3 for code deployment and static content hosting
- Security Groups configured following the principle of least privilege

---

## 🛠 Tech Stack:
- Layer: Technology
- Frontend: React (compiled to static HTML/CSS/JS), served via NGINX
- Backend: Node.js
- Database: Amazon RDS (MySQL)
- Infrastructure: AWS EC2, S3, RDS, ELB, Auto Scaling Groups, Security Groups

--- 

## 🧩 Component-wise Architecture Breakdown

- 1️⃣ **VPC (Virtual Private Cloud)**:
<img width="1920" height="1080" alt="vpc" src="https://github.com/user-attachments/assets/59d8ed74-332d-4cfd-96da-e48ce3bc8ee1" />

---

- 2️⃣ **EC2 Instances**: Provisioned to host frontend (NGINX) and backend (Node.js) servers.
<img width="1920" height="1080" alt="EC2" src="https://github.com/user-attachments/assets/c8ec7609-7350-42ea-a80c-2a2a1365f9fc" />

---

- 3️⃣ **Security Groups**: Custom security group rules configured for web, app, and DB layers.
<img width="1920" height="1080" alt="Security group" src="https://github.com/user-attachments/assets/ddb2dcdc-02e5-419b-8e73-3db414789514" />

---

- 4️⃣ Load Balancers & Target Groups:
   - External Load Balancer for handling client traffic
   - Internal Load Balancer for routing traffic to the app tier
   - Target Groups for managing registered EC2 instances

<img width="1920" height="1080" alt="load balancer" src="https://github.com/user-attachments/assets/21eb478b-fa76-4c69-8621-fbd992c872a5" />
<img width="1920" height="1080" alt="target grp" src="https://github.com/user-attachments/assets/3a193317-ce64-44ce-9920-bf392802064f" />

---

- 5️⃣ **Amazon S3**: Code deployment and versioning
<img width="1920" height="1080" alt="s3" src="https://github.com/user-attachments/assets/1b45e3e9-bb86-4940-aa94-ac5689afbc97" />

---

- 6️⃣ **Amazon RDS (MySQL)**: Managed relational database used for application data storage.
<img width="1920" height="1080" alt="DB" src="https://github.com/user-attachments/assets/8dc4a627-f6a3-457d-9c77-dd52258802fc" />

---

- 7️⃣ **Auto Scaling Groups (ASG)**: Automatically scale EC2 instances based on demand to ensure high availability.
<img width="1920" height="1080" alt="asg" src="https://github.com/user-attachments/assets/6dd4da76-e942-49dc-966a-35580001e408" />

---

- 8️⃣ **Internet Gateway & NAT Gateway**:
   - Internet Gateway: Enables internet access for public subnets
   - NAT Gateway: Provides internet access to private instances without exposing them publicly
<img width="1920" height="1080" alt="internet getway" src="https://github.com/user-attachments/assets/91109c1c-550d-4e49-bb86-41ccc974a7af" />
<img width="1920" height="1080" alt="nat gateway" src="https://github.com/user-attachments/assets/589d7a55-2a7f-485c-ab23-6624aa27aef3" />

---

- 9️⃣ **Amazon CloudWatch Monitoring**: Real-time monitoring of Load Balancer and Database performance
<img width="1920" height="1080" alt="lb CW" src="https://github.com/user-attachments/assets/68ac3d56-ea4a-475e-8bac-5861efc1931a" />
<img width="1920" height="1080" alt="cloud watch" src="https://github.com/user-attachments/assets/b98686b0-ecae-4c32-8f22-1aacc8a25455" />


---

<p align="center">
Made with by Shubhankar Gupta   <a href="mailto:shubhankargupta200309@gmail.com">
    <img src="https://img.shields.io/badge/Email-ff3625" alt="Email">
</p>

---
