ubuntu-sshd
===========

ubuntu-14.04-with-SSHD-installed base image for Docker.

## Usage

Run a container:

```
$ sudo docker run gedex/ubuntu-sshd
```

Get the IP Address of the running container:

```
$ sudo docker inspect -f '{{ .NetworkSettigs.IPAddress }}' CONTAINER
172.17.0.8
```

SSH into the running container:

```
$ ssh root@172.17.0.8
```

## username:password

`root:root`
