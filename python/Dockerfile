FROM python:latest
LABEL "Author"="Justine Brun brunjustin@eisti.eu"
WORKDIR /app

ADD requirements.txt /app/requirements.txt
RUN pip install -r requirements.txt

ADD app.py /app/app.py

ENV FLASK_ENV=development

EXPOSE 80

CMD ["python","app.py"]
