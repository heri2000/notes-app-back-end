# notes-app-back-end

To run the services (PostgreSQL): `docker-compose up`

To run the node server: `npm run start-dev`

To run database migration:
   - `npm run migrate create ‘<migration name>’` to create new migration file.
   - `migrate up` to run up migration which has not been applied.
   - `migrate down` to run down migration from current state.
   - `migrate redo` to rerun previous migration (to run down migration, then up migration).
