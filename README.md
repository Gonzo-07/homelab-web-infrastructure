# 💻 Homelab Web Infrastructure

A browser-based Linux course built on 
Proxmox. The goal was to create a professional learning 
environment accessible from anywhere without any local 
setup required.

> Built as a side project to help colleagues prepare 
> for their Linux exam 

## 📦 Tech Stack
- Proxmox VE
- Debian 12
- Nginx (Reverse Proxy)
- MkDocs + Material Theme
- Apache Guacamole (Docker)
- Cloudflare Tunnel
- MySQL

## 🚦 Requirements
- Proxmox Server (min. 32GB RAM)
- Cloudflare Account (Free)
- Domain (recommended)
- Debian 12 ISO

## ⏱️ Time Spent
Around 25 hours across multiple sessions

## 🦄 Features
- Browser-based terminal access via Apache Guacamole
- Dedicated VM per apprentice
- No password login required (credentials stored in Guacamole)
- Accessible from anywhere via Cloudflare Tunnel
- 8 course chapters in MkDocs
- VM reset capability via Proxmox snapshots

## 🔁 Reusable Infrastructure

This project serves as a base infrastructure for 
multiple web projects. Adding a new service is as 
simple as:

1. Create a new VM or project
2. Add a new location block in Nginx
3. Add a new subdomain in Cloudflare
4. Done! 🎉

**Already running:**
- 🐧 Linux Course (this project)

**Planned:**
- 📝 CTF Writeups
- 🌐 Portfolio Website
- 📚 Project Wiki

## 🎯 Architecture
<img width="676" height="929" alt="image" src="https://github.com/user-attachments/assets/8bfc0a53-d738-4fbe-98a4-c4170e4e9cf6" />

Internet → Cloudflare Tunnel → Nginx Reverse Proxy → MkDocs / Guacamole → Apprentice VMs

## 📚 What I Learned
- Setting up and managing multiple Linux VMs on Proxmox
- Configuring Nginx as a Reverse Proxy including WebSocket support
- Deploying services with Docker and Docker Compose
- Setting up Cloudflare Tunnel for secure external access
- WebSocket configuration for real-time browser applications
- Network fundamentals in a homelab environment

## 💭 How can it be improved?
- Add a Windows/Active Directory course
- Add automated VM resets after each session
- Add a monitoring dashboard
- Add more course chapters

## 🍿 Video 



https://github.com/user-attachments/assets/272f0299-201e-4f78-8b7f-bc3c97353e48

