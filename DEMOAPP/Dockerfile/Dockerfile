FROM python:3.6-slim
WORKDIR /DEMOAPP
RUN pip install --upgrade pip
COPY requirements.txt /DEMOAPP

RUN pip install -r requirements.txt
COPY . /code/

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
