# x11-firefox-docker

http://postd.cc/running-gui-apps-with-docker/

# Usage
```
docker run -it --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix prince0203/x11-firefox
```
