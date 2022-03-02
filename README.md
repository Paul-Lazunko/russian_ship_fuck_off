Specify target in the .env file:

```dotenv

TARGET=company.rt.ru

```

Run it via docker-compose at the VPS:

```shell

docker-compose up -d --scale rsfo1=8 --scale rsfo2=8 --scale rsfo3=8  --scale rsfo4=8 --scale rsfo5=8

```