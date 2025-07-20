AWS 3‑Tier Architecture Web Application 

This repository contains an implementation of a 3‑tier web application on Amazon Web Services (AWS)

Architecture Flowchart

<img width="1920" height="1080" alt="3TierArch" src="https://github.com/user-attachments/assets/de7d3986-fc84-49c3-b047-c96bfcfd810e" />



Key Features

Auto Scaling Groups for Web and App tiers

Internal and External Load Balancer for Traffic Distribution

AWS S3 for code deployment and static assets hosting

Security Groups configured for least privilege



Tech Stack

Frontend: React (built into static HTML/CSS/JS) served via NGINX

Backend: Node.js 

Database: Amazon RDS MySQL

Infrastructure: AWS EC2, S3, RDS, ELB, Auto Scaling Groups, Security Group


Architecture Overview

1)VPC:
<img width="1920" height="1080" alt="vpc" src="https://github.com/user-attachments/assets/2a47eba2-0f73-4490-8f8a-10dd84ce6340" />


2)EC2 Instance:
  <img width="1920" height="1080" alt="EC2" src="https://github.com/user-attachments/assets/02b40e73-2f14-4848-97c7-c8d3687f65d0" />

3)Security Group:
<img width="1920" height="1080" alt="Security group" src="https://github.com/user-attachments/assets/c41b354d-0014-4c42-8c69-c7eb58133f02" />

4)Target Group and Load Balancer:
<img width="1920" height="1080" alt="load balancer" src="https://github.com/user-attachments/assets/47cb602b-2fa2-49ed-8a3f-ec6e19fa7310" />
<img width="1920" height="1080" alt="target grp" src="https://github.com/user-attachments/assets/b80294e5-a327-4b89-acaa-a27fc629b79c" />

5)S3:
<img width="1920" height="1080" alt="s3" src="https://github.com/user-attachments/assets/4f0e6e38-9e8b-487e-8426-173e9e159656" />

6)Database:
<img width="1920" height="1080" alt="DB" src="https://github.com/user-attachments/assets/159dfaa7-f433-4ea4-b2c5-216528b198ef" />


7)ASG:
<img width="1920" height="1080" alt="asg" src="https://github.com/user-attachments/assets/cf941dbe-1077-4cc9-9616-104174accf5a" />

7)Internet Gateway and NAT Gateway:
<img width="1920" height="1080" alt="internet getway" src="https://github.com/user-attachments/assets/4c43ccd0-1819-4c09-994b-d7590ec8192c" />
<img width="1920" height="1080" alt="nat gateway" src="https://github.com/user-attachments/assets/2d990636-bad2-4253-800a-d9ea3669066e" />

8)CloudWatch for Load Balancer AND Database:
<img width="1920" height="1080" alt="lb CW" src="https://github.com/user-attachments/assets/680785be-ffad-48ae-bda4-0136720609e9" />
<img width="1920" height="1080" alt="cloud watch" src="https://github.com/user-attachments/assets/b4b160ce-ffea-414c-8fa6-96f8b1402405" />





