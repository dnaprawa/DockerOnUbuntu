# Install Docker and docker-compose on Ubuntu



##### 
####
```sh
$ sudo curl -LJO https://raw.githubusercontent.com/dnaprawa/DockerOnUbuntu/master/docker.sh 
$ sudo sh docker.sh
```

### If you encounter below error when trying to use docker commands, you will need to logout and log in again.

```sh
Got permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.soc
```

### If you are installing on the VM....

If you plan to install on a Virtual Machine, after installation a VM restart would be required in order to propagate `docker` usergroup assigment to you user.

