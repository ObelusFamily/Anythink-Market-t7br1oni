# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1) Clone the repo
2) Run `docker-compose up`
3) Visit the server running on port 3000 with path /api/ping to check the backend is running
4) Visit the server running on port 3001 with path /register to create a new user to check frontend and backend are connected
