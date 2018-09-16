FROM python:3

RUN apt-get update

WORKDIR /usr/src/app

COPY . /usr/src/app

RUN pip install --no-cache-dir -r requirements.txt

CMD [ "python", "./app.py" ]

EXPOSE 5000