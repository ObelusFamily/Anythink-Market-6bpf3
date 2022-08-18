# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker on your machine.

2. Verify that Docker is installed by running `docker -v` and `docker-compose -v`.

3. Git clone the repo.

4. Make sure to checkout a new branch. You can do so by typing `git chechout -b branchName` in the root folder.

5. Finally, run `docker-compose up` from the project root directory.

6. After the docker container installation & setup you should be able to check backend by going to
   `http://localhost:3000/api/ping`.

7. Once that working, head over to `http://localhost:3001/register` to create a new user!
