[![Build Status](https://travis-ci.com/trydirect/symfony-restful.svg?branch=master)](https://travis-ci.com/trydirect/symfony-restful)
![Docker Stars](https://img.shields.io/docker/stars/trydirect/symfony4-restful.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/trydirect/symfony4-restful.svg)
![Docker Automated](https://img.shields.io/docker/cloud/automated/trydirect/symfony4-restful.svg)
![Docker Build](https://img.shields.io/docker/cloud/build/trydirect/symfony4-restful.svg)
[![Gitter chat](https://badges.gitter.im/trydirect/community.png)](https://gitter.im/try-direct/community)

# symfony4-restful
RESTfull API template based on Symfony 4 for development purpose
* PHP-fpm 7.2.11
* Rest API
* MySQL 5.7
* Redis latest
* Elasticsearch 5.4.3
* Kibana 5.4.3
* Logstash 5.4.0
* XDebug 2.6.1
* Nginx 
* Supervisord
* Ubuntu 18.04

## Note
Before installing this project, please, make sure you have installed docker and docker-compose

To install docker execute: 
```sh
$ curl -fsSL https://get.docker.com -o get-docker.sh
$ sh get-docker.sh
$ pip install docker-compose
```
## Installation
Clone this project into your work directory:
```sh
$ git clone "https://github.com/trydirect/symfony4-restful.git"
```
Then build it via docker-compose:
```sh
$ cd symfony4-restful
$ docker-compose up -d
```


# Contributing

1. Fork it (https://github.com/trydirect/symfony4-restful/fork)
2. Create your feature branch (git checkout -b feature/fooBar)
3. Commit your changes (git commit -am 'Add some fooBar')
4. Push to the branch (git push origin feature/fooBar)
5. Create a new Pull Request
