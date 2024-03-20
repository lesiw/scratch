# [lesiw/scratch](https://hub.docker.com/r/lesiw/scratch)

An empty Docker image, but one that you can actually run, unlike `scratch`.

## Build

Install [gx](https://lesiw.io/gx), then set `IMAGE_NAME` as an environment
variable.

`gx build` will build the image locally. `gx release` will build a multi-arch
image and push to Docker Hub.
