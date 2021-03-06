# Notes

The first thing I've clearly noted by digging through some websites is that docker is designed to run an isolated process in its own container. It's not really a replacement for a VM environment; instead you want to carefully package up single processes/applications (i.e. web servers) and start them within a container. You can then interact with them in a number of ways (i.e. via network).

Installing SSH and SSHing into a container is an anti-pattern, unless the point of the container is to host an SSH server. Now this doesn't mean you can't do it, but it adds an additional layer of vulnerability and configuration.

Using the `volume` mappings is important; this is one good way to communicate in and out of a container.

## Useful commands

Delete all containers - `docker rm $(docker ps -a -q)`

Delete all images - `docker rmi $(docker images -q)`

## Kaggal Tutorial
Walking through a tutorial (here)[http://blog.kaggle.com/2016/02/05/how-to-get-started-with-data-science-in-containers/] to try to start up a "data science" docker container. Some interesting notes (based on my work Mac).

- The default docker installation creates a VM to run your containers in. But it is small. You can create a bigger one. `docker-machine` can create a bigger one.

~~~
R0223760:~ m134910$ docker-machine create -d virtualbox --virtualbox-disk-size "50000" --virtualbox-cpu-count "2" --virtualbox-memory "4096" docker-test
Running pre-create checks...
Creating machine...
(docker-test) Copying /Users/m134910/.docker/machine/cache/boot2docker.iso to /Users/m134910/.docker/machine/machines/docker-test/boot2docker.iso...
(docker-test) Creating VirtualBox VM...
(docker-test) Creating SSH key...
(docker-test) Starting the VM...
(docker-test) Check network to re-create if needed...
(docker-test) Waiting for an IP...
Waiting for machine to be running, this may take a few minutes...
Detecting operating system of created instance...
Waiting for SSH to be available...
Detecting the provisioner...
Provisioning with boot2docker...
Copying certs to the local machine directory...
Copying certs to the remote machine...
Setting Docker configuration on the remote daemon...
Checking connection to Docker...
Docker is up and running!
To see how to connect your Docker Client to the Docker Engine running on this virtual machine, run: docker-machine env docker-test
~~~

- Once you have created a machine (i.e. the VM things will run in) you can start and stop it via docker-machine.

~~~
docker-machine start docker-test
~~~

- Once you have created or started a machine, you have to configure the enviornment in your shell to be able to work with the container.

~~~
R0223760:~ m134910$ eval $(docker-machine env docker-test)
R0223760:~ m134910$ docker-machine env docker-test
export DOCKER_TLS_VERIFY="1"
export DOCKER_HOST="tcp://192.168.99.101:2376"
export DOCKER_CERT_PATH="/Users/m134910/.docker/machine/machines/docker-test"
export DOCKER_MACHINE_NAME="docker-test"
# Run this command to configure your shell: 
# eval $(docker-machine env docker-test)
~~~

- After I started a stopped docker machine I ran into this:

~~~
R0223760:~ m134910$ eval $(docker-machine env docker-test)
Error checking TLS connection: Error checking and/or regenerating the certs: There was an error validating certificates for host "192.168.99.100:2376": x509: certificate is valid for 192.168.99.101, not 192.168.99.100
You can attempt to regenerate them using 'docker-machine regenerate-certs [name]'.
Be advised that this will trigger a Docker daemon restart which will stop running containers.
~~~

So I did this

~~~
R0223760:~ m134910$ docker-machine regenerate-certs docker-test
Regenerate TLS machine certs?  Warning: this is irreversible. (y/n): y
Regenerating TLS certificates
Waiting for SSH to be available...
Detecting the provisioner...
Copying certs to the local machine directory...
Copying certs to the remote machine...
Setting Docker configuration on the remote daemon...
~~~

Which allowed me to do the `eval` and get the environment setup.

- Now pull down an image

~~~
R0223760:~ m134910$ docker pull kaggle/python
Using default tag: latest
latest: Pulling from kaggle/python
5c90d4a2d1a8: Pull complete 
2aca0b47210e: Pull complete 
94d64496b1a4: Pull complete 
819eb10182fc: Pull complete 
850b107f4232: Pull complete 
711dac880bda: Pull complete 
8000eb2e76dc: Pull complete 
08e8b6eb101f: Pull complete 
d5703e09f8b9: Pull complete 
2d9f7d93016f: Pull complete 
7f4df05e7709: Pull complete 
e2bc8e7e1bbd: Pull complete 
50c79443ab9c: Pull complete 
d200bd026af7: Pull complete 
4a0ee60c562c: Pull complete 
aa15a64a0f6f: Pull complete 
39ea52ddfa64: Pull complete 
Digest: sha256:b1fe6a5de72c600d9178dcd1de8e3a6125368e6dd34e04e65ed16418cc51c5f5
Status: Downloaded newer image for kaggle/python:latest
~~~

- Now you can run python in your container.

~~~
R0223760:docker-scratch m134910$ docker run -v $PWD:/tmp/working -w=/tmp/working --rm -it kaggle/python python
Python 3.5.2 |Anaconda 4.1.1 (64-bit)| (default, Jul  2 2016, 17:53:06) 
[GCC 4.4.7 20120313 (Red Hat 4.4.7-1)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print ("Hello World")
Hello World
>>> import pandas
>>> import os
>>> os.pwd
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: module 'os' has no attribute 'pwd'
>>> import env
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ImportError: No module named 'env'
>>> print os.getcwd()
  File "<stdin>", line 1
    print os.getcwd()
           ^
SyntaxError: invalid syntax
>>> print ("{0}".format(os.getcwd()))
/tmp/working
>>> os.system("echo \"Hello\" > file.txt")
0
>>> 
R0223760:docker-scratch m134910$ ls
file.txt
R0223760:docker-scratch m134910$ more file.txt
Hello
R0223760:docker-scratch m134910$
~~~

- Or a shell

~~~
R0223760:docker-scratch m134910$ docker run -v $PWD:/tmp/working -w=/tmp/working --rm -it python-ds bash
[root@f4fcce6d084f working]# 
~~~

You'll get root unless you create a user account and such. Volumes are key to mounting directories and allowing interaction even with isolation.


## Cache
Docker caches images for speedy builds. I wanted to do a full build without the cache. There is a `build` option to disable the cache, but I decided I wanted to know how to clear it.

Found these useful aliases.

`alias docker_clean_images='docker rmi $(docker images -a --filter=dangling=true -q)'`
`alias docker_clean_ps='docker rm $(docker ps --filter=status=exited --filter=status=created -q)'`

This works also
`sudo docker ps --filter=status=exited --filter=status=created -q | sudo xargs docker rm`

With these, you can clear the cache with:

```
docker kill $(docker ps -q)
docker_clean_ps
docker rmi $(docker images -a -q)
```

# Docker Compose
Tool for definining and running multi-container Docker applications.

# Clair
Vulnerability scanner
https://github.com/coreos/clair

# Registries

With the V2 registries you can query for information about what's available.

(Stack Overflow)[https://stackoverflow.com/questions/31251356/how-to-get-a-list-of-images-on-docker-registry-v2#31750543]

```
curl -X GET https://myregistry:5000/v2/_catalog
curl -X GET https://myregistry:5000/v2/ubuntu/tags/list
```
