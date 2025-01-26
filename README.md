# V2Ray Server with X-UI Panel Installation Guide

Easily install and configure your **V2Ray Server** with the **X-UI Panel** for better management.

---

## 🛠 Step 1: Update Your System

Run the following command to update and upgrade your server:

```bash
sudo apt update && sudo apt upgrade -y

```
## 🛠 Step 2: Install X-UI Panel
English Version Installation
To install the English version of X-UI, run the command below:
```bash
bash <(curl -Ls https://raw.githubusercontent.com/NidukaAkalanka/x-ui-english/master/install.sh)

```
Chinese Version Installation
To install the Chinese version of X-UI, use the command below:
```bash
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)

```
🛠 Step 3: Configure Firewall (UFW Rules)
To ensure proper access, configure your firewall with the following commands:
# Change your port if needed
```bash
sudo ufw allow 1024:65535/tcp
sudo ufw allow 443/tcp
sudo ufw allow 80/tcp
sudo ufw enable
sudo ufw allow 54321

```
🛠 Step 4: Access the X-UI Panel
Once installation is complete, open your browser and visit:
(Replace your-server-ip with your actual server IP address.)
```bash
http://your-server-ip:54321

```
🛠 Step 5: Default Login Credentials
Your default login credentials will be set during installation. Example:
Username: Set during installation
Password: Set during installation
