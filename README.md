<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Teslo API

1. Clonar proyecto
2. `npm install`
3. Clonar el archivo `.env.template` y renombrarlo a `.env`
4. Cambiar las variables de entorno
5. Levantar la base de datos

```
docker-compose up -d
```

6. Levantar:

```
npm run start:dev (yarn start:dev)

```

7. Ejecutar SEED

```
http://localhost:4000/api/seed
``` 
Nota: Si no permite subir en el puerto 3000 que es por defecto, lo cambiamos al 4000. Tambien cambiar en las bariales de entorno .env

# Production notes:
