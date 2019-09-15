FROM mysql/mysql-server:8.0.16

MAINTAINER pedroPolonea

ENV MYSQL_DATABASE=employees \
    MYSQL_ROOT_PASSWORD=root

#ADD schema.sql /docker-entrypoint-initdb.d
COPY ./sql-scripts/ /docker-entrypoint-initdb.d/

EXPOSE 3306