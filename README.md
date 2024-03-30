# Rasbperry Pi Snippets

## Create user

```sh
sudo adduser --disabled-password --gecos "" USER_NAME
```

## Add user to group

```sh
sudo adduser USER_NAME GROUP
```

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
