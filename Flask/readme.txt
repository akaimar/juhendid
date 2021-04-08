## INSTALLEERIMINE ##

1) Ava kataloog, kus arendus toimub
2) Paigaldan virtual env käsurealt $ python3 -m venv venv
3) Aktiveerin käsurealt venvi $ . venv/bin/activate
4) Installi hilisem Flask $ pip install Flask

## GUICKSTART & BULIT IN SERVER ##

# Käsurealt teen järgmised käsud
$ export FLASK_APP=app.py

# server käima
$ python -m flask run või $ flask run

# server käima Dja EBUG mode on, siis näeme iga kord muudatusi
$ FLASK_DEBUG=1 flask run

# Nüüd saab avada lehe browseris aadressil: http://127.0.0.1:5000/

## FLASK APP DEPLOYMENT ##

Juhend:
https://flask.palletsprojects.com/en/1.1.x/deploying/#deployment
