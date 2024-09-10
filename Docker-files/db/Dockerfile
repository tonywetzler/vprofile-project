FROM mysql:8.0.33
LABEL "project"="Vprofile"
LABEL "Author"="Imran"

ENV MYSQL-ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb/db_backup.sql