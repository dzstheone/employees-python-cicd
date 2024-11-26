# Employee application

This is a python web applicaiton with Flask.

```sh
docker run -d -e POSTGRES_DB=employees -e POSTGRES_USER=employees  -e POSTGRES_PASSWORD=employees  -p 5432:5432  --name employees-postgres postgres
```

``` sh
flask --app employees run --debug
```
