FROM postgres:9.6
LABEL maintainer="youremail  @gmail.com"
EXPOSE 5432
COPY seed.sql /docker-entrypoint-initdb.d/
RUN mkdir -p /data/db
VOLUME /data/db