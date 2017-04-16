# 🌱 The smallest and most compact PHP 7.x Docker image

 [![Build Status](https://travis-ci.org/ulabs-org/php7-base.svg)](https://travis-ci.org/ulabs-org/php7-base)

This docker image based on [Alpine](https://hub.docker.com/_/alpine/) ( [Alpine Linux](http://www.alpinelinux.org) - 
lightweight Linux distribution).

The size of this docker image is very small, ≈ 56Mb!

## How get The Image

This image is published in the [Docker Hub](https://hub.docker.com/r/imkulikov/php7-base/).

Run command in your terminal:

```sh
docker pull imkulikov/php7-base
```

### PHP Modules
```
# php -m
Core
ctype
curl
date
dom
fileinfo
filter
ftp
hash
iconv
json
libxml
mbstring
mysqlnd
openssl
pcre
PDO
pdo_sqlite
Phar
posix
readline
Reflection
session
SimpleXML
SPL
sqlite3
standard
tokenizer
xml
xmlreader
xmlwriter
zlib

[Zend Modules]
Zend OPcache
```
