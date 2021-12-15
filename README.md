# Envoy Compressor

## Start

```bash
cd ./v1.19.1
docker-compose up
```

* Access: `localhost:8000`

```bash
$ curl "http://localhost:8000/" -X "GET" --compressed -I

HTTP/1.1 200 OK
x-powered-by: Express
content-type: application/json; charset=utf-8
etag: W/"21d-lrW6z0EnVx7JX0I23RvZRHWPGpU"
date: Thu, 16 Dec 2021 11:13:38 GMT
x-envoy-upstream-service-time: 1
content-encoding: gzip
vary: Accept-Encoding
server: envoy
transfer-encoding: chunked
```
