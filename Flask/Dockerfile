FROM cgr.dev/chainguard/python:latest  AS base

#RUN  install --upgrade pip



COPY . /docker-flask/
WORKDIR /docker-flask

RUN install -r requirements.txt

CMD ["python", "app.py"]