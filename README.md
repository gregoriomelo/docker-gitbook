# gitbook

[![dockeri.co](http://dockeri.co/image/_/gregoriomelo/docker-gitbook/)](https://registry.hub.docker.com/_/gregoriomelo/docker-gitbook/)

Use [gitbook](https://github.com/GitbookIO/gitbook) in a Docker container. Based on [node:alpine](https://hub.docker.com/_/node/)

## Usage

### Initializing your book

```
docker run -it -v $PWD:/home/book -w /home/book --rm -p 4000:4000 --name gitbook gregoriomelo/gitbook gitbook init
```

### Serving your book

```
docker run -it -v $PWD:/home/book -w /home/book --rm -p 4000:4000 --name gitbook gregoriomelo/gitbook gitbook serve
```
