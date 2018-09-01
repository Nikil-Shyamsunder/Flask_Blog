# Flask_Blog
Flask Blog Demo

## Install Flask:
```shell 
$ pip install flask 
```
Basic Code:
from flask import Flask 
app = Flask(__name__)

@app.route("/")
def hello_world:
  return "hello world"

export FLASK_APP "flaskblog.py"
$ flask run

## debug mode
exort FLASK_DEBUG = 1

