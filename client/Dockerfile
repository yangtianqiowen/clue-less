FROM python:alpine

EXPOSE 6000

WORKDIR /
ADD ./core /core
ADD ./client /client

ENV PYTHONPATH="$PYTHONPATH:/core"

RUN pip install flask
RUN pip install requests
RUN pip install attrs
RUN pip install networkx
