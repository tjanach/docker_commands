# docker_commands

## Basic Options
+ ```-d``` used to create the container as demon
+ ```-i``` used to create the container in interactive mode
+ ```--name <cname>``` custom name for the container    
+ ```-e <ENV=value>``` used to create ENV variable = val
+ ```run <cname>``` creates and run a container
+ ```create <cname>``` creates a container, but not starts
+ ```start <cname>``` starts existing container
+ ```stop <cname>``` stops existing container
+ ```restart <cname>``` stops and starts existing container
        

## Creation of mySQL DB
```sh
$ docker run -d --name mySqlServer -e MYSQL_ROOT_PASSWORD=admin mysql
```



