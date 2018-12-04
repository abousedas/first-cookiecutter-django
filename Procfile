web: gunicorn config.wsgi:application
worker: celery worker --app=my_awesome_project.taskapp --loglevel=info
