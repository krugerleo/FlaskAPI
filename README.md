# FlaskAPI
REST API With Flask & SQL Alchemy

Quick Start:

```bash
# Dependencies

pip install flask
pip install flask-marshmallow
pip install flask-sqlalchemy

# Create DB
$ python
>> from app import db
>> db.create_all()
>> exit()

# Run Server (http://localhst:5000)
python app.py
```

## Endpoints

* GET     /product
* GET     /product/:id
* POST    /product
* PUT     /product/:id
* DELETE  /product/:id