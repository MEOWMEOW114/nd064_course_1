FROM python:3.8.2-slim-buster

COPY . /app

WORKDIR /app

RUN pip install -r requirements.txt

RUN python3 init_db.py

EXPOSE 3111

CMD [ "python3", "app.py" ]

