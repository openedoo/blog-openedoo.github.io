---
title: Openedoo v0.2 Beta
---
### Hello Friends of OpenEdoo ... !!!

At the year end of 2016 we've released version vO.2 which we named "Openedoo Beta" on December 17, 2016 ago. This is the second version of Openedoo. In openedoo beta there are a few additional amenities and features that are new in version v0.2. Additional facilities such as `docker` containers so as to facilitate the application installation process, without having to bother to enviroment - enviroment that has been presented. And the feature 'Management Command Line' more complete and detail in comparison with the previous version. The facilities and this feature can be used to use an application program openedoo.

## Docker Compose

### Setup
```sh
	$ docker-compose up -d
	$ curl
```

### Stop Services
```sh
	$ docker-compose stop
```

###Run And Play
```sh
	$ docker-compose start
```

###Create Module
```sh
	$ docker-compose stop od
	$ docker-compose run od python manage.py create "test"
	$ docker-compose start od
```

###Manage Module
```sh
$ docker-compose stop od
$ docker-compose run od bash
[from_od]$ python manage.py create "test"
[from_od]$ python manage.py remove test
[from_od]$ python manage.py install https://github.com/openedoo/module_hello
```
### New Features :
```sh
	- New Command Line Management
	  * Create module
	  * Remove module
	  * Install module from git
	  * Check Module installed
	  * Check Official Module Available
	- Container Support (Docker)
	- Database Config
```

Many explanations about the second version openedoo. Please upgrade v0.2 version as soon as possible. I hope you liked the upgrade application program openedoo beta. Good luck ... ^^