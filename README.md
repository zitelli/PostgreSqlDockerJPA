
# Java: data persistence and queries with Spring Data JPA

Project developed in the second course of Alura's Advancing with Java training.

## 🔨 Project objectives

- Evolve in the Screenmatch project, started in the first training course, creating a menu with several options;
- Model application abstractions through classes, enums, attributes and methods;
- Consume the ChatGPT API (in this project we are not using ChatGPT, but the translation api at https://www.omdbapi.com/;
- Use Spring Data JPA to persist data in the database;
- Know various types of databases and use PostgreSQL via Docker Compose. Execute command in the project directory: docker compose up -d; Or to stop docker compose down;
- Work with various types of database queries;
- Dive deeper into the JPARepository interface

When assembling the project, you will need:
- create the directories: pgadmin_data, postgres_data, redis.conf, redis_data (this project is not using Redis yet)

When the project is running, the database can be consulted by pgadmin at the local address: http:\\localhost:16543

It is necessary to create a .env file in the project's local directory to maintain the API_KEY for accessing the API. Here's an example:

API_KEY = "&apikey=65xxxxxxxc"
