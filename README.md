# Installation

npm init 
-- creates package.json

npm intall knex
-- installs knex dependency to interface with pg db

npm install express 
-- install express.js lib

npm install pg 
-- installs pg interface for knex and psql

cat package.json 
-- verify dependecies have been added

npm knex init 
-- creates knexfile.js
-- make sure knexfile.js has development environment info. 

```
        module.exports = {

        development: {
            client: 'postgresql',
            connection: {
            database: 'northwind',
            user:     'postgres',
            password: 'Longbow15Y'
            },
            pool: {
            min: 2,
            max: 10
            },
            migrations: {
            tableName: 'knex_migrations'
            }
        }

        };
```






