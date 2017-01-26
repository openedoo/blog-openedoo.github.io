---
title: How to install the module on openedoo
---

Openedoo provides features such as module - module provided by openedoo or created by the community itself. Openedoo has a unique where every person who makes the module can store in a git repository respectively. module features provided by openedoo are as follows:

	1. module available:
	serves to locate the module - module provided by openedoo
	2. The module create:
	serves to make the base module, the basic module is made as endpoint url
	3. The module updates:
	serves to update the modules that have been installed,
	The update module comes from the git pull command
	4. remove module:
	serves to remove modules that have been installed
	5. module installed:
	serves to check the modules have been installed
	6. module installed:
	install modules from both github git repository, or any other gitlab

### Basic commands module

All openedoo commands contained in ** manage.py ** so that way for the execution of the commands module is as follows:

```
python manage.py module <command>
```

### How to find a module that has been provided

```
python manage.py module available
```

### How to create a new module

```
python manage.py module create -n <the modul name>
```

You can attach the remote git directly with the following command:

```
python manage.py module create -n <the modul name> -r <git remote url>
```

### How to update the module

```
python manage.py module update -n <the modul name>
```

### How to remove a module

```
python manage.py module remove <the modul name>
```

### How to find the modules that have been installed

```
python manage.py module installed
```

### How to install the module from the repository

```
python manage.py module install <git url>
```