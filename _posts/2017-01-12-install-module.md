---
title: Cara memasang module pada openedoo
---

Openedoo menyediakan fitur berupa modul - modul yang disediakan oleh openedoo atau pun yang dibuat oleh komunitas itu sendiri. Openedoo mempunyai keunikan dimana setiap orang yang membuat modul dapat menyimpan di repositori git masing-masing. fitur module yang disediakan oleh openedoo adalah sebagai berikut :

	1. module available : 
	berfungsi untuk mencari modul - modul yang disediakan oleh openedoo
	2. module create : 
	berfungsi untuk membuat modul dasar, modul dasar yang dibuat sebagai endpoint url
	3. module update : 
	berfungsi untuk mengupdate modul yang telah dipasang, 
	modul update ini berasal dari perintah pull pada git
	4. module remove : 
	berfungsi untuk menghapus modul yang telah dipasang
	5. module installed : 
	berfungsi untuk mengecek modul apa saja yang telah dipasang
	6. module install : 
	menginstall modul dari repositori git baik github,gitlab atau pun yang lainnya

### Perintah dasar modul

semua perintah openedoo terdapat pada **manage.py** sehingga cara untuk eksekusi perintah module adalah sebagai berikut:

```
python manage.py module <perintah>
```

### Cara mencari modul yang telah disediakan

```
python manage.py module available
```

### Cara membuat modul baru


```
python manage.py module create -n <nama modul>
```

anda dapat memasang remote git secara langsung dengan perintah sebagai berikut:

```
python manage.py module create -n <nama modul> -r <git remote url>
```

### Cara mengupdate module

```
python manage.py module update -n <nama modul>
```

### Cara menghapus modul

```
python manage.py module remove <nama modul>
```

### Cara mencari modul yang telah dipasang

```
python manage.py module installed
```

### Cara memasang modul dari repositori

```
python manage.py module install <git url>
```