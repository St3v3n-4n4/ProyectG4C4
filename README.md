# ProyectG4C4
Sistema de Gestión de Información WEB

<div align="center">
<h1> <b>Proyecto G4C4</b> </h1>

[![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=000000&?logoWidth=40)](https://github.com/St3v3n-4n4/AnaPi_IoT) 
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white&labelColor=000000&?logoWidth=40)](https://github.com/St3v3n-4n4/AnaPi_IoT) 
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=000000&?logoWidth=40)](https://github.com/St3v3n-4n4/AnaPi_IoT)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white&labelColor=000000&?logoWidth=40)](https://github.com/St3v3n-4n4/AnaPi_IoT)

[![NodeJS](https://img.shields.io/badge/NodeJS-339933?style=for-the-badge&logo=Node.js&logoColor=white&labelColor=000000&?logoWidth=40)](https://github.com/St3v3n-4n4/AnaPi_IoT)

[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white&labelColor=000000&?logoWidth=40)](https://github.com/St3v3n-4n4/AnaPi_IoT)


</div>

La empresa `Fly Emirates` nos ha contratado para desarrollar un sistema que le permita
`gestionar la información relacionada con su plan de negocio` tras su llegada reciente a
Colombia.
Dicho software debe cumplir con una serie de requerimientos que se enumeran a
continuación:
- `Gestionar Usuarios del sistema`, los cuales tiene la siguiente información: (`id`,
`nombre`, `apellidos`, `correo`, `teléfono`, `contraseña`), el correo debe ser único en la
base de datos, la contraseña se debe generar de forma dinámica y ser enviada
al usuario vía correo electrónico.
- `Implementar el módulo de autenticación en la plataforma`, tanto a nivel de
Frontend como de Backend.
- `Registrar`, `consultar`, `editar` y `eliminar Aeropuertos`, los cuales tiene la siguiente
información: (`id`, `nombre`, `ciudad`, `país`, `coord. x`, `coord. y`, `siglas`, `tipo`), el tipo
puede ser nacional o internacional y las siglas deben ser únicas en la base de
datos.
- `Registrar`, `consultar`, `editar` y `eliminar Rutas`, las cuales tienen la siguiente
información: (`id`, `origen`, `destino`, `tiempo estimado`), el origen y destino son
Aeropuertos previamente registrados y deben ser diferentes.
- `Registrar`, `consultar`, `editar` y `eliminar la información de los Vuelos` los cuales tienen
la siguiente información (`id`, `fecha inicio`, `hora inicio`, `fecha fin`, `hora fin`, `asientos
vendidos`, `nombre piloto`, `ruta`), donde la ruta debe pertenecer a una ruta
previamente registrada.