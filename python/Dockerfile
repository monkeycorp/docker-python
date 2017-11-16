FROM python:3
MAINTAINER Uriel Elias <urieleliasg@gmail.com>
 ENV PYTHONUNBUFFERED 1
 ARG INSTALL_APPLICATION_PATH=../
 RUN mkdir /code
 WORKDIR /code
 ADD requirements.txt /code/
 RUN pip install -r requirements.txt
#ADD ${INSTALL_APPLICATION_PATH} /code/
