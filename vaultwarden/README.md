# vaultwarden

[vaultwarden](https://github.com/dani-garcia/vaultwarden)

```sh
docker rm -f vaultwarden

docker rmi vaultwarden/server:latest

docker pull vaultwarden/server:latest

docker run -d --name vaultwarden -v {DATA_DIR}:/data/ --restart unless-stopped -p 9080:80 vaultwarden/server:latest
```
