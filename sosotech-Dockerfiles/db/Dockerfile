FROM mysql:5.7.25
LABEL "Project"="sosoSQL"
LABEL "Author"="Cafanwi"

ENV MYSQL_ROOT_PASSWORD="sosotechdbpassword"
ENV MYSQL_DATABASE="accounts"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
