## Description
pitchZone is an App that allows the user to pitch his/her idea be it business idea, politics etc and also allows the user to comment and rate pitched ideas from other different users. A user can choose different area or category to pitch his or her idea. These categories include:

    1. Interview
    2. Product
    3. Promotion
    4. Business
    5. Academic
    6. Political
    7. Technology
    8. Health

A user can select any of the categories from the navbar to view the pitches on these categories

Other users can give feedback to the pitch posts by commenting, liking or disliking the pitch. 



## Set-up and Installation

### Prerequiites
    - Python 3.6
    - Ubuntu software

### Clone the Repo
Run the following command on the terminal:
`git clone https://github.com/Matongo2010/pitchZone`

Install [Postgres](https://www.postgresql.org/download/)

### Create a Virtual Environment
Run the following commands in the same terminal:
`sudo apt-get install python3.6-venv`
`python3.6 -m venv virtual`
`source virtual/bin/activate`

### Install dependancies
Install dependancies that will create an environment for the app to run
`pip3 install -r requirements`

### Prepare environment variables
```bash
export DATABASE_URL='postgresql+psycopg2://username:password@localhost/pitchZone'
export SECRET_KEY='Your secret key'
```

### Run Database Migrations
```
python manage.py db init
python manage.py db migrate -m "initial migration"
python manage.py db upgrade
```

### Running the app in development
In the same terminal type:
`python3 manage.py server`

Open the browser on `http://localhost:5000/`

## Known bugs
SQLAlchemy errors, automatic sign out has a short time span

## Technologies used
    - Python 3.6
    - HTML
    - Bootstrap 4
    - Heroku
    - Postgresql

## Support and contact details
Contact me on developer.justineadriano638@gmail.com for any comments, reviews or advice.

### License
Copyright (c) ** Adriano Meroka **