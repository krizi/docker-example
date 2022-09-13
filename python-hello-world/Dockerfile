FROM python:3.9.14-slim

RUN mkdir /app

COPY requirements.txt /app
COPY run.py /app

WORKDIR /app

RUN pip install -r requirements.txt

CMD python run.py