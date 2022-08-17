# hosted https://fcc-learn-flask-crud.herokuapp.com/

# How to init the db
    1. >> 'python3', to enter python 3 shell
    2. >> 'from app import db', import the db into our interactive shell
    3. >> 'db.create_all(), that will create the db. 
    4. >> 'exit()

# how to host on heroku
    1. git init the project
    2. pip3 install guniorn
    3. pip3 freeze > requirements.txt
    4. touch Profile. Inside procfile 'web: gunicorn app:app'
    5. heroku login
    6. heroku create project-name
    7.git add & commit
    8. git push heroku master
