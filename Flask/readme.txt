## SISUKORD ##
1. INSTALLEERIMINE
2. KÄIVITAMINE


## 1. INSTALLEERIMINE ##

1) Paigaldan virtual env käsurealt $ python3 -m venv myapp // see teeb virtual environment kausta
2) Lähen sellesse kausta $ cd myapp
3) Aktiveerin käsurealt venvi $ source bin/activate
4) Installi Flaski dependecy-d $ pip install Flask
6) Installi formid $ pip install flask_wtf ja $ pip install wtforms
5) Et environmentist välja minna $ deactivate

## LOO JÄRGMISED FAILID JA sinna import ##

app.py

from flask import Flask, render_template, request

app = Flask(__name__)
app.config['SECRET_KEY'] = 'mysecret'

@app.route('/', methods=["GET", "POST"])
def index():
    return "Hello world"

## GUICKSTART & BULIT IN SERVER ##

# server käima
$ python -m flask run või $ flask run

# server käima ja EBUG mode on, siis näeme iga peale igat refreshi muudatusi
$ FLASK_DEBUG=1 flask run

# server käima ja automaatne reload peale muudatust
$ FLASK_APP=app.py FLASK_ENV=development flask run

# Nüüd saab avada lehe browseris aadressil: http://127.0.0.1:5000/

## FLASK APP DEPLOYMENT ##

Juhend:
https://flask.palletsprojects.com/en/1.1.x/deploying/#deployment


## 2. KÄIVITAMINE ##

1) Mine kausta, kus asub app.py
2) Aktiveerin käsurealt venvi $ source bin/activate
3) Käivitan flaski $ python -m flask run
4) Nüüd saab avada lehe browseris aadressil: http://127.0.0.1:5000/
