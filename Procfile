web: gunicorn LMS.asgi: application --log-file - --log-level debug
heroku ps:scale web=1
python manage.py migrate
