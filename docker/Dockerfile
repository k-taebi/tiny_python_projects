FROM python:3.8.3-buster
RUN apt-get -y update

WORKDIR /app
COPY ../requirements.txt /app/requirements.txt

RUN python3 -m pip install -r requirements.txt

CMD ["python3", "--version"]
