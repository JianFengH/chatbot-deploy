# chatbot-deploy
This project is conveinent for the environment of development and deployment.

## dev
```
cd ./dev
docker-compose up -d

docker-compose down
```

## prod
Create a file `config.ini` under the directory of `prod`

```
[postgresql]
host=
database=
user=
password=

[telegram]
access_token=
``` 

```
cd ./prod
docker-compose up -d

docker-compose down
```

# view log
```
docker-compose logs -f
```