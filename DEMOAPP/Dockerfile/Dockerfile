FROM python3

WORKDIR /app

COPY . /app
RUN pip3 install django

COPY . .

CMD [ "python3", "-m" , "django", "run", "--host=0.0.0.147" ]