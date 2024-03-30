# Docker CE

```sh
sudo apt-get update && sudo apt-get upgrade -y

curl -sSL https://get.docker.com | sh

sudo usermod -aG docker ${USER}

sudo systemctl enable docker

sudo reboot
```

# Docker Compose

```sh
sudo apt -y install python3-pip

sudo pip3 install docker-compose

sudo reboot
```
