# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Create a folder for the project and enter it

```bash
mkdir <folder_name> && cd <folder_name>
```

2. clone the repo

```bash
    git clone <project_url>
```

3. intall docker [link](https://docs.docker.com/get-docker/)
4. check docker and docker-compose versions

```bash
docker -v
docker-compose -v
```

5. If the installation is ok - run docker

```bash
docker-compose up
```

6. Open [backend](http://localhost:3000/api/ping) and the [frontend](http://localhost:3001/register)
