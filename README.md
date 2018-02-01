# docker_commands
docker_commands

## Basic Options
    ### -d option
        used to create the container as demon
    ### -i option
        used to create the container in interactive mode
    ### --name cname
        custom name for the container

## creation of mySQL DB
```sh
$ docker run -d --name mySqlServer -e MYSQL_ROOT_PASSWORD=admin mysql
```



