FROM mysql:5.7

RUN echo '!includedir /etc/mysql/conf.d/' > /etc/my.cnf
COPY ./conf/ /etc/mysql/conf.d/

VOLUME /var/lib/mysql
VOLUME /var/log/mysql

CMD [ "mysqld" ]
