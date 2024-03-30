# memos

[memos](https://github.com/usememos/memos)

```bash
docker rm -f memos

docker rmi neosmemo/memos:stable

docker pull neosmemo/memos:stable

docker run -d --name memos -p 5230:5230 --restart unless-stopped -v DATA_DIR:/var/opt/memos neosmemo/memos:stable
```
