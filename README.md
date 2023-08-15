# docker-todo-app
A simple todo app built with django. This project is an implementation of how to deploy microservices in docker.

### Setup
To get this repository, run the following command inside your git-enabled terminal
```bash
$ git clone https://github.com/pythoner-code/docker-todo-app.git
```
You will need docker and docker-compose to be installed on your computer to run this app.
Once you have downloaded docker, go to the cloned repo directory and run the following command

```bash
$ docker-compose up -d
```

This will create two containers, one is for frontend and another one is a database container to store data even when the container is either stopped or killed or removed.

Once the app is hosted, head over to http://127.0.0.1:8000 for the App.
