FROM python:3.7.2-stretch

ENV APP_DIR /app

WORKDIR $APP_DIR
COPY . $APP_DIR
RUN pip install -r requirements.txt

#Comando para iniciar el uWSGI
CMD ["uwsgi", "app.ini"]
