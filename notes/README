# Docker
## Image & Important commands.. 
### Docker Image:
Docker images are read-only templates that contain instructions for creating a container. 
Or
A Docker image is a snapshot or blueprint of the libraries and dependencies required inside a container for an application to run.
### How to write one:
The contents of the Dockerfile depend on the image it describes. You can open your preferred IDE (such as VS Code) and create a new file named Dockerfile at the root level of your project directory. The file should have no file extension.
Now to write one you can use the commands as follows:
FROM python:3.11  
	Here ‘FROM’ is used to describe source  for base image as we can see ‘python:3.11’ is used as source of the  base image.  
RUN echo hello world!
	Here ‘RUN’ is used to run and execute a command you can also used it to install packages or update your image.
WORKDIR relative/path/of/working/directory
	Here ‘WORKDIR’ give directions towards the working directory. 
 USER user1
	Here ‘USER’ is to specify which user will be using this file. Either it could be root or you can specify as per you like.
SHELL [‘pwsh’,’command’]
	Here ‘SHELL’ is used to run commands in shell

RUN “hello” | out-file – path /demo/message.txt|
	Now here when you this run this command under shell, you’ll see ‘messagge.txt’ file getting created with hello written inside.
ENV app_hosts=’0.0.0.0/0’
	Here ‘ENV’  is used to declare environmental variable in your dockerfile.
COPY app.py /code/file.txt
	This command helps you in copying everything from source(app.py) to destination(/code/file.txt)
ADD <linkofanypakageyouwantoinstall>
This command is similar to COPY command but here you can also add link to download packages. 
ENTRYPOINT [‘npm’,’cmd’]
	Defines the executable that will always run when the container starts. Cannot be easily overridden when running the container (unless using the --entrypoint flag).
CMD ["apache2ctl", "-DFOREGROUND"]
	Provides default arguments for the ENTRYPOINT. Can be easily overridden when running the container using command line arguments.

### DOCKER COMMANDS ( MUST KNOW COMMANDS)
o	Docker build: Creates an image from a Dockerfile.
	Syntax: docker build [OPTIONS] PATH | URL | -

o	Docker run: Runs a command in a new container.
	Syntax: docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

o	Docker info: Displays system-wide information about Docker.
	Syntax: docker info

o	Docker search: Searches the Docker Hub for images.
	Syntax: docker search [OPTIONS] TERM


o	Docker logs: Fetches the logs of a container.
	Syntax: docker logs [OPTIONS] CONTAINER

o	Docker ps -a: Lists all containers, including stopped ones.
	Syntax: docker ps –a

o	Docker images: Lists all images on the local system.
	Syntax: docker images [OPTIONS] [REPOSITORY[:TAG]]

o	Docker pull: Pulls an image or a repository from a registry.
	Syntax: docker pull [OPTIONS] NAME[:TAG|@DIGEST]

o	Docker tag: Creates a tag for an image.
	Syntax: docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]

o	Docker push: Pushes an image or a repository to a registry.
	Syntax: docker push [OPTIONS] NAME[:TAG]

o	Docker history: Shows the history of an image.
	Syntax: docker history [OPTIONS] IMAGE

o	Docker exec: Runs a command in a running container.
	Syntax: docker exec [OPTIONS] CONTAINER COMMAND [ARG...]

o	Docker kill: Kills a running container.
	Syntax: docker kill [OPTIONS] CONTAINER [CONTAINER...]

o	Docker stop: Stops one or more running containers.
	Syntax: docker stop [OPTIONS] CONTAINER [CONTAINER...]

o	Docker network: Manages Docker networks.
	Syntax: docker network COMMAND

o	Docker login: Logs into a Docker registry.
	Syntax: docker login [OPTIONS] [SERVER]

o	Docker rmi: Removes one or more images.
	Syntax: docker rmi [OPTIONS] IMAGE [IMAGE...]

o	Docker rm: Removes one or more containers.
	Syntax: docker rm [OPTIONS] CONTAINER [CONTAINER...]
