# One-line Web Servers

### Python 2.x

```shell
python -m SimpleHTTPServer 8080
```
### Python 3.x

```shell
python -m http.server 8080
```

### Ruby 1.9.2+

```shell
ruby -run -e httpd . -p 8080
```

### PHP 5.4+

```shell
php -S 0.0.0.0:8080
```

### NodeJS (http-server)

```shell
$ npm install -g http-server
$ http-server -p 8000
```
### NodeJS (node-static)

```shell
$ npm install -g node-static
$ static -p 8000
```

### Go (spark)

```shell
$ go get github.com/rif/spark
$ spark -port 8000 .
```

### BusyBox

```shell
$ busybox httpd -f -p 8000
```

### Webfsd 

```shell
$ webfsd -F -p 8000
```

## Credits

- [Discussion on reddit](https://www.reddit.com/r/webdev/comments/1fs45z/list_of_ad_hoc_http_server_oneliners)
- [willurd/web-servers.md gist](https://gist.github.com/willurd/5720255)