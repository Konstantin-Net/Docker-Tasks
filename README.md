## Команды для создания Docker образа и запуска контейнера

### Задача 1

```bash
docker build --tag nginx_test .

docker run -it -p 7777:80 nginx_test
```

### Задача 2

```bash
docker build --tag crud .

docker run -it -p 8000:8000 crud
```
