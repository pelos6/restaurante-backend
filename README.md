# RESTAURANTE BACKEND

* repositorio de ejemplo par el curso con Juanda JAVIER

## Descripción

- Un contenedor con una base de datos mysql llamada restaurante y un esquema de base de datos según ./data/initData/database.sql
- Un contenedor con un phpmyadmin para acceder a la base de datos
  - usuario/pwd por defecto user/admin (se puede modificar en el fichero .env)
  ```
  localhost:8080
  ```

- Un contenedor con una aplicación en node.js que obtiene los datos y los muestra vía API:

  ```
  http://localhost:3000/categories
  http://localhost:3000/restaurants
  http://localhost:3000/dishes
  http://localhost:3000/customers
  http://localhost:3000/orders
  http://localhost:3000/order/1/dishes

  ```

## Ejecución

```
docker compose up -d
```
# restaurante-backend
