FROM python:3.9-alpine

WORKDIR /app

COPY ./app /app

RUN pip install --upgrade pip

RUN pip install flask

CMD ["python", "app.py"]
