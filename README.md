# Simple NGINX
Simple NGINX is a fairly simple, static website running on NGINX to demonstrating NGINX in a Docker container.

## Building from Scratch
This repo is used to showcase a build change from within Rancher.  I have placed the 2 versions of the Docker image on Docker hub.

This repo is the final copy.

```
$ clone the git
$ cd nginxdemo
$ docker build -t <imagename> .
```

## Running the Built Container

```
$ docker run -it -p 80:80 <imagename>
```

