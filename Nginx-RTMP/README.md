# Nginx & RTMP Module

## Building
```
$ docker build -t nginx-rtmp:1.12.0 .
```

## Running
```
$ docker run -it -p 80:80 -v $(pwd)/nginx.conf:/etc/nginx/nginx.conf -v $(pwd)/html/:/usr/share/nginx/html/ nginx-rtmp:1.12.0
```