# frps, A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet.

[![Docker Build Status](https://img.shields.io/docker/build/onisuly/frps.svg)](https://github.com/onisuly/docker-frps) [![Docker Automated build](https://img.shields.io/docker/automated/onisuly/frps.svg)](https://github.com/onisuly/docker-frps) [![Docker Stars](https://img.shields.io/docker/stars/onisuly/frps.svg)](https://github.com/onisuly/docker-frps) [![Docker Pulls](https://img.shields.io/docker/pulls/onisuly/frps.svg)](https://github.com/onisuly/docker-frps)

This Dockerfile build an image for [frp](https://github.com/fatedier/frp) server.

## Quick Start

```shell
docker run -d --name frps \
-p 7000:7000 \
onisuly/frps
```
