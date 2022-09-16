# Storefront Backend Project

## Setup And Connect To The Database

1. Create User On Database
   `CREATE USER admin WITH PASSWORD 'password';`

2. Create Dev Database
   `CREATE DATABASE store_dev;`

   - To Connect
     `\c store_dev`

3. Create Test Database
   `CREATE DATABASE store_test;`

   - To Connect
     `\c store_test`

## Prepare env

- add a `.env` file in the main directory

NODE_ENV=dev
POSTGRES_HOST=localhost
DB_PORT=5432
POSTGRES_DB=**\***
POSTGRES_TEST=**\***
POSTGRES_USER=**\***
POSTGRES_PASSWORD=**\***
BCRYPT_PASSWORD=**\***
SECRET_TOKEN=**\***
PEPER_PASSWORD=**\*\***

## To Start App

### Run

npm install && npm run start

## To Start Test

### Run

npm run test_db
