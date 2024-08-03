FROM postgres:16-alpine

WORKDIR /db

ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=root
ENV POSTGRES_DB=TicketDesk

RUN mkdir docker-entrypoint-initdb.d

COPY . /docker-entrypoint-initdb.d

EXPOSE 5432