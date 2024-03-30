## Cloudflare

[reference](https://pimylifeup.com/raspberry-pi-cloudflare-tunnel/)

```sh
sudo apt update && sudo apt upgrade -y

curl -L https://pkg.cloudflare.com/cloudflare-main.gpg | sudo tee /usr/share/keyrings/cloudflare-archive-keyring.gpg >/dev/null

echo "deb [signed-by=/usr/share/keyrings/cloudflare-archive-keyring.gpg] https://pkg.cloudflare.com/cloudflared $(lsb_release -cs) main" | sudo tee  /etc/apt/sources.list.d/cloudflared.list

sudo apt update
sudo apt install cloudflared
```
