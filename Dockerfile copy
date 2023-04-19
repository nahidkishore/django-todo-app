FROM python:3
WORKDIR app
RUN pip install django==3.2

COPY . /app

RUN python manage.py migrate
EXPOSE 8000
CMD ["python","manage.py","runserver","0.0.0.0:8000"]


