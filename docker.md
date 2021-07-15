# Docker
## Создание образов

    docker build -t <image name> <path>

## Запуск контейнера

    docker run -it --rm -p <port of the host machine>:<port of the container> --name <name> <image name>

## Сеть

    docker network inspect bridge