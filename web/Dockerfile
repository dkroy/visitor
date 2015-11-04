# start with a base image
FROM ubuntu:14.04

# install dependencies
RUN apt-get -y update
RUN apt-get install -y python python-dev python-pip python-psycopg2
RUN apt-get install -y nginx supervisor

ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt
CMD python app.py
