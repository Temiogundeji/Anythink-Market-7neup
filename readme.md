# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Intructions on How to Setup a Development Environment
This instruction assumes that you've approved a Github invite from AnyThink to be able to access the Project repository.

- Step 1:
Clone project repository to your local machine.
- Step 2:
Install [Docker]("https://docs.docker.com/get-docker/") desktop on your machine. To verify your Docker installation, enter these commands in your terminal: docker -v and docker-compose -v
- Step 3: 
Start your docker
- Step 4: 
Run docker-compose up from the project root directory to load Anythink's backend and frontend. If your Docker is working correctly, the backend should be running and able to connect to your local database.
- Step 5:
You are almost there, running this request: http://localhost:3000/api/ping in your browser should produce this response:
msg	"Pong! Seems like Everythink is working, great job!"
- Step 6: 
Now, check the frontend and make sure it’s connected to the backend. If everything is working fine, http://localhost:3001/register should lead you to the registration page.

Cheers!