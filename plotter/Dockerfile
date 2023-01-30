FROM python:3.11-slim-bullseye
RUN adduser --system  plotter

USER plotter

ENV PATH="/home/plotter/.local/bin:$PATH"

RUN pip install --upgrade pip && pip install \
  pandas \
  matplotlib \
  click

