# E-commerce-graphql-django

This is the back-end side of a e-commerce website.

[Here](https://github.com/jsebdev/E-commerce-graphql-nextjs) is the front-end side and it's [deployment](http://port-ecommerce.shop/)

Table of Contents
=================

* [E-commerce-graphql-django](#E-commerce-graphql-django)
   * [Principal Features:](#principal-features)
   * [Environment variables](#environment-variables)
   * [How to run](#how-to-run)

## Principal Features:

- 3 models: User, Item, tag
- User authentication using graphql
- Storage and optimization of images

## Environment variables
The following environment variables are necessary for the correct functioning. Add them to an .env file

- EMAIL_HOST_PASSWORD: String
- SECRET_KEY: String
- PRODUCTION: True | False
- DEBUG: True | False
- FRONT_DOMAIN: String
- ALLOWED_HOSTS: String (comma separated)
- CORS_ORIGIN_WHITELIST: String (comma separated)
- CUSTOM_PASSWORD: String

## How to run

Clone the repo

```
https://github.com/jsebdev/E-commerce-graphql-django.git
cd E-commerce-graphql-django
```

If you don't have installed virtual env yet, install it
```
pip install virtualenv
```

Create and run the virtual environment

```
virtualenv env
source env/bin/activate
```

Install all dependencies

```
pip3 install -r requirements.txt
```

Run django server

```
python3 manage.py runserver
```
