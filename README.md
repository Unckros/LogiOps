# LogiOps
// Instalação:
yay -Suy logiops-git
cd /tmp 
mkdir git
cd git
git clone https://github.com/Unckros/LogiOps.git
cd LogiOps
sudo mv logid.cfg /etc/
sudo systemctl enable --now logid
