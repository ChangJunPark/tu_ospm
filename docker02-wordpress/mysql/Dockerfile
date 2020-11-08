from mysql:5.7

volume /var/lib/mysql

env MYSQL_ALLOW_EMPTY_PASSWORD ture

expose 3306

add ./init.sql /docker-entrypoint-initdb.d/init.sql
