# AWS 3-Tier Web Application

🚀 *Live Demo:* [Open Live Application](http://app-external-alb-1871298044.ap-south-1.elb.amazonaws.com)

A production-style 3-Tier Web Application deployed on AWS using React, Node.js, MySQL, EC2, Application Load Balancers, Target Groups, and a custom VPC architecture.# AWS 3-Tier Web Application

A production-style 3-Tier Web Application deployed on AWS using React, Node.js, MySQL, EC2, Application Load Balancers, Target Groups, and a custom VPC architecture.

## 🏗️ Architecture

The application follows a 3-Tier architecture:

- 🌐 Web Tier – React frontend running on EC2 instances
- ⚙️ App Tier – Node.js backend running on EC2 instances
- 🗄️ Database Tier – MySQL database
- ⚖️ Application Load Balancers – Traffic distribution between tiers
- 🔐 AWS VPC – Public and private subnet-based network architecture

## 🚀 Technologies Used

- AWS VPC
- EC2
- Application Load Balancer (ALB)
- Target Groups
- MySQL
- Node.js
- React.js
- Nginx
- Linux
- AWS Systems Manager Session Manager

## ✨ Features

- 3-Tier AWS architecture
- React-based frontend
- Node.js backend API
- MySQL database integration
- Load balancing
- Health check endpoints
- Nginx reverse proxy
- Private application tier
- AWS-based deployment

## 📂 Project Structure

```text
AWS-3tier-WebApp/
│
├── app-tier/
│   ├── DbConfig.js
│   ├── index.js
│   ├── TransactionService.js
│   └── package.json
│
├── web-tier/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── nginx.conf
├── install.sh
├── error.txt
└── 3-Tier Architecture Application Steps.txt
