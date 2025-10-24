# 🧩 V-Profile Project Setup

## 📘 About the Project
The **V-Profile Project** is a **Multi-Tier Web Application Stack** that can be set up on a **Laptop or Desktop**.  
It serves as the **baseline for all AWS projects**, allowing developers to locally simulate a full cloud-like environment for research and development.

---

## 💡 Scenario
While working on large projects, teams often face these challenges:
- Making changes directly on real servers is risky.  
- Local setup is **complex, time-consuming, and non-repeatable**.

### 🧠 Problem Statement
Developers need a way to set up and test AWS-like environments **locally** without affecting real infrastructure.

### ✅ Solution
The **V-Profile Project** provides a **local setup of AWS** which is:
- **Automated**
- **Repeatable**
- **Infrastructure as Code (IaC)**

This enables developers to perform **R&D on their own machines** safely and efficiently.

---

## 🧰 Tools & Technologies Used
| Purpose | Tool |
|----------|------|
| **Hypervisor** | Oracle VM VirtualBox |
| **Automation** | Vagrant |
| **Command Line Interface (CLI)** | Git Bash |
| **Code Editor / IDE** | Sublime Text |

---

## 🎯 Objective
- Learn **Virtual Machine Automation** locally.  
- Set up a **real-world project environment** for **R&D**.  
- Build confidence in handling **multi-tier architectures**.

---

## 🏗️ Project Architecture
The **V-Profile Project** consists of multiple servers working together:

| Server | Purpose |
|---------|----------|
| **Nginx** | Web Server |
| **Tomcat** | Application Server |
| **RabbitMQ** | Messaging Queue |
| **Memcached** | Caching Layer |
| **MySQL** | Database Server |

---

## ⚙️ Architecture Diagram
![Architecture Diagram]![ArchitectureDiagram](https://github.com/user-attachments/assets/f11ab771-5fe2-4f7b-a0d7-50700394e439)


---

## ⚡ Architecture of Automated Setup
The project uses the following tools for full automation:
- **Vagrant** for VM provisioning  
- **VirtualBox** for virtualization  
- **Git Bash** for command execution and environment setup  

---

## 🚀 Flow of Execution
1. **Setup Tools** (VirtualBox, Vagrant, Git Bash, Sublime Text)  
2. **Clone Source Code** from the repository  
3. `cd` into the **Vagrant directory**  
4. **Bring up all VMs** using Vagrant (`vagrant up`)  
5. **Validate all VMs** are running correctly  
6. **Setup all services** – MySQL, Memcached, RabbitMQ, Tomcat, Nginx  
7. **Build & Deploy the App**  
8. **Verify from the Browser**

---

## 🌐 About the Web Application
The **V-Profile Web App** is a **social networking site** written in **Java**.  
It demonstrates a **real-world multi-tier application architecture**, ideal for both learning and practical experimentation.

---

## 🧠 Summary
The **V-Profile Project** bridges the gap between learning and real-world AWS setups.  
It simplifies **local development**, promotes **IaC principles**, and provides a **safe environment** for innovation.

---

## 👩‍💻 Author
**Sakshi Sharma**  
📫 [Connect on LinkedIn] : www.linkedin.com/in/sakshisharma48
