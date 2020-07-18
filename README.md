# proyecto-sequelize
Hola a todes!

Les paso un proyecto modelo que estuve armando de en Node, Express y muuucho sequelize

https://github.com/dariosus/proyecto-sequelize

¿Porqué?

Bueno, principalmente porque la ejercitación de la clase 22 asume que los alumnos ya hicieron mucho de esto y la idea es darle este proyecto a los alumnos en esa clase si es que estan medio bloqueados...

Además, mientras lo hacía me pareció una GRÁN referencia tanto para alumnes como para ustedes :)

¿Cómo instalarlo?

- Necesitan tener la movies_db en su sistema
- Clonan el proyecto
- npm install
- editan los datos de base de datos (en carpeta config)

LISTO

¿Qué tiene el proyecto?

- CRUD de películas, actores y generos
- Estan montados los modelos de las 3 tablas y todas las relaciones
- Se muestran todas las relaciones (1:N y N:M)
- Se pueden editar y crear relaciones 1:N
- Todos los forms validados y se muestran mensajes de error. Inclusive hay lógica para que si querer borrar un género con películas o películas con actuaciones todo funciones de pelos.
- Hay custom rule (para la validación de fecha) y mensajes de error custom
- Buscador
- Algunos endpoints extras para ver order, limit y where en sequelize (en moviesController)
- Template en ejs (usando bootstrap y css propio)

Opciones de mejora

Creo que RE podría crecer. Si gustan, avisen y les doy permisos en el repo o se hacen un fork. Algunas ideas de cosas que se pueden agregar:

- Express Validator: Custom rules más piolas
- Express Validator: Que cada campo se marque en rojo en error
- Express Validator: Que en caso de error se mantengan los campos ya completados
- Realizar la alta, edición y borrado de actuaciones (relación entre películas y actores)
- Refactor de validators: Se podrían sacar los validators de las rutas y ponerlos en archivos correspondientes
- Agregar registración, login y hacer que algunas rutas (creación, edición y borrado) sean solo para usuarios logueados
- Versión 3: Tener 2 tipos de usuarios y que solo los admins puedan borrar


En fin, ojalá sirva :)

Abrazo!!