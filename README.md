# docker-kodexplorer

Docker image of [KodExplorer](https://github.com/kalcaddle/KodExplorer)

## Run

```
docker run -d -p 80:80 --name kodexplorer -v $HOME/docker/kodexplorer:/var/www/html -v <RUTA ARCHIVOS>::/var/www/html/data/User/admin/home ugeek/kodexplorer
```
