# V2ray-Server---X-ui
How to Setup V2Ray Server with X-UI Panel


sudo apt update && sudo apt upgrade -y

X-ui Engilsh Version 
bash <(curl -Ls https://raw.githubusercontent.com/NidukaAkalanka/x-ui-english/master/install.sh)

X-ui China Version 
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)

sudo ufw allow 1024:65535/tcp
sudo ufw allow 443/tcp
sudo ufw allow 80/tcp
sudo ufw enable

ufw allow 54321 (Change Your Port)

http://0.0.0.0:54321 (Change Your Port)

Loigin

UserName
Pass
