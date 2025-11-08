# 🔐 Networking Project — Access Control Lists (ACL) Implementation

### 👤 Author: Ore-ofe Adeyemi Adesuyi  
**Budding Cybersecurity Analyst | 10Alytics Trainee**

---

## 📘 Project Overview
This project demonstrates how **Access Control Lists (ACLs)** can be used to strengthen network security by controlling departmental access to specific network resources.  

In this lab, I designed and configured a small office network that restricts **HTTP access** to a web server based on departmental needs allowing only **Admin** and **Sales** departments to connect, while **HR** remains restricted.  

This project highlights my growing understanding of **network segmentation**, **traffic control**, and **security policy enforcement** using router configurations.

---

## 🧩 Objectives
- Implement ACLs to secure internal network communication.  
- Grant HTTP access to specific departments (Admin and Sales).  
- Deny unauthorized access from the HR department.  
- Validate configurations through testing and documentation.

---

## 🧰 Tools & Technologies
| Category | Tools / Technologies |
|-----------|----------------------|
| **Simulation Software** | Cisco Packet Tracer |
| **Core Concepts** | Access Control Lists (ACLs), IP Addressing, Subnetting |
| **Devices Used** | Routers, Switches, PCs, and a Web Server |
| **Protocols** | HTTP, DNS, TCP/IP |

---

## 🗺️ Network Overview
The lab network includes three departments connected through a central router:

| Department | Network Address | Description |
|-------------|----------------|--------------|
| **Admin** | 192.168.10.0/24 | Hosts the company’s web and DNS servers |
| **Sales** | 192.168.20.0/24 | Permitted to access the web server |
| **HR** | 192.168.30.0/24 | Denied HTTP access for security control |

---

## ⚙️ Configuration Summary
ACLs were configured on the router to enforce the desired access rules.  
The ACL allowed HTTP traffic from **Admin** and **Sales** networks while denying requests from **HR**.  
Minimal router commands were used — focusing on clean, effective implementation rather than complexity.

---

## 🧪 Testing & Results
- **Admin & Sales:** Successfully accessed the company’s web server.  
- **HR:** Access was denied, confirming ACL enforcement.  
- Network performance and connectivity remained stable across departments.

---

## 🧠 Key Takeaways
- ACLs are powerful tools for **controlling access** and **protecting sensitive resources**.  
- Proper IP planning ensures security policies are implemented accurately.  
- This project enhanced my understanding of **practical network defense** and **router-based security configuration**.

---

## 📎 Project File
You can view the detailed configuration steps, screenshots, and explanations in the PowerPoint presentation below:  

📄 **https://docs.google.com/presentation/d/1FlY1AfZMh2QqHPbF4wNvx-bTsNhBmJDH/edit?usp=sharing&ouid=103131329338357540361&rtpof=true&sd=true**

---

> “In networking, even the smallest configuration choice can define how secure your system truly is.”

