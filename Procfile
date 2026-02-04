release: python manage.py migrate --noinput && python manage.py collectstatic --noinput
web: gunicorn dragronball2.wsgi:application --bind 0.0.0.0:$PORT