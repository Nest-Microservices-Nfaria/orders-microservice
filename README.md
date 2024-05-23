# Orders Microservice 



```
docker compose up -d
```

1. Clonar el proyecto
2. Crear el archivo `.env` basado en el archivo `.env.template`
3. Levantar la base de datos con `docker compose -up -d`
4. Levantar el servicor de NATS
```
docker run -d --name nats-sever -p 4222:4222 -p 8222:8222 nats
```
5. Levantar el proyecto con `npm run start:dev` 