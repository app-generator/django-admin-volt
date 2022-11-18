# [Django Admin Volt](https://github.com/app-generator/django-admin-volt)

Modern template for **Django Admin Interface** coded on top of **Volt Dashboard**, an open-source `Boostrap 5` design. 

> Actively supported by [AppSeed](https://appseed.us/) via `Email` and `Discord`.

<br>

**Links & Resources**

- [Django Volt Dashboard](https://appseed.us/product/volt-dashboard/django/) - free starter with the same design
- [Django Volt Dashboard](https://django-volt-dashboard.appseed-srv1.com/) - LIVE Demo

<br />

## [Black Friday](https://appseed.us/discounts/) - `75%OFF`

> The campaign is active until `30.NOV` and applies to all products and licenses.

[![AppSeed - Black Friday 2022 Campaign, 75% OFF Discount (all products).](https://user-images.githubusercontent.com/51070104/201829599-9fe6bdd7-3f19-46f3-9115-962eeb13bf29.jpg)](https://appseed.us/discounts/)

<br />

## Why `Django Admin Volt`

- Modern `Bootstrap 5` Design
- `Responsive Interface`
- `Minimal Template` overriding
- `Easy integration`

<br>

## How to use it

<br />

> Install the package via `PIP` 

```bash
$ pip install django-admin-volt
// OR
$ pip install git+https://github.com/app-generator/django-admin-volt.git
```

<br />

> Add `admin_volt` application to the `INSTALLED_APPS` setting of your Django project `settings.py` file (note it should be before `django.contrib.admin`):

```python
    INSTALLED_APPS = (
        ...
        'admin_volt.apps.AdminVoltConfig',
        'django.contrib.admin',
    )
```

<br />

> Collect static if you are in production environment:

```bash
$ python manage.py collectstatic
```

<br />

> Start the app

```bash
$ # Set up the database
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Create the superuser
$ python manage.py createsuperuser
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
```

Access the `admin` section in the browser: `http://127.0.0.1:8000/`

<br />

## Screenshots

> **Volt Theme** - `Admin Section`  

![Django Admin Volt - Main Django Dashboard screen.](https://user-images.githubusercontent.com/51070104/136143245-85cd8af7-43ea-4956-8fcd-45e307171943.png) 

<br />

> **Volt Theme** - `Dashboard`

![Django Admin Volt - Template project for Django provided by AppSeed.](https://user-images.githubusercontent.com/51070104/132288100-0c65159f-71a6-41f0-9f55-9544916385ae.jpg)

<br />

---
**[Django Admin Volt](https://github.com/app-generator/django-admin-volt)** - Modern Admin Interface provided by **[AppSeed](https://appseed.us/)**
