FROM python:3.10.6-slim-bullseye
# Install python packages
ARG VERSION
RUN pip install --no-cache mlflow==$VERSION
RUN pip install psycopg2-binary
