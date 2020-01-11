# PruebaAlmundo
Prueba de Almundo para el Accelerator IT. Esta app está compuesta por el backend desarrollado en node js, el cual tiene como base de datos mongo db (cluster de atlas en la nube). Consta de 3 endpoints. un POST para la creación de los hoteles. Y dos GET para listar todos los hoteles en la base de datos y otro para listar un hotel en específico por ID de hotel.

El front end está desarrollado en react-native y consume los dos endpoints GET expuestos por el backend para la correcta visualización de los componentes.

Por cuestiones de tiempo no me fue posible renderizar correctamente las estrellas de los hoteles ni la ubicación de cada hotel. Se dejaron datos estáticos a propósito. Lo arreglare en el futuro.

## Prerequisitos

tener instalados  `node js y npm `

##### Pasos para ejecucion del ejercicio:

1. instalacion de paquetes requeridos(node_modules) tanto para front como para el back.
ejecutar en la raiz del proyecto y en la carpeta react-api: `npm i`
2. correr backend.
ejecutar en la raiz del proyecto: `node app.js`
3. correr front.
ejecutar en la carpeta react-api:  `npm start `
4. en el navegador abrir localhost.
 `localhost:3000 `
