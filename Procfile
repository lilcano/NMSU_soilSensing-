web: gunicorn config.wsgi:application
worker: celery worker --app=nmsoil.taskapp --loglevel=info
