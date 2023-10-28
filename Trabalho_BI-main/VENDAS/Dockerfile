FROM mysql:8.0.16

ENV MYSQL_ROOT_PASSWORD 1234

#COPY ./dw.sql /docker-entrypoint-initdb.d/01-dw.sql
COPY ./Base-Vendas-2021.csv /docker-entrypoint-initdb.d/01-Base-Vendas-2021.csv
