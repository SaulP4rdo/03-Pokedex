<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio

2. Ejecutar **"pnpm i"** para instalar las dependencias

   ```sh
   pnpm install
   ```

3. Tener Nest CLI instalado

   ```sh
   pnpm i -g @nestjs/cli
   ```

4. Levantar la base de datos

   ```sh
   docker-compose up -d
   ```

5. Clonar el archivo `.env.template` y renombrar la copia a `.env`

6. LLenar las variables de entorno definias en `.env`

7. Reconstruir la base de datos con la semilla

   - [http://localhost:3000/api/v2/seed](http://localhost:3000/api/v2/seed)

8. Ejecutar la aplicacion en dev:

   ```sh
   pnpm start:dev
   ```

# Stack Usado

- MongoDB
- Nest
