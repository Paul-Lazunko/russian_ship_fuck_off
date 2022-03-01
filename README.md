Specify target in the .env file:

```dotenv

TARGET=company.rt.ru

```

Run it via docker-compose:

```shell

docker-compose up -d --scale bombardier=10

```