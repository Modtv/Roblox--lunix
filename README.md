# Roblox--lunix

sudo dpkg --add-architecture i386

sudo wget -nc -O /usr/share/keyrings/winehq-archive.key https://dl.winehq.org/wine-builds/winehq.key

sudo wget -nc -P /etc/apt/sources.list.d/ https://dl.winehq.org/wine-builds/debian/dists/buster/winehq-buster.sources

sudo apt update

sudo apt install --install-recommends winehq-stable

sudo apt install -y gettext git python3-pip python3-setuptools python3-wheel python3-dev pkg-config mesa-utils libcairo2-dev gtk-update-icon-cache desktop-file-utils xdg-utils 

git clone --depth=1 https://gitlab.com/brinkervii/grapejuice.git /tmp/grapejuice

cd /tmp/grapejuice

python3 ./install.py
