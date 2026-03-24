# 🛠️ Home Lab Infrastructure & Portfolio
**Transitioning from Master Carpentry to IT Systems Administration**

## 📖 Project Overview
This repository contains the Infrastructure-as-Code (IaC) configurations for my personal home lab. I am currently utilizing **Proxmox VE** to host a variety of services focused on network security, virtualization, and web hosting.

### 🚀 Tech Stack
* **Hypervisor:** Proxmox VE (LXC & VM)
* **Containerization:** Docker & Portainer
* **Web Server:** Nginx (Alpine Linux)
* **Security:** Pi-hole (Network-wide DNS filtering)
* **Monitoring:** Speedtest-Tracker

## 📂 Featured Project: Professional Portfolio
I deployed a responsive portfolio website using an **Nginx** Docker container.
* **Deployment Method:** Docker Compose (Portainer Stacks)
* **Key Feature:** Utilized **Bind Mounts** to map host directories to the container, allowing for real-time content updates without service interruption.
* **Security:** Implemented Read-Only (`:ro`) volume permissions to follow the Principle of Least Privilege.

### 📸 Project: AI-Powered Private Photo Cloud (PhotoPrism)
* **Goal:** Create a secure, self-hosted alternative to Google Photos for family and project photography.
* **Implementation:** Deployed PhotoPrism using Docker with AI-indexing enabled via TensorFlow.
* **Storage Logic:** Configured persistent bind mounts on a Proxmox host to ensure data durability across container lifecycles.
* **Skills Demonstrated:** AI integration, Linux directory permissions, and database management.
---
*Currently studying for CompTIA A+ | Berkley, MA*
