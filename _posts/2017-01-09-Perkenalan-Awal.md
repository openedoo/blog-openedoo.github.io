---
title: Get Started Openedoo
---

Openedoo merupakan platform `open source` (terbuka), kami yakin kalian sudah tahu apa itu `open source`. Kalau begitu kita lanjutkan saja apa tujuan dari openedoo. Openedoo itu sendiri yang bertujuan untuk memenuhi kebutuhan web terutama dalam bidang pendidikan. Openedoo sendiri diharapkan bisa menjadi `Platform`pendidikan masa depan berdasarkan tujuan dan kebutuhan. Openedoo merupakan salah satu web `framework python` yang dibangun dengan `framework flask`. 

### Database dan Koneksifitas

Dengan berbasiskan flask maka openedoo dapat menjadikan framework web baik untuk menyajikan data berupa XML, JSON, atau membuat aplikasi berbasis web sederhana. Dibekali dengan sqlalchemy openedoo dapat menggunakan beberapa database seperti mysql, atau sqlite.

### Cara Memasang Framework Openedoo

1. Openedoo berbasis git sehingga yang perlu dilakukan adalah melakukan clone.
   * Git clone https://github.com/openedoo/openedoo
   * Bila tidak memiliki git maka bisa didownload di https://github.com/openedoo/openedoo/archive/master.zip

2. Memasang keseluruhan enviroment yang dibutuhkan dengan menggunakan sintak berikut:

	```
	sudo pip install requirement.txt.
	```

3. Mengedit file config.json.example menjadi config.json dengan configurasi anda.
	{% highlight html linenos %}
	{
    "db":
        {
            "db_engine": "mysql",
            "db_id": "your_username",
            "db_password" : "your_password",
            "db_host" : "localhost",
            "db_port" : "3306",
            "db_name" : "db_openedoo",
            "db_prefix" : "openedoo"
        },
    "config": "Development",
    "secret_key" : "aksaramaya_openedoo"
	}
	{% endhighlight %}
4. dan sekarang anda siap run dengan perintah
	```
	python manage.py run
	```
