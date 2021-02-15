# Spoton 

Social Platform for posts. 

## Dev Setup

1. To build the app and docker images

```bash
docker-compose build
```
2. To initialize the database and run migrations

```bash
docker-compose run app rake db:init
docker-compose run app rake db:migrate
```

3. To run the application you can use 

```bash
docker-compose up -d
```


The application should be accessible on `http://localhost:3000`

Any changes made on your local should be reflected automatically as we are doing a volume mount.


