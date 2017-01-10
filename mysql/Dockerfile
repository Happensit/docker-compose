FROM mysql:5.7

ADD startup /etc/mysql/startup

RUN chown -R mysql:root /var/lib/mysql/

ADD my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld", "--init-file=/etc/mysql/startup"]

EXPOSE 3306
