FROM python3

RUN apt-get update && apt install -y --no-install-recommends \
    git \
    wget \
    openjdk-11-jdk \
    python3 \
    && rm -rf /var/lib/apt/lists/*
RUN pip install django
COPY . /opt/source-code
ENTRYPOINT PYT_APP = /opt/source-code/manage.py django run
