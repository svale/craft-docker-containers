# craft-docker-containers
A suitable set of containers for running a Craft CMS site in Docker

[ *Work in progress* ]


The setup includes containers for:
* nginx - web server
* php - run php-fpm (php8)
* mariadb - database
* redis - key/value database for caching & php sessions

# Use
Download and unzip the entire repo to your computer
```
https://github.com/svale/craft-docker-containers/archive/main.zip
```
Delete the following files from the download
```
README.md
LICENSE
```

Run
```
$ docker-compose up
```


# Credits
Inspired and informed by https://github.com/nystudio107/craft

