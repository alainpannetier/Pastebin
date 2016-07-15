#Golang Pastebin
[![Build Status](https://travis-ci.org/ewhal/Pastebin.svg?branch=master)](https://travis-ci.org/ewhal/Pastebin) [![GoDoc](https://godoc.org/github.com/ewhal/Pastebin?status.svg)](https://godoc.org/github.com/ewhal/Pastebin) [![Go Report Card](https://goreportcard.com/badge/github.com/ewhal/Pastebin)](https://goreportcard.com/report/github.com/ewhal/Pastebin) [![MIT
licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/pomf/pomf/master/LICENSE.md)

Modern self-hosted pastebin service with a restful API.

## Motivation
Many Pastebin services exist but all are more complicated than they need to be.
That is why I decided to write a pastebin service in golang.

![paste](http://i.imgur.com/7BeCKa3.png)

## Getting started
### Prerequisities
* pygmentize
* go
* mariadb

```
pip install pygmentize
sudo yum install -y go mariadb-server mariadb
```

### Installing

* go get https://github.com/ewhal/Pastebin
* nano pastebin.go
* Configure port and database details
* make

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

