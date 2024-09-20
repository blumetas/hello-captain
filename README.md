# Docker "Hello, Captain!" project

## Project information

### Project URL

This project is a community solution for "Basic Dockerfile" from **roadmap.sh**. You can find project details [here](https://roadmap.sh/projects/basic-dockerfile).

### Project installation

To install and run this image, you will needed **Docker CLI**, to install it click [here](https://docs.docker.com/get-started/get-docker/). Follow these steps to install and run this image:

- ### Clone repository

````sh
$ git clone https://github.com/artem-lip/hello-captain hello-captain
````

- ### Build image

````sh
$ cd hello-captain
$ sudo docker build -t hello-captain .
````

- ### Run container

````sh
$ sudo docker run hello-captain
````

- ### Output

````
Hello, captain!
````