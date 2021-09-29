release: python manage.py makemigrations viajes reservas usuarios vehiculos
release: python manage.py migrate


web: gunicorn reito.wsgi --log-file -