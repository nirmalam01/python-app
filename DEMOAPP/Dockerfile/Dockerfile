FROM python3
RUN apt update && apt-get install python3
RUN pip install django
COPY . /opt/source-code
ENTRYPOINT PYT_APP = /opt/source-code/manage.py django run
