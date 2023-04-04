# docker_project
Containerize/Integrate Microservices using Docker

The Ops teams have pointed out that it takes a lot of time to deal with packages (for this project: Redis and Python) because they require OS dependencies that have to be reinstalled every time a component's version is upgraded. On the other hand, the Dev team has raised concerns that they have a lot of trouble installing and configuring the application in their local environments because the procedure differs depending on the OS system they use. 

To fix these problems we have decided to migrate our applications to Docker. To do so, some scripts (to run our application) as well as a file (readme) has been provided. We are going to use Docker Compose to execute a single command to bring all the containers up/down.
