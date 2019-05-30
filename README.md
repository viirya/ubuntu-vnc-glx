ubuntu-vnc-glx
=========================

[![Docker Pulls](https://img.shields.io/docker/pulls/viirya/ubuntu-vnc-glx.svg)](https://hub.docker.com/r/viirya/ubuntu-vnc-glx/)
[![Docker Stars](https://img.shields.io/docker/stars/viirya/ubuntu-vnc-glx.svg)](https://hub.docker.com/r/viirya/ubuntu-vnc-glx/)

Docker image to provide Ubuntu LXDE desktop environment with VNC and GLX support.

Usage
-------------------------

```
docker run -it --rm -p 5900:5900 -e VNC_PASSWORD=password viirya/ubuntu-vnc-glx
```

The VNC service port 5900 is forwarded to the host. You could open vnc viewer to connect to port 5900.

