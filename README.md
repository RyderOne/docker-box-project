# docker-box-project
Git repository for docker image with box project to build phar

This is a simple Dockerfile with Box project to build php application .phar

Use it like this (from your application directory) :
```sh
$ docker run --rm -v "$PWD":/usr/src docker-box-project box build
```

> Note that you need, according to box project documentation, a box.json (or box.json.dist) file inside your application directory

All credits to https://github.com/box-project/box2
