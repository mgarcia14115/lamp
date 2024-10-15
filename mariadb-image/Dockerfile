FROM mariadb:latest

ENV MARIADB_ROOT_PASSWORD password
ENV MARIADB_DATABASE MYDB

COPY ./scripts/ /docker-entrypoint-initdb.d/
