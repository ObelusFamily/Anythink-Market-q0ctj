# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?

- Go to your cloned repo and create the project docker containers with `docker-compose up', it should take a while.
- When is finished go to your browser at http://localhost:3000/api/ping if there is an error with backend migrations, click in run migration in the browser, it should fix it.
- Now go to  http://localhost:3001/register and create your user.