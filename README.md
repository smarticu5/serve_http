# serve_http

A quick Dockerfile 'borrowed' from [ROPNOP](https://blog.ropnop.com/docker-for-pentesters/#example5servinghttpfiles) to serve HTTP files from the current working directory. 

Usage: 

```docker run --rm -it -p 80:80 -p 443:443 -p "{$PWD}:/srv/data smarticus/serve_http"```