FROM postgres:alpine

MAINTAINER Ben M <git@bmagg.com>

RUN echo "host all  all    0.0.0.0/0  md5" >> /var/lib/postgresql/data/pg_hba.conf 

CMD ["postgres"]

EXPOSE 5432