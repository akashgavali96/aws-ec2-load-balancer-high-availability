# aws-ec2-load-balancer-high-availability

🚀 AWS EC2 Load Balancer - High Availability Architecture

📌 Project Overview

This project demonstrates how to design and deploy a highly available web application architecture on AWS. It uses multiple EC2 instances behind an Application Load Balancer (ALB) to ensure fault tolerance and efficient traffic distribution.

---

🛠️ Technologies Used

* AWS EC2
* Application Load Balancer (ALB)
* Target Groups
* Amazon Linux
* Apache (httpd) Web Server
* HTML

---

⚙️ What This Project Does

* Launches two EC2 instances in AWS
* Installs and configures Apache web server on both instances
* Deploys custom HTML webpages on each server
* Creates an Application Load Balancer (ALB)
* Configures a Target Group with health checks
* Distributes incoming traffic between multiple servers
* Ensures high availability and fault tolerance

---

🌐 Architecture

User → Application Load Balancer → Target Group → EC2 Instances

---

🚀 How It Works

1. User accesses the Load Balancer DNS URL
2. Request is received by the Application Load Balancer
3. Load Balancer forwards traffic to the Target Group
4. Target Group routes requests to healthy EC2 instances
5. Apache web server responds with the hosted webpage

---

📷 Output

* Refreshing the Load Balancer URL shows responses from:

  * Server 1
  * Server 2
* Demonstrates traffic distribution across instances

---

🎯 Key Learnings

* Load Balancer fundamentals (ALB)
* High Availability architecture design
* Target Groups and Health Checks
* Traffic distribution across multiple servers
* AWS networking and security concepts

---

🔐 Security Considerations

* Configured Security Groups to allow HTTP (port 80) access
* Restricted EC2 access to only Load Balancer traffic
* Implemented best practices for secure architecture

---

🚀 Future Improvements

* Add Auto Scaling Group for dynamic scaling
* Configure HTTPS using SSL/TLS
* Use Route 53 for domain mapping
* Deploy infrastructure using Terraform

---
