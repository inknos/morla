# syntax=docker/dockerfile:1

FROM python:3.8-slim-buster

RUN pip3 install --upgrade pip

COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

RUN mkdir -p /etc/letsencrypt/gandi
