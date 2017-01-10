# gitbook

[![dockeri.co](http://dockeri.co/image/_/gregoriomelo/gitbook/)](https://registry.hub.docker.com/_/gregoriomelo/gitbook/)

Use [gitbook](https://github.com/GitbookIO/gitbook) in a Docker container.

## Usage

### Initializing your book

```
docker run -it -v $PWD:/home/book -w /home/book --rm -p 4000:4000 --name gitbook gregoriomelo/gitbook gitbook init
```

### Serving your book

```
docker run -it -v $PWD:/home/book -w /home/book --rm -p 4000:4000 --name gitbook gregoriomelo/gitbook gitbook serve
```
