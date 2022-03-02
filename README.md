Specify target in the .env file:

```dotenv

TARGET=company.rt.ru

```

Run it via docker-compose at the VPS:

```shell

docker-compose up -d --scale rsfo1=8 rsfo2=8 rsfo3=8  rsfo4=8 rsfo5=8

```