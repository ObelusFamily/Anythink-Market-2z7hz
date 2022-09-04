# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 09/04/2022 @SD-13]:** Follow the steps to build the setup locally

1. Clone the repo by using this command

    > git clone <https://github.com/ObelusFamily/Anythink-Market-2z7hz.git>

2. Get into the cloned repo

    > cd Anythink-Market-2z7hz

3. Install docker (I am using Ubuntu:22.04, so I used the below command)

    > sudo apt install docker
Use the [Official documentation](https://docs.docker.com/get-docker/) to install in other OS

4. Install the docker-compose plugin to run docker from files. For Ubuntu, I used the below command

    > sudo apt install docker-compose

    Checkout [this Doc](https://docs.docker.com/compose/install/) for other OS.

5. Make sure you are in the cloned repo and run
    > docker-compose up

Yuhooo🥳🥳, AWESOME!! You did it.

Now checkout your localhost in the respective ports to see them in action.
