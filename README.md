Specify target in the .env file:

```dotenv

TARGET=fuck.ru

```

Run it via docker-compose at the VPS:

```shell

docker-compose up -d --scale rsfo1=20

```