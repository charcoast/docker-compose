# docker-compose

Dockercompose do projeto Aplantica

## Start
1. Clonar os repositórios
```
$ git clone https://github.com/charcoast/docker-compose && git clone https://github.com/charcoast/storage-sensor-data
```
2. Mover o docker-compose.yml para o seu diretório corrente.
```
$ mv docker-compose/docker-compose.yml . && rm -rf docker-compose/
```
3. Execute o docker-compose
```
$ docker-compose up --build -d
```
