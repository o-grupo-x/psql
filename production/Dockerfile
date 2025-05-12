FROM postgres:16

ENV POSTGRES_USER=postgres

ENV POSTGRES_PASSWORD=Vkhn2W3LudKzzis

ENV POSTGRES_DB=app_presente

EXPOSE 5432

WORKDIR /app

COPY ./init/ /docker-entrypoint-initdb.d/

VOLUME /var/lib/postgresql/data