1.What is the difference between `docker run` and `docker start`?

`docker run` creates and starts a new container from an image. `docker start` starts an already created (but stopped) container.

2.What’s the difference between interactive and detached mode?

Interactive mode (`-it`) connects your terminal to the container for direct input/output. Detached mode (`-d`) runs the container in the background.

3.How do you check the logs of a container?

Use `docker logs <container>` to view stdout and stderr output from the container.

4.What does `docker ps -a` show that `docker ps` does not?

`docker ps -a` lists all containers, including stopped ones. `docker ps` only shows currently running containers.

5.How do you remove a Docker image?

Use `docker rmi <image_name_or_id>` to delete an image from your local system.

6.How can you execute a shell command inside a running container?

`docker exec -it <container> <command>` lets you run a command like `, `sh`, or any utility inside the container.

7.How can you restart a container without deleting it?

Use `docker restart <container_name_or_id>` to stop and start the container again with the same configuration.
