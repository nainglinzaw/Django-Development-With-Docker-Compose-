#Django Development With Docker Compose 
**Include**: 

- PostgreSQL 

- Django 

- Python

**Requirements**: 

- Django==3.0.5 

- psycopg2==2.8.5 

- Pillow==7.1.2 

- postgres==3.0.0

**Instruction**

*Start Docker Native Build images*

- docker-compose build 

*Create the database migrations* 

- docker-compose run web python manage.py migrate 

*Start services* 
- docker-compose up 

View in browser http://127.0.0.1:8000/