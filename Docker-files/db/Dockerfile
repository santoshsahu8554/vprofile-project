FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "AUthor"="santosh8554"

ENV MySQL_ROOT_PASSWORD="vprodpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb/db_backup.sql
