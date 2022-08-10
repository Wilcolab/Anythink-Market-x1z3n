# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**Local Environment**
1. Make a clone of this repo.
2. [Install Docker](https://docs.docker.com/get-docker/)
3. In terminal run commands `Docker -v` and `docker-compose -v` to verify install.
4. In the project's root directory run `docker-compose up` to load Anythink's backend and frontend.
5. Open http://localhost:3000/api/ping to test the backend.
6. Open http://localhost:3001/register and create an account.
