FROM  mysql:5.7.37
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="account"
ADD db_back.sql  docker-entrypoint-initdb.d/db_backup.sql
LABEL "Authur"="Atal"
LABEL "Project"="Atal_project"