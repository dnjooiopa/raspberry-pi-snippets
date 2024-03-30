# vaultwarden

[vaultwarden](https://github.com/dani-garcia/vaultwarden)

```sh
docker pull vaultwarden/server:latest

docker rm -f vaultwarden

docker run -d --name vaultwarden -v DATA_DIR:/data/ --restart unless-stopped -p 9080:80 vaultwarden/server:latest
```