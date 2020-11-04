# Docker files Installation Guide

_The Folder Test1 Contains Docker File for Installation of Python._

Firstly build the Docker image by

```
$docker build .
```

Then run it by

```
$ sudo docker run -it <imagename>
```

_The floder Tomcat contains docker file of installtion of tomcat._

Similar to above build the docker image and then run it

```
$ docker run -d -p 8080:8080 <image_id>
```

Check it by

```
$ curl http://localhost:8080
```

*The folder DockerCompose conatains two different docker file *one* and *two\* which can be composed using an yml file.

_Also if in case you want to run a application on your AWS Instance you can do it by creating a GUI._

Refer for installation details here [HERE](https://ubuntu.com/tutorials/ubuntu-desktop-aws#3-configuring-the-vnc-server)
