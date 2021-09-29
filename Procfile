release: python manage.py makemigrations reservas
release: python manage.py makemigrations usuarios
release: python manage.py makemigrations vehiculos
release: python manage.py makemigrations viajes
release: python manage.py migrate
release: python script_destinos.py


web: gunicorn reito.wsgi