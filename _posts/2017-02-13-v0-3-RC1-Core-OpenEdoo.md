---
title: Openedoo v0.3 RC-1 Core
---

At the beginning of this year we've released version vO.3 which we named "Openedoo Core RC-1" on January 6, 2017. This is the third version of Openedoo. In openedoo core rc-1 there are a few additional amenities and features that are new in version v0.3 but there are also features that are removed. In the coding component in the container `docker` like to prepare, service start and stop the service is still the same with the beta version of v0.2 openedoo. Create a new module and manages modules kodingnya slightly different syntax than the previous version. The facilities and this feature can be used to use an application program openedoo.

## Docker Compose

### Setup
```sh
	$ docker-compose up -d
	$ curl
``` 

### Stop Services
```sh
	$ docker-compose stop
``

### Run And Play
```sh
	$ docker-compose start
```

### Create Module
```sh
	$ docker-compose exec od python manage.py create "test"
```

### Manage Module
```sh
	$ docker-compose stop od
	$ docker-compose run od bash
	[from_od]$ openedoo module create -n "test"
	[from_od]$ opendoo module remove test
	[from_od]$ opendoo module install https://github.com/openedoo/module_hello
```

### New Features :

- New Command Line Management
  * Update Module
- New Module Command Management
- Database Support in module
- Changes to the Core
- New Dockerfile and init.sh

### Remove Feature :
```sh
	db_tables.py on core (removed)
	auth.py on core (removed)
```

Many explanations about the third version of this openedoo. Please upgrade version v0.3 for the User are strongly encouraged to upgrade immediately. I hope you like openedoo application program that has been upgraded. Good Luck ... ^^