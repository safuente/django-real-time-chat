# django-real-time-chat
A django real time chat using web sockets

## Run local environment

To run the container please execute the following command:

    make up

Once the command is executed in order to test it create two different users (executes twice):

    make superuser

You could log in the chat in http://localhost:8000/auth/login
You must open two different browser windows (e.g: Chrome and Safari), from each one log in with
the users created in the previous step and send a message to see the communication between the two users.

## Other useful commands

Build docker image

    make build

Stop containers

    make stop

Stop containers

    make stop

Delete containers

    make rm

Run unit tests

    make test

Run flake8 linter:

    make lint
