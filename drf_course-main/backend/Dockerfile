FROM python:3.10-slim

USER root

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y netcat gettext && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
