# spatialverse-aws

Docker container with R, RStudio, various spatial packages, and the tidyverse.

## How to use

Download and run this image using the following commands:

To use Rstudio:

```
docker run -d -p 8787:8787 earthlab/spatialverse-aws
```

In a web browser, navigate to localhost:8787 (on linux) or on a Mac, substitute the location pointed to by `docker-machine ip default` for `localhost`.
Log in with username: rstudio, password: rstudio.

## Mounting folders

If you want to share a directory between your host machine and the container, use the `-v` flag in your call to `docker run`, as described [here](https://github.com/rocker-org/rocker/wiki/Sharing-files-with-host-machine).
For more information on how to take full advantage of RStudio in this image, see https://github.com/rocker-org/rocker/wiki/Using-the-RStudio-image.

