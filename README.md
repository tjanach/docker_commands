# docker_commands

## Basic Options
+ ```-d``` used to create the container as demon
+ ```-i``` used to create the container in interactive mode
+ ```--name <cname>``` custom name for the container    
+ ```-e <ENV=value>``` used to create ENV variable = val
+ ```--link <cname>``` links the container to another container "cname" 
+ ```--read-only ``` causes the container created in read-only mode, it cannot change its file system
+ ```-v <exception path>``` add exception paths to the mode of read-only 
+ ```run <cname>``` creates and run a container
+ ```create <cname>``` creates a container, but not starts
+ ```start <cname>``` starts existing container
+ ```stop <cname>``` stops existing container
+ ```restart <cname>``` stops and starts existing container

        

## Creation of mySQL DB
```sh
$ docker run -d --name mySqlServer -e MYSQL_ROOT_PASSWORD=admin mysql
```



