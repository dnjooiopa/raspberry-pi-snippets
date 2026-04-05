# File Browser

## Docker Installation

```sh
docker run --name filebrowser \
    -dp 8080:80 \
    --restart unless-stopped \
    -v /path/to/srv:/srv \
    -v /path/to/database:/database \
    -v /path/to/config:/config \
    filebrowser/filebrowser
```
