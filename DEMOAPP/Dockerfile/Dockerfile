FROM python:3.8-slim-buster

WORKDIR /app

COPY . /app
RUN pip3 install django

COPY . .

CMD [ "python3", "-m" , "django", "run", "--host=0.0.0.147"]