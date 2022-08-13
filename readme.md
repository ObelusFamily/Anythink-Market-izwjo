# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Run `docker-compose up`
2. Verify that everything's running
  a. Go to http://localhost:3000/api/ping and verify that the backend works. You should see a JSON response indicating that everything is okay.
  b. Go to http://localhost:3001/register and verify that the frontend works
3. Register for a user
