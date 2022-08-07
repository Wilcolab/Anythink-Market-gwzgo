# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Follow the steps below to install and run this repo on your local machine.

1. [Install GitHub desktop](https://desktop.github.com/) (if you are lost, read more instructions [here](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop))
2. [Clone this repo from your GitHub desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop)
3. [Install Docker Desktop](https://docs.docker.com/get-docker/)
4. [Open a terminal on your local repo folder](https://www.groovypost.com/howto/open-command-window-terminal-window-specific-folder-windows-mac-linux/)
5. Verify if docker is ready by running the following commands at your terminal: `docker -v` then `docker-compose -v`  
    - You'll be ready if you are able to see a printed version on each command. If not, try [troubleshooting](https://docs.docker.com/desktop/troubleshoot/overview/)
6. Run `docker-compose up` (you should be on the project root directory)


After finished, let's test

1. The **backend**: opening <http://localhost:3000/api/ping> on your browser
2. The **frontend**: creating a new user on <http://localhost:3001/register>
