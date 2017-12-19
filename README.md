# Contacts Snapshot starter project

## Dev Setup

1. Create your database: `createdb contacts_development`
1. Load your database with the schema: `npm run load_schema`
1. Install your dependencies: `npm install`
1. Run the server: `nodemon`

## TODO
- [X] create a migration config, which contains the config for test, development and production environments.
- [X] add to the config in a way that I can use SQL files.
- [ ] add a migration to transpose the 'schema.sql' file into a migration (init migration)
- [ ] run 'db-migrate' using the config file, to see if things work.
