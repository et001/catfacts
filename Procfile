web: python catfacts/manage.py collectstatic --noinput
web: python catfacts/manage.py run_gunicorn
celeryd: python catfacts/manage.py celeryd -E -B --loglevel=INFO
