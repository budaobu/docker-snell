### Latest version

snell-server v1.1.1

### Pull the image

```bash
docker pull bufang/docker-snell:latest
```

### Start a container

```bash
docker run -p 8388:8388 -p 8388:8388/udp -d \
--restart always --name=snell bufang/docker-snell
```

### Display config

```bash
docker logs snell
```
