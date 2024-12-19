<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```bash
npm install
```

3. Tener Nest CLI instalado

```bash
npm i -g @nestjs/cli
```

4. Levantar la base de datos

```bash
docker-compose up -d
```

5. Clonar el archivo **.env.template** y renombrar la copa a **.env**

6. Llenar las variables de entorno definidad en ela archivo

```bash
.env
```

7. Ejecutar la aplicación en dev

```bash
npm run start:dev
```

8. Reconstruir la base de datos

```bash
http://localhost:3000/api/seed
```

6.

## Stack Usado

- MongoDB
- NestJS
