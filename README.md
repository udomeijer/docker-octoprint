# docker-raspberrypi3-octoprint

Octoprint for Raspberry Pi 3

Exposes:
- 5000

Volumes:
- /data

```
 $ docker run --privileged -p 80:5000 -v /data:/data udom/raspberrypi3-octoprint
```
