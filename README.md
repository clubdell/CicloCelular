# Ciclo celular

**Important**: It's recommended you use a linux or another unix system that already have installed python and pip to make this easier.

1. Open a terminal
2. Install virtualenv `pip install virtualenv`
3. Create the virtualenv for your python projects `virtualenv <name>`
4. In your terminal navigate to the virtualenv folder `cd <name>`
5. Start the virtualenv `source bin/activate`
6. Clone this repository
7. `cd ciclocelular` and install the dependencies `pip install -r requeriments.txt`
8. `cp ciclocelular/local_settings.py.example ciclocelular.py`
9. Configure your database system settings in `local_settings.py`
10. Run `python manage.py makemigrations` `python manage.py migrate`
11. Create the superuser `python manage.py createsuperuser`
12. Run the local server `python manage.py runserver <PORT>`

**Warning:** In case the mysql package for python gives you an error execute
`sudo apt-get install mysql-server libmysqlclient-dev`
