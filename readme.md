# Django Devenv Simple

## Local directory Structure

``` Directory structure
<work-dir>  
 ├── docker-compose.yml
 │
 ├── app
 │   ├── dockerfile
 │   ├── requirements.txt
 │   ├── entrypoint.sh
 │   └── mysite
 │       ├── manage.py
 │       └── mysite
 │           ├── __init__.py
 │           ├── asgi.py
 │           ├── settings.py
 │           ├── urls.py
 │           └── wsgi.py
 │
 ├── web
 │   ├── Dockerfile
 │   └── nginx.conf
 │
 └── db
     ├── Dockerfile
     └── sql
         └── init.sql
```
