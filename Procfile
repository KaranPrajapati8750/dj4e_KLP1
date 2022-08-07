web: gunicorn dj4e_KLP1.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate