# Nginx Web Server on Azure

This repository provides a simple guide to deploy an Ubuntu Virtual Machine (VM) on Azure, install Nginx, and serve custom web files.

## Steps to Deploy Nginx on Azure VM

### 1. Deploy Azure VM
- Create an **Ubuntu** Virtual Machine on Azure.
- Make sure to allow SSH access and note the **public IP address** of the VM.

### 2. Access the VM via SSH
Use the following command to access your VM using SSH:

```bash
ssh -i /path/to/your/private-key.pem username@public-ip-address
