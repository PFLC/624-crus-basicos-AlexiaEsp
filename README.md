# ¿Qué es CRUD?

CRUD es el acrónimo de Create (Crear), Read (Leer), Update (Actualizar) y Delete (Borrar). Este concepto se utiliza para describir las cuatro operaciones básicas que pueden realizarse en la mayoría de las bases de datos y sistemas de gestión de información.
El concepto de CRUD surge en el contexto del desarrollo de software y de la gestión de bases de datos relacionales. La idea es que cualquier sistema de información que interactúe con datos debe proporcionar funcionalidades para crearlos, leerlos, actualizarlos y eliminarlos.
Un framework CRUD, usualmente formado por interfaces HTML, muestra los objetos individuales a través de una interfaz gráfica y los modifica mediante operaciones CRUD. Éstas pueden ser configuradas para ejecutarse en períodos distintos, permitiendo a los demás usuarios acceder a los datos de cada plazo determinado, siendo útiles para sistemas multiusuarios.
El CRUD permite, por lo tanto, reunir las operaciones básicas en un solo elemento, lograr que el cliente entienda más fácilmente cómo funciona el sistema, así como reutilizar el código y especificar los casos de uso sin demandar mucho tiempo ni esfuerzo.

![image](https://github.com/PFLC/624-crus-basicos-AlexiaEsp/assets/113717920/9c011e68-89a9-47b6-a409-6790fc352288)

- Create (Crear registros)
- Read (Leer registros)
- Update (Actualizar registros)
- Delete (Borrar registros)

---

## Ventajas y desventajas del CRUD

*Ventajas*

- Facilita la creación y gestión de datos.
- Proporciona una estructura coherente y fácil de entender para su manipulación.
- Ayuda a minimizar los errores y garantiza la integridad de los datos.
- Proporciona una base sólida para el desarrollo de aplicaciones.

*Desventajas*

- Puede ser demasiado simplista para aplicaciones complejas.
- En ocasiones, es menos eficiente para aplicaciones de alta velocidad o de gran escala.
- A veces, requiere una gran cantidad de código y configuración para implementarlo completamente.

---
## Ejemplos de aplicaciones del CRUD

- Aplicaciones de gestión de contenido
- Aplicaciones de comercio electrónico
- Sistemas de reservas
- Aplicaciones de redes sociales
- Aplicaciones de gestión de proyectos

  ## Función de cada fase
  
**Create (crear)**
  
Esta fase se utiliza para crear un nuevo registro en la base. Para implementar la operación «Crear», es necesario proporcionar un formulario o una interfaz donde el usuario pueda ingresar los datos para el nuevo registro. ***Después de que el usuario envía los datos, se debe realizar una validación de los mismos y luego insertarlos en la base o en el sistema de almacenamiento.***

**Read (leer)**

Esta fase se utiliza para leer los datos de la base y mostrarlos al usuario. Para implementar la operación «Leer», se debe proporcionar una interfaz que permita al usuario buscar y recuperar los registros existentes. ***Esto puede lograrse mediante el uso de filtros de búsqueda y una lista de resultados. Cuando el usuario hace clic en un registro, se debe mostrar su información completa.***

**Update (actualizar)**

Esta fase se utiliza para actualizar los datos existentes en la base de datos. Para implementar la operación «Actualizar», es necesario proporcionar una interfaz para que el usuario pueda modificar los datos de un registro existente. ***Una vez que el usuario envía los datos actualizados, debe realizarse una validación de los mismos y luego actualizar el registro correspondiente en la base o en el sistema de almacenamiento.***

**Delete (borrar)**
Esta fase se utiliza para eliminar un registro existente. Para implementar la operación «Eliminar», se debe proporcionar una interfaz que permita al usuario seleccionar un registro existente y confirmar su eliminación.

---

# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

