# Simple NGINX
Simple NGINX is a fairly simple, static website running on NGINX to demonstrating NGINX in a Docker container.

## Building from Scratch
Simple NGINX is hosted in a Docker Hub repository under `arueth/simple-nginx` but you can also build it locally with the following steps:

```
$ git clone https://github.com/docker-demo/simple-nginx.git
$ cd simple-nginx
$ docker build -t simple-nginx .
```

## Running the Built Container

```
$ docker run -it -p 8080:80 simple-nginx
```

