# lets-go-further.pdf

Current location: Chapter 8.1.

```
 go mod init github.com/keirwhitlock/greenlight
```

http://localhost:4000/v1/healthcheck`

```
curl -i localhost:4000/v1/healthcheck
HTTP/1.1 200 OK
Date: Tue, 11 Jan 2022 00:17:03 GMT
Content-Length: 58
Content-Type: text/plain; charset=utf-8

status: available
environment: development
version: 1.0.0
```

`go run ./cmd/api -port=3030 -env=production`


```
 postgres://greenlight:pa55word@localhost/greenlight
```# letsGoFurther
