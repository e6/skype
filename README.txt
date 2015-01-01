forked from https://github.com/pfcarrier/skype
---
Barebone container used to run skype.

Setup:
Change timezone in Dockerfile

Start with :
  xhost +
  docker run -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=unix$DISPLAY -d 6536/skype

Or use the provided :
  ./build.sh ; ./run.sh
