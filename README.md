# systems-db
Contains schema, seed data, and scripts for the main system database.

## How to use for testing

1. git pull the repo to ensure you have the latest code
2. Install docker (if not already installed)
3. `docker compose up -d`
4. Access the database by whatever postgres compatible client you see fit.

## If running only on localhost

psql --host 127.0.0.1 -p 5432 --username CIMS_DB CIMS -f init.sql

Credentials are found in the docker-compose file.
