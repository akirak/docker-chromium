# Docker image providing a Chromium executable for Puppeteer

![build](https://github.com/akirak/docker-chromium/workflows/build/badge.svg)

This repository provides Alpine Linux images containing only a specific version of Chromium. It is intended for use with [Puppeteer](https://github.com/puppeteer/puppeteer), a browser automation library for JavaScript. Each Puppeteer version must be combined with its corresponding version of Chromium, and this image enables that.

The image name is `akirak/chromium`, and tags are created from the version of Chromium and the distribution, e.g.

```
akirak/chromium:83.0.4103-alpine
akirak/chromium:83-alpine
```

For the up-to-date list of tags, see the [list on Docker Hub](https://hub.docker.com/repository/docker/akirak/chromium/tags). Images are built against stable releases of Alpine Linux, so if the build is outdated (see [the package database of Alpine](https://pkgs.alpinelinux.org/packages?name=chromium) to check if there is a new release), please feel free to create a PR.
