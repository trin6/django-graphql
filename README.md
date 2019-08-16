# django-graphql

Sample demonstrating the minimum steps required to run a DJANGO, GRAPHQL project.

Initialize script used to generate boiler plate django project, branch compare MASTER and DEVELOP to view all steps neccessary to enable  GRAPHQL.

##Initialize

```shell script
python3 -m venv venv
. ./venv/bin/activate
pip install django

django-admin startproject graphproject
cd graphproject
django-admin startapp app

python manage.py makemigrations
python manage.py migrate
```