# notes-app-back-end

### A Dicoding sample project

----------

To run the services (PostgreSQL): `docker-compose up`.

To use determined node version, run `nvm use`.

To run the node server in dev mode: `npm run start-dev`.

To run the node server in prod mode: `npm run start-prod`.

To run database migration:
   - `npm run migrate create ‘<migration name>’` to create new migration file.
   - `migrate up` to run up migration which has not been applied.
   - `migrate down` to run down migration from current state.
   - `migrate redo` to rerun previous migration (to run down migration, then up migration).
