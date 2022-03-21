FROM postgres:11.15-alpine3.15

RUN apk add --update htop

COPY ./setup-primary.sh /docker-entrypoint-initdb.d/setup-primary.sh

RUN chmod 0666 /docker-entrypoint-initdb.d/setup-primary.sh