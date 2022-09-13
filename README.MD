# Tasks
## verify to pull images from Dockerhub
Command: `hello-world`

```
docker pull hello-world                                                                                                                                   git:(master|) 
Using default tag: latest
latest: Pulling from library/hello-world
2db29710123e: Pull complete 
Digest: sha256:7d246653d0511db2a6b2e0436cfd0e52ac8c066000264b3ce63331ac66dca625
Status: Downloaded newer image for hello-world:latest
docker.io/library/hello-world:latest
```
## verify run images
Command: `docker run hello-world`
```

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

```
## list local images
Command: `docker images`
```                                                                                                                                          git:(master|✚1 
REPOSITORY                                  TAG               IMAGE ID       CREATED         SIZE
hello-world                                 latest            feb5d9fea6a5   11 months ago   13.3kB
```