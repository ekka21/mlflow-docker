FROM python:3.7.9-slim

ADD . /app
WORKDIR /app

COPY wait-for-it.sh wait-for-it.sh 
RUN chmod +x wait-for-it.sh

RUN pip install mlflow boto3 psycopg2-binary

