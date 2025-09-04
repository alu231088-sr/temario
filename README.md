# temario
temario
Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.
<img width="239" height="155" alt="image" src="https://github.com/user-attachments/assets/48a9bc3f-061c-4707-91df-4a89b2b4c010" />

1.-Introducción al desarrollo web
Historia y evolución del desarrollo web
Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)
2.Arquitectura de aplicaciones web
Cliente-Servidor
Arquitectura de tres capas (presentación, lógica, datos)
REST y API-first design
3. -Lenguajes y tecnologías fundamentales
HTML, CSS, JavaScript, PHP, MySQL
4.-Control de versiones
Git y GitHub
Flujo de trabajo con ramas (branching, merge, pull requests)

# Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web

## 1. Introducción al desarrollo web

### 1.1 Historia y evolución del desarrollo web
- **Década de 1990**: Nace la World Wide Web (HTML básico, sitios estáticos).
- **2000-2010**: Surgen tecnologías dinámicas (PHP, ASP, bases de datos, AJAX).
- **2010-presente**: Aplicaciones ricas, frameworks JavaScript, APIs, SPA, PWA.

### 1.2 Tipos de aplicaciones web
- **Aplicaciones estáticas**: Solo HTML, CSS, sin interacción dinámica.
- **Aplicaciones dinámicas**: Generan contenido en el servidor (PHP, bases de datos).
- **SPA (Single Page Applications)**: Interfaz dinámica en una sola página, uso intensivo de JavaScript (React, Angular, Vue).
- **PWA (Progressive Web Apps)**: Aplicaciones web que funcionan como apps nativas, con capacidades offline y notificaciones push.

---

## 2. Arquitectura de aplicaciones web

### 2.1 Cliente-Servidor
- **Cliente**: Navegador web, envía peticiones y muestra resultados.
- **Servidor**: Procesa las peticiones, ejecuta lógica y responde con datos o páginas.

### 2.2 Arquitectura de tres capas
- **Presentación**: Interfaz de usuario (HTML, CSS, JS).
- **Lógica de negocio**: Procesa datos y reglas (PHP, Node.js, etc.).
- **Datos**: Almacenamiento y gestión de información (MySQL, MongoDB).

### 2.3 REST y API-first design
- **REST**: Arquitectura para APIs basada en recursos y operaciones HTTP (GET, POST, PUT, DELETE).
- **API-first design**: El diseño de la API se define antes que el desarrollo, permitiendo integración fácil entre frontend y backend.

---

## 3. Lenguajes y tecnologías fundamentales

- **HTML**: Lenguaje de marcado para estructurar páginas web.
- **CSS**: Hojas de estilo para el diseño visual.
- **JavaScript**: Lenguaje de programación para añadir interactividad en el navegador.
- **PHP**: Lenguaje de programación del lado servidor para crear aplicaciones dinámicas.
- **MySQL**: Sistema de gestión de bases de datos relacional.

## 4. Control de versiones

### 4.1 Git y GitHub
- **Git**: Herramienta para gestionar versiones de código, permite guardar historial y colaborar.
- **GitHub**: Plataforma en la nube para alojar repositorios Git y facilitar la colaboración.

### 4.2 Flujo de trabajo con ramas
- **Branching**: Crear ramas para nuevas características o correcciones.
- **Merge**: Integrar cambios de diferentes ramas.
- **Pull requests**: Solicitudes de integración de cambios, revisión y aprobación antes de unir ramas.

**Resumen:**  
Este propósito abarca la historia y tipos de aplicaciones web, su arquitectura, los lenguajes y tecnologías clave, y el manejo profesional del código con control de versiones.

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
<img width="288" height="146" alt="image" src="https://github.com/user-attachments/assets/8be22864-f88f-4cff-a847-00f996fd120a" />

1.-Diseño e implementación del frontend
Maquetación/Wireframe/Mockup
API
2.-Diseño e implementación del backend
Servidor
Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
3.-Bases de datos
 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend
4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización 

# Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

## 1. Diseño e implementación del frontend

### 1.1 Maquetación / Wireframe / Mockup
- **Maquetación:** Proceso de estructurar visualmente una página web usando HTML y CSS para definir la disposición de los elementos (cabecera, menús, contenido, pie de página, etc.).
- **Wireframe:** Boceto simple de la estructura de una interfaz, enfocado en la disposición de elementos, sin detalles de diseño.
- **Mockup:** Versión más detallada y visual del wireframe, que muestra colores, tipografías y aspecto final antes de la implementación.

### 1.2 API
- El frontend consume datos y funcionalidades a través de una **API** (Interfaz de Programación de Aplicaciones), generalmente usando peticiones HTTP para comunicarse con el backend.

## 2. Diseño e implementación del backend

### 2.1 Servidor
- El **servidor** es el programa que recibe las peticiones del frontend, procesa la lógica de negocio y responde con datos o recursos. Puede estar desarrollado en lenguajes como PHP, Node.js, Python, etc.

### 2.2 Manejo de peticiones y respuestas HTTP
- El backend debe recibir, interpretar y responder a las solicitudes que llegan por HTTP (GET, POST, PUT, DELETE), devolviendo resultados en formatos como HTML o JSON.

