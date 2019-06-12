### Pull the image

```bash
$ docker pull bufang/docker-snell
```

### Start a container

```bash
docker run -p 4231:4231 -p 4231:4231/udp -d \
--restart always --name=snell deercloud/snell
```

### Display config

```bash
docker logs snell
```
