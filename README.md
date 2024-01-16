# Rasbperry Pi Snippets

## Docker CE

```sh
sudo apt-get update && sudo apt-get upgrade -y

curl -sSL https://get.docker.com | sh

sudo usermod -aG docker ${USER}

sudo systemctl enable docker

sudo reboot
```

## Docker Compose

```sh
sudo apt -y install python3-pip

sudo pip3 install docker-compose

sudo reboot
```

## Temperature

```sh
vcgencmd measure_temp
```

## Cloudflare

[reference](https://pimylifeup.com/raspberry-pi-cloudflare-tunnel/)

```sh
sudo apt update && sudo apt upgrade -y

curl -L https://pkg.cloudflare.com/cloudflare-main.gpg | sudo tee /usr/share/keyrings/cloudflare-archive-keyring.gpg >/dev/null

echo "deb [signed-by=/usr/share/keyrings/cloudflare-archive-keyring.gpg] https://pkg.cloudflare.com/cloudflared $(lsb_release -cs) main" | sudo tee  /etc/apt/sources.list.d/cloudflared.list

sudo apt update
sudo apt install cloudflared
```
