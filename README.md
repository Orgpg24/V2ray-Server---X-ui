# V2Ray Server with X-UI Panel Installation Guide

Easily install and configure your **V2Ray Server** with the **X-UI Panel** for better management.

## Step 1: Update Your System
```bash
sudo apt update && sudo apt upgrade -y

Step 2: Install X-UI Panel

English Version Installation
bash <(curl -Ls https://raw.githubusercontent.com/NidukaAkalanka/x-ui-english/master/install.sh)

Chinese Version Installation
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)

Step 3: Configure Firewall (UFW Rules)
sudo ufw allow 1024:65535/tcp
sudo ufw allow 443/tcp
sudo ufw allow 80/tcp
sudo ufw enable
sudo ufw allow 54321  # Change your port if needed


Step 4: Access the X-UI Panel
Open your browser and visit:
http://your-server-ip:54321


Step 5: Default Login Credentials
Username: Your set username
Password: Your set password


