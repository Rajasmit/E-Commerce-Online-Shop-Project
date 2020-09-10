# E-Commerce Website

- clone the repository or download it to run it locally
- pip3 install pipenv to use virtual environment
- type the command to install all dependencies => pipenv install
- Prior to running the WebSite, you need rabbitmq server, you also need redis to be setup for recommendation engine
- have a breaintree sandbox account setup so that you may access the admin and setup the dummy data
- Input the Braintree settings information in the settings.py file
- type => pipenv shell
- type => python manage.py createsuperuser
- have a braintree account setup to manage payments.
- type => python manage.py makemigrations
- type => python manage.py migrate
- type => python manage.py runserver
