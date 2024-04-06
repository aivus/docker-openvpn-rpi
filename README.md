# OpenVPN for RPi

This repository is a fork of [nuBacuk/docker-openvpn](https://github.com/nuBacuk/docker-openvpn) which is synced monthly with upstream.

Check [README.md](https://github.com/nuBacuk/docker-openvpn?tab=readme-ov-file) from the original repo for details

#### Links

* Docker Registry @ [aivus/openvpn-rpi](https://hub.docker.com/r/aivus/openvpn-rpi)
* GitHub Repository @ [aivus/docker-openvpn-rpi](https://github.com/aivus/docker-openvpn-rpi)

### Special notes

* In case you cannot access the network from inside the container, or you are seeing `clock_gettime(MONOTONIC) failed` error

  Please [follow next steps](https://docs.linuxserver.io/FAQ/#libseccomp) or use `aivus/openvpn-rpi:alpine-3.12`
