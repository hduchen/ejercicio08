# Pasos 

* Creamos archibo docker-compose.yml de configuracion

* Creamos DockerFile de Nginx.conf


* Ejecutamos comando levantar 

```
$   docker-compose up

```
* validamos q este levantados correctamente

```
$   docker-compose ps

```

* validamos luego ejecutamos Helath para ver que corre por contenedores

```
$ curl --location --request GET 'http://localhost:3000/health'

```

