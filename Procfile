web: gunicorn config.wsgi:application
worker: celery worker --app=atenea.taskapp --loglevel=info
