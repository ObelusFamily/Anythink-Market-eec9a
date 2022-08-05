# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. make sure docker is installed on your machine
2. run `docker-compose up` from the project root directory to load backend and frontend
3. make sure backend is running correctly by pointing your browser to  http://localhost:3000/api/ping
4. make sure frontend is working correcly and [create new user](http://localhost:3001/register)
