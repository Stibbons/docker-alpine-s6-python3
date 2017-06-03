[![Docker Stars](https://img.shields.io/docker/stars/stibbons31/alpine-s6-python3.svg?style=flat-square)](https://hub.docker.com/r/stibbons31/alpine-s6-python3/) [![Docker Pulls](https://img.shields.io/docker/pulls/stibbons31/alpine-s6-python3.svg?style=flat-square)](https://hub.docker.com/r/stibbons31/alpine-s6-python3/)

# Alpine S6 Python 3

Alpine Linux Base Docker Image with Python 3 and s6-overlay.

Link to [Dockerfile](https://github.com/Stibbons/docker-alpine-s6-python3/blob/master/Dockerfile)

This image is based on [LinuxServer.io](https://www.linuxserver.io/) Alpine Python 2 image: [github.com/linuxserver/docker-baseimage-alpine-python](https://github.com/linuxserver/docker-baseimage-alpine-python), itself based upon [Alpine Linux](https://hub.docker.com/_/alpine/) and [S6 overlay](https://github.com/just-containers/s6-overlay).

# Usage Example

```bash
$ docker run --rm stibbons31/alpine-s6-python3 python3 -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!

NOTE:
- `pip`/`pip3` are also available in this image.
- `python`/`python3` are also available in this image.
