# 💻 V-Profile Project Setup

## 📘 About the Project
**V-Profile** is a **multi-tier web application stack** set up locally on a laptop or desktop.  
It serves as a **baseline for all AWS projects**, enabling developers to build, test, and automate infrastructure in a local environment before moving to the cloud.

This project demonstrates how to automate the setup of an entire application stack using **Vagrant** and **VirtualBox**, providing an **Infrastructure as Code (IaC)** experience for local R&D and testing.

---

## ❗ Problem Statement
Working directly on real servers can be risky and complex. Developers often face:
- Difficulty making configuration changes safely on production systems  
- Time-consuming and error-prone local setups  
- Non-repeatable environments across different machines  

---

## 💡 Solution
Create a **fully automated local setup** of an AWS-like environment using **Vagrant**, **VirtualBox**, and **Git Bash**.  
This setup allows:
- Safe **R&D on your own machine**  
- **Repeatable and automated** provisioning  
- Hands-on experience with **IaC and VM automation**  
- Local testing of **real-world multi-tier applications**

---

## 🎯 Objective
- Learn **Virtual Machine Automation** using **Vagrant**  
- Build a **real-world multi-tier application stack** locally  
- Enable **R&D and experimentation** on a safe, isolated setup  
- Gain foundational skills for **cloud infrastructure automation**

---

## 🧰 Tools & Technologies Used

| **Tool / Technology** | **Purpose** |
|------------------------|-------------|
| **Oracle VM VirtualBox** | Acts as the hypervisor to run multiple VMs locally |
| **Vagrant** | Automates VM creation and provisioning |
| **Git Bash** | CLI for executing commands and managing repositories |
| **Sublime Text** | Lightweight IDE for editing configuration and code files |
| **Java** | Programming language used for the V-Profile web application |

---

## 🏗️ Architecture Overview

### 🧱 Project Servers
The **V-Profile** multi-tier architecture includes:
- **Nginx** – Web Server / Reverse Proxy  
- **Tomcat** – Application Server (Java Web App Deployment)  
- **RabbitMQ** – Messaging Queue  
- **Memcached** – Caching Layer  
- **MySQL** – Database Server  

### ⚙️ Automated Setup Architecture
The setup uses:
- **Vagrant** for defining and provisioning virtual machines  
- **VirtualBox** for hosting VMs  
- **Git Bash** for command execution and automation scripts  

---

## 🔁 Flow of Execution

1. **Setup Tools** – Install VirtualBox, Vagrant, Git Bash, and Sublime Text  
2. **Clone Source Code** – Clone the V-Profile repository from GitHub  
3. **Navigate to Directory** – `cd vagrant`  
4. **Bring Up All VMs** – Run `vagrant up` to start provisioning  
5. **Validate VMs** – Ensure all machines are up and connected  
6. **Setup Services** – Automatically install and configure:
   - MySQL  
   - Memcached  
   - RabbitMQ  
   - Tomcat  
   - Nginx  
7. **Build & Deploy App** – Deploy the Java web application using Tomcat  
8. **Verify Setup** – Access the application via browser to confirm successful deployment  

---

## 🧠 Key Learnings
- End-to-end **VM provisioning automation** using Vagrant  
- Practical understanding of **multi-tier architecture**  
- Experience with **IaC concepts** and **environment reproducibility**  
- Hands-on exposure to **Linux services setup** and **networked VM environments**  

---

## 🚀 Outcome
A **fully functional, locally hosted version** of a multi-tier web application stack that mimics AWS environments — enabling developers to:
- Test and validate infrastructure automation  
- Perform R&D safely on their own machine  
- Build confidence before deploying to the cloud  

---

## 🧑‍💻 Author
**Sakshi Sharma**  
📫 [Connect on LinkedIn](Add_LinkedIn_Profile_Link)  
🌐 [Portfolio/Website](Add_Portfolio_Link)
