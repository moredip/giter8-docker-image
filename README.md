# giter8 docker image

A simple containerization of [giter8](https://github.com/n8han/giter8). 

To use it:
```
docker run -v ${HOME}/tmp:/g8out moredip/giter8 softprops/unfiltered.g8 --name=my-new-website
```

This will take generate a new `my-new-website` project based on the `[softprops/unfiltered.g8](softprops/unfiltered.g8)` template and place it in `~/tmp/my-new-website`.
