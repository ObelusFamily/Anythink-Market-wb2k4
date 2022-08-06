# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Use command `docker-compose up` from your root directory to run the docker container. Try pinging [Backend](http://localhost:3000/api/ping) and [Frontend](http://localhost:3001/register) and check ifyou are able to get any output. Also it would be better if you create your own user account by providing the credentials in the Frontend.
