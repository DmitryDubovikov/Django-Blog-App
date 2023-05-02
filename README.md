# Django-Blog-App

## Project description:

Blogs: posts, comments, recomendation/share emails, posts tagging, 

## Technologies used: 

* django
* custom queryset manager
* forms, templates
* pagination
* email senging
* django-taggit
* PostgreSQL

## How to run:

Run containers:

    docker-compose build
    docker-compose up

Run in docker:    

    python manage.py migrate
    python manage.py createsuperuser

Create posts, tags, comments, etc.


![image](https://github.com/DmitryDubovikov/Django-Blog-App/blob/main/blog.png)