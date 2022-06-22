# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## setting up an env

Make sure you have docker installed.

Once that's done, run `docker-compose up`

check the backend is working by going to `http://localhost:3000/api/ping`

check that the frontend is connected and working by going to `http://localhost:3001/register` and creating a new user