# Usage
To run use:

```
docker run --rm -ti \
  -e DISPLAY=$DISPLAY \
  -e XAUTHORITY=/.Xauthority \
  -v /tmp/.X11-unix:/tmp/.X11-unix \
  -v ~/.Xauthority:/.Xauthority:ro \
  -v /mount/your/movies/place:/home/developer/movies
  tgagor/subget
```
