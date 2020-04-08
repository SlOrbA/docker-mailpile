# Mailpile Docker image

A minimal Mailpile Docker image based on Alpine Linux.

## Usage

```
docker run -d --name mailpile -p 33411:33411 slorba/mailpile
```

Bind volume `/root` for persistent storage:

```
docker run -d --name mailpile -p 33411:33411 -v /some/local/path:/root/ slorba/mailpile
```
