# Msterkey Django App
A simple ecommerce web app api with django and Mysql.
**Initial Setup**

    mkdir MK_Tech
    cd MK-Tech
    git clone https://github.com/samsmusa/MK-Tech.git
    pipenv install
   create .env file with .env_example and put all credential as like as .env_example
   then,
   

    pipenv shell
    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser
   after create super user, then
   

    python manage.py runserver

open browser and goto default localhos with port 8000

    http://127.0.0.1:8000/api-doc/
  here, you can find all api end-point documentation.
  at first, create a admin user
  and login admin user with Api endpoint. copy access token from response.
  after create, authorize swagger api with access token.\
  
