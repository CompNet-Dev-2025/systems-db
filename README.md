# systems-db
Contains schema, seed data, and scripts for the main system database.

## How to use for testing

1. git clone the repo, or git pull if already present
2. Install docker (if not already installed)
3. Copy .env.example to .env
4. Modify credentials in .env to suit your needs
3. `docker compose up -d --force-recreate`
4. Access the database by whatever postgres compatible client you see fit.

## If running only on localhost

`psql --host 127.0.0.1 -p 5432 --username username databasename -f init.sql`

Credentials are found in the env file.
