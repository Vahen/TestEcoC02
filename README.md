# Django_test

## Create and run the virtual environnement
 * Run the command `python -m venv <path to venv>`
 * For example `python -m venv venv`
 * You need to activate the venv by using:
 * `source venv/bin/activate` on Linux
 * `venv\Scripts\activate` on Windows command prompt (There is only 1 backslash, somehow markdown writes 2 of them)

## Database
If the database doesn't exist, you will need to run the following commands:
 * `python manage.py makemigrations app` (for the app named app)
 * `python manage.py migrate` (you can also migrate only the app stuff by appending "app" to the command)


## How to run the api :
 * `python manage.py runserver 8000`

## How to run the tests :
 * `python manage.py test`

## Access the webpage:
 * Go to your browser and tip `http://127.0.0.1:8000/`, if you started you server on the same computer as your browser

