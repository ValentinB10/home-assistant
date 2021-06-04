# home-assistant

A personal installation of home-assistant

## Installation steps

### Raspbian

* Install raspbian
* Activate ssh by adding a ssh file in `/media/valentin/boot`
```
cd /media/valentin/boot
touch ssh
```
* Connect to your raspberry with ssh
* Add a fix local IP with DHCP in router.asus.com
* Add a new user
```
sudo useradd -m valentin -G sudo
sudo passwd valentin
```

### Docker

sudo apt install docker.io
groupadd docker
sudo usermod -aG docker $USER
newgrp docker
