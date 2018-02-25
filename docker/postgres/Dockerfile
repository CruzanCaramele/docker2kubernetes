FROM postgres:9.6
LABEL maintainer="letters2hamza@gmail.com"
EXPOSE 5432
COPY seed.sql /docker-entrypoint-initdb.d/
VOLUME /var/lib/postgres/data  