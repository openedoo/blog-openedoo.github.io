---
title: Openedoo vO.1 Core
---

### Hello friends of the OpenEdoo ... !!!

We just released the first version of vO.1 which we named "Openedoo Core" on November 30, 2016. Probably the first version is still quite simple just some basic amenities that we provide. Like migration database, create a new module, and several features that can be used to use openedoo application program.

### Migrate Database
```sh

	python manage.py db init
	python manage.py db migrate
	python manage.py db upgrade
	python manage.py --help 
```
### Creat New Modul
```sh 
	python manage.py create "module_name" 
```

### OpenEdoo Features
```sh
	- Build from Flask
	- Werkzeug Support
	- Management Command Line
	- ORM Support (Database)
	- Database Engine Support
	- Mysql
	- SQLite
	- Postgresql
	- API Support
	- Third Party Module Support
```

You can use the terminal to run this application program with the following syntax:

```sh 
python manage.py runserver 
```

Many explanations about the first version openedoo. I hope you liked our application program. Good luck ... ^^