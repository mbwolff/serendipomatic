
Installation
-------------

Install pip if you don't have it:
easy_install pip (or sudo easy_install pip)

(sudo) pip install -r requirements.txt

open question: do we want to use virtualenv?

Make a copy of smartstash/localsettings.py.dist named smartstash/localsettings.py
and fill in any required settings:
SECRET_KEY: generate one at http://www.miniwebtool.com/django-secret-key-generator/
API_KEY: use 880a57b8031d34448691aafe881cfd2f

Add new python dependencies to requirements.txt as needed.


To start the local dev server:

python manage.py runserver

