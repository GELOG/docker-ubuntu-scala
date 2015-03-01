# Supported tags and respective `Dockerfile` links
- [`2.11.5`/Dockerfile](https://github.com/GELOG/docker-ubuntu-scala/tree/2.11.5/Dockerfile)
- [`2.11.4`/Dockerfile](https://github.com/GELOG/docker-ubuntu-scala/tree/2.11.4/Dockerfile)
- [`2.11.2`/Dockerfile](https://github.com/GELOG/docker-ubuntu-scala/tree/2.11.2/Dockerfile)
- [`2.11.1`/Dockerfile](https://github.com/GELOG/docker-ubuntu-scala/tree/2.11.1/Dockerfile)
- [`2.11.0`/Dockerfile](https://github.com/GELOG/docker-ubuntu-scala/tree/2.11.0/Dockerfile)
- [`2.10.4`/Dockerfile](https://github.com/GELOG/docker-ubuntu-scala/tree/2.10.4/Dockerfile)

# What is Scala?
Scala is a modern multi-paradigm programming language designed to express common programming patterns in a concise, elegant, and type-safe way. It smoothly integrates features of object-oriented and functional languages.

[http://docs.scala-lang.org/tutorials/tour/tour-of-scala.html](http://docs.scala-lang.org/tutorials/tour/tour-of-scala.html)

# What is Docker?
Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications. Consisting of Docker Engine, a portable, lightweight runtime and packaging tool, and Docker Hub, a cloud service for sharing applications and automating workflows, Docker enables apps to be quickly assembled from components and eliminates the friction between development, QA, and production environments. As a result, IT can ship faster and run the same app, unchanged, on laptops, data center VMs, and any cloud.

[https://www.docker.com/whatisdocker/](https://www.docker.com/whatisdocker/)

## What is a Docker Image?
Docker images are the basis of containers. Images are read-only, while containers are writeable. Only the containers can be executed by the operating system.

[https://docs.docker.com/terms/image/](https://docs.docker.com/terms/image/)

# Dependencies
* [Install Docker](https://docs.docker.com/installation/)

# Base Docker image
* [gelog/java:oraclejdk7](https://registry.hub.docker.com/u/gelog/java/)

# How to use this image?

    docker run --rm -ti gelog/scala:2.10.4
