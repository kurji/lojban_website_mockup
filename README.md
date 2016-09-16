# lojban_website_mockup
Lojban Website Mockup

## Installing

First install `pip3` for Python3:

```shell
sudo apt-get install python3-pip
```

If that doesn't work, try:

```shell
wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py
```

Then install Django:

```shell
sudo pip3 install django
```

Then run:

```shell
python3 jbobau/manage.py runserver
```

go to localhost:8000/index/ and voila!

If that last command doesn't work, ensure `python3 --version` returns at least 3.4.
