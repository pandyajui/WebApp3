FROM python:3.8

EXPOSE 5000

WORKDIR /app

COPY requirements.txt /app
run pip install -r requirements.txt

COPY . /app

CMD python app.py
