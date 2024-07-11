**ForoHub** es una plataforma API REST desarrollada con Spring Boot, diseñada para facilitar la gestión de tópicos en una comunidad virtual. Permite a los usuarios autenticarse, crear, listar y eliminar tópicos de discusión de manera eficiente y segura mediante autentificación JWT.

## Características ✨

- **Registro de Usuarios**: Registro seguro de nuevos usuarios mediante endpoint `POST /signup`.
- **Autenticación JWT**: Generación de tokens JWT para inicio de sesión seguro con `POST /login`.
- **Gestión de Tópicos**: Creación (`POST /topicos`), listado (`GET /topicos` o `GET /topicos{id}` ), actualización (`PUT /topicos/{id}`) y eliminación (`DELETE /topicos/{id}`) de tópicos disponibles.

## Dependencias 🛠️

El proyecto hace uso de diversas tecnologías y herramientas indispensables:

- **Spring Security**: Para la gestión de la seguridad y autenticación.
- **JWT (JSON Web Tokens)**: Para la creación y validación de tokens de autenticación.
- **JPA (Java Persistence API)**: Para la persistencia de los datos.
- **MySQL**: Base de datos relacional utilizada para el almacenamiento de datos.
- **Lombok**: Para la reducción de código en la creación de getters y setters,
- **Flyway**: Para la migración y versionado de la base de datos.
- **Swagger**: Para la documentación automática de la API.
---------------------------------En construcciobn-----------------------------------
