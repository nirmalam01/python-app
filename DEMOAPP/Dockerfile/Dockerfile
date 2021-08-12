FROM python3
RUN apt-get-update && apt-get -y install python3
RUN pip install django
COPY . /opt/source-code
ENTRYPOINT PYT_APP = /opt/source-code/manage.py django run