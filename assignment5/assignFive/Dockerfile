FROM mysql
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=mydb
COPY mydb.sql /docker-entrypoint-initdb.d/
