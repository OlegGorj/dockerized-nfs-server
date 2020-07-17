# Dockerized NFS Server

This will create an NFS Server and map ports on the host. Based on CentOS 7.

To run server:

`docker run -d --net=host --privileged --name nfs-server docker.io/oleggorj/dockerized-nfs-server /exports/docker-registry /exports/git`


---
