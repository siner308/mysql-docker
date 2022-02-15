# mysql-docker

## set env

```bash
$ cp .env.sample .env
```

## start

```bash
$ docker-compose up -d --build
```

## stop

```bash
$ docker-compose down
```

## set adminer

If you want UI dashbord together, just unset comment in docker-compose `adminer` application
