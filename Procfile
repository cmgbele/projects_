web: gunicorn -b "0.0.0.0:$PORT" -w 3 blog_api.wsgi  
release: python manage.py migrate
