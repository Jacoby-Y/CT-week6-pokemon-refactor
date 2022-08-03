## Coding Temple Week 6 Pokemon Project (But, its refactored)
###### CT-week6-pokemon-refactor

#### Env variables
```
FLASK_APP
FLASK_ENV
SECRET_KEY
SQLALCHEMY_DATABASE_URI
SQLALCHEMY_TRACK_MODIFICATIONS
```

#### Create Secret Key
```python
./$ python # or python3 on Unix systems
>>> import secrets
>>> secrets.token_urlsafe(50)
# Copy output and paste as value for SECRET_KEY
```

#### Run Instructions
`$ python -m venv venv` - (python3 on Unix systems)   
`$ . venv/bin/activate`   
`$ pip install -r requirements.txt`   
`$ flask run`   
