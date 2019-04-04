# Allscripts_internship_app

This is my web app for the Allscripts internship application

## Local testing ##
Install dependencies
```bash
pip install -r requirements.txt
```
Initialize sqlite database and create tables
```bash
flask db init
flask db migrate
flask db upgrade
```
The database will be empty, populate it with test data using
```
python insert_db.py
```

Start application with
```bash
flask run
```


