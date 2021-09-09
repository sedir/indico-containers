FROM getindico/indico:3.0

COPY ./app.py.patch /opt/indico/

RUN patch /opt/indico/.venv/lib/python3.9/site-packages/indico/web/flask/app.py -i /opt/indico/app.py.patch

