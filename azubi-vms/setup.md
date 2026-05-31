# Azubi VM Setup

## Requirements
- Debian 12
- 1 Core, 1GB RAM, 12GB Disk

## Post Installation
apt update && apt upgrade -y
apt install vim sudo
usermod -aG sudo it11
mkdir -p /var/www/html

## Cloning
Clone the template VM in Proxmox for each apprentice
