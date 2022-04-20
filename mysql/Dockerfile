FROM mysql:5.7

ENV MYSQL_DATABASE=bulletin_board \
  MYSQL_USER=dbadmin \
  MYSQL_PASSWORD=dbadmin \
  MYSQL_ROOT_PASSWORD=password \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf