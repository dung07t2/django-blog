web: python ./manage.py collectstatic --noinput; gunicorn blogproject.wsgi --log-file - 
ps:scale web=1
config:set DISABLE_COLLECTSTATIC=1