# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_


Installing Docker Desktop in Windows home was a hard task. The first approach is to follow the standard installation instructions being aware of:
- Enabling hardware virtualization in your BIOS
- Being sure that hyper-v is enabled 
Because of my windows edition, I needed to manually install Hyper-V and also had to install Ubuntu within WSL2 to have it up and running.
Finally it is needed to run the command docker-compose up within the directory of the cloned project.