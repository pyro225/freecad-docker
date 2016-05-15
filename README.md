# Docker Image for FreeCad

## Why

## Usage

```bash
$ docker run --name freecad -v ~/workspace/:/home/freecad/workspace/:ro -e "DISPLAY=unix:0.0" --privileged -v /tmp/.X11-unix:/tmp/.X11-unix:ro -d pyro225/freecad-docker:stable
```

## Troubleshooting

If you have trouble opening the window, try this:

```bash
$ xhost +si:localuser:freecad
```
