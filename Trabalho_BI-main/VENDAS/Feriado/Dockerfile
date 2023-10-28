FROM mysql:8.0.16

ENV MYSQL_ROOT_PASSWORD 1234

COPY ./schema_feriado_EUA.sql /docker-entrypoint-initdb.d/01-schema_feriado_EUA.sql
COPY ./data_feriado_EUA.sql /docker-entrypoint-initdb.d/02-data_feriado_EUA.sql