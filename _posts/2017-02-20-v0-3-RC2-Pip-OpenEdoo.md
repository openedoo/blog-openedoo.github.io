---
title: Openedoo has realesed in "pip"
---

Hello...!!!

Openedoo has been released in the pip with version 1.0.1 on February 7, 2017. On its own version openedoo vO.3 RC-2 which we named "Openedoo pip RC-2" can add pip installation. How do I install openedoo namely with the "pip install openedoo". Once installed then there command openedoo in the terminal. To install just need to type "openedoo install". And then open the folder openedoo, and run "python manage.py". In the coding component within the docker and its features are the same as the previous version is v0.3 RC-1.

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

Many explanations about the third version of this openedoo. Please upgrade version v0.3 pip for the User are strongly encouraged to upgrade immediately. Hope you like openedoo application program that has been upgraded. Good luck ... ^^