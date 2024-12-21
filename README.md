# Nginx Web Server on Azure

This repository provides a simple guide to deploy an Ubuntu Virtual Machine (VM) on Azure, install Nginx, and serve custom web files.

## Steps to Deploy Nginx on Azure VM

### 1. Deploy Azure VM
- Create an **Ubuntu** Virtual Machine on Azure.
- Make sure to allow SSH access and note the **public IP address** of the VM.

### 2. Access the VM via SSH
Use the following command to access your VM using SSH:

ssh -i /path/to/your/private-key.pem username@public-ip-address 

#### 3. Install Nginx & Config

![WhatsApp Image 2024-12-21 at 11 34 26 AM](https://github.com/user-attachments/assets/37b13fa2-c3fe-463f-822b-9a367775f1a1)

![Screenshot (72)](https://github.com/user-attachments/assets/b4c97276-0a47-4cb7-89ce-ce2744df9f90)


##### 4. Load Default Nginx Web Page

http://public-ip-address

![WhatsApp Image 2024-12-21 at 11 34 27 AM (1)](https://github.com/user-attachments/assets/edd8c5bb-c2eb-4be4-9fa5-61994b8dcae1)


##### 5.Upload & Move Web Files,Execute

make the web pages like index.html,style.css and main.js.
move the web files to var/www/ file 
make the change (var/www/html/ to var/html/nginx.azurex0.com) on etc/nginx/sites-available/default file

![Screenshot (74)](https://github.com/user-attachments/assets/eeca97ab-c678-44c8-b320-7323089535c5)

###### 6. Load the public ip on web browser

![WhatsApp Image 2024-12-21 at 11 34 27 AM](https://github.com/user-attachments/assets/666c8d0a-596e-4ed6-8b7e-7b695a1338d0)



