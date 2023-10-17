### ! через $ обозначаются переменные
#### Посмотреть запущенный контейнеры
```
docker ps
```
#### Посмотреть все контейнеры
```
docker ps -a
```
#### Запустить контейнер
```
docker run -it -d --name $container_name $docker_image
```
Например запустить контейнер из образа nginx
```
docker run -it -d --name nginx_test nginx
```
#### Собрать docker-image
```
docker build -t $tag .
```
#### Зайти в контейнер
```
docker exec -it $container_name /bin/bash
```
