# dia-fedora-dockerfile
This repository contains Dockerfile to auto-build Dia tool in Docker image

To start the application, run:

```
docker run -v $HOME:$HOME --net host -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY= -e XAUTHORITY=/.Xauthority -v ~/.Xauthority:/.Xauthority:ro vpavlin/dia
```
