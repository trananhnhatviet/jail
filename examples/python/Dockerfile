FROM python:slim AS app
RUN pip install --no-cache-dir progress

COPY multiply.py /srv/app/run
ENV JAIL_MEM=20M JAIL_POW=5000 JAIL_ENV_NUM=5