### 2.3 Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
- El servidor se conecta a bases de datos para almacenar, consultar y modificar datos persistentes, usando tecnologías como MySQL (relacional), PostgreSQL (relacional avanzado) o MongoDB (NoSQL/documental).

## 3. Bases de datos

### 3.1 Modelado de datos y relaciones
- Proceso de diseñar las tablas/colecciones y las relaciones entre ellas (uno a muchos, muchos a muchos, etc.), asegurando integridad y eficiencia en el almacenamiento y consulta de información.

### 3.2 ORM (Object Relational Mapping)
- Herramientas que permiten manipular bases de datos usando objetos del lenguaje de programación, facilitando la interacción y evitando escribir directamente SQL (ejemplo: Sequelize en Node.js, Eloquent en Laravel, SQLAlchemy en Python).

### 3.3 CRUD desde el backend
- Funcionalidad para **Crear, Leer, Actualizar y Eliminar** registros desde el servidor, permitiendo gestionar la información de la aplicación.


## 4. Seguridad básica en aplicaciones web

### 4.1 Validación de formularios
- Verificar en frontend y backend que los datos ingresados por los usuarios sean válidos y seguros (por ejemplo: que el email tenga formato correcto, que las contraseñas cumplan requisitos de seguridad).

### 4.2 Autenticación y autorización
- **Autenticación:** Verificar la identidad del usuario (por ejemplo, mediante inicio de sesión con usuario y contraseña).
- **Autorización:** Controlar el acceso a recursos o funcionalidades según el rol o permisos del usuario (por ejemplo, solo administradores pueden borrar datos).

**Resumen:**  
Este propósito aborda el desarrollo tanto del frontend como del backend, el manejo e integración con bases de datos, y la incorporación de prácticas básicas de seguridad en aplicaciones web.

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
<img width="291" height="163" alt="image" src="https://github.com/user-attachments/assets/ae3a928f-5ea3-4c1a-9603-9e3945777d0f" />

1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend

2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto

# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

## 1. Integración de frontend y backend

### 1.1 Interfaz de usuario Frontend
- Es la parte visual de la aplicación web, desarrollada con tecnologías como HTML, CSS y JavaScript (o frameworks como React, Vue o Angular). Permite la interacción directa del usuario con la aplicación.

### 1.2 Manejo de API
- El frontend se comunica con el backend a través de API (normalmente REST o GraphQL), enviando solicitudes y recibiendo respuestas en formatos como JSON o XML. Esta comunicación permite obtener, enviar y modificar datos.

### 1.3 Proceso de Solicitud y Respuesta de Backend
- El backend recibe las solicitudes del frontend, ejecuta la lógica necesaria (consultas a la base de datos, validaciones, procesamiento) y responde con los datos solicitados o mensajes de estado. Este proceso se realiza usando protocolos como HTTP/HTTPS.



## 2. Almacenamiento en Servidor

### 2.1 Tipos de servidores
- **Servidor físico:** Hardware dedicado exclusivamente a alojar aplicaciones y servicios.
- **Servidor virtual:** Espacio virtualizado dentro de un servidor físico, con recursos dedicados (por ejemplo, VPS).
- **Servidor en la nube:** Infraestructura proporcionada por servicios como AWS, Azure o Google Cloud, escalable y gestionada externamente.

### 2.2 Servidores y servicios de hosting
- Plataformas que permiten alojar aplicaciones web, bases de datos y otros recursos. Ejemplos: Heroku, Netlify, Vercel, DigitalOcean, AWS Elastic Beanstalk.

### 2.3 Proveedores de Servicios de Almacenamiento
- Empresas o plataformas que ofrecen almacenamiento de datos o archivos, como Amazon S3, Google Cloud Storage, Dropbox, entre otros. Permiten guardar imágenes, documentos, backups, etc.


## 3. Optimización y rendimiento

### 3.1 Optimización de recursos (imágenes, scripts)
- Consiste en reducir el tamaño de imágenes, minificar archivos CSS/JS, cargar scripts de forma asíncrona y utilizar técnicas de caché para mejorar la velocidad de carga y la experiencia de usuario.

### 3.2 Despliegue de aplicaciones web
- Proceso de poner la aplicación en línea para que esté disponible al público. Incluye configurar el entorno de producción, subir los archivos al servidor o plataforma de hosting, y asegurar que todo funcione correctamente.

### 3.3 CI/CD básico
- **Integración Continua (CI):** Automatización del proceso de pruebas e integración de código nuevo para detectar errores rápidamente.
- **Entrega/Despliegue Continuo (CD):** Automatización del proceso de despliegue de la aplicación a entornos de prueba o producción, permitiendo actualizaciones rápidas y seguras.

### 3.4 Documentación del proyecto
- Consiste en crear documentación clara sobre la estructura, instalación, uso y mantenimiento de la aplicación web, facilitando su comprensión y colaboración futura.


**Resumen:**  
Este propósito se centra en la conexión entre frontend y backend, el uso y gestión de servidores y almacenamiento, así como en la optimización, automatización y documentación necesarias para desplegar una aplicación web funcional y eficiente.
