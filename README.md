# Proyecto Foro Alura

  

Foro Hub es un API : creado en Java Spring, que se basa en REST, corresponde a un requisito para la formación de `BacKEnd` de #OracleOne y #Alura.

Este API se conecta a una base de datos MySQL
 La función principal de este Web API es crear una tópico o llamado cosulta, para uno de los cursos y que otros usuarios puedan ayudarle mediante respuestas.


El mismo permite consultar, crear, modificar y eliminar tópicos, respuestas. Y permite consultar, crear y modificar usuarios.

<h2>Autenticación</h2>

  

- Para utilizar los métodos del Web API es necesario autenticarse, se utiliza JWT para realizarlo, lo debe de realizar en el método `POST` de la ruta `/login`

- Una vez generado el token deberá de utilizarse en la sección Authorize (Swagger UI).


- Una vez verificado el token podra consumir los mètodos de `GET`, `POST`, `PUT`, `DELETE`.




<h2>Tecnologías Utilizadas</h2>

  - Lombok

- JDK 17.

- Maven.

- Spring Web

- Spring Boot.

- MySQL.

- Spring Data JPA.

- Flyway Migration

- Validation

- Spring Security - Auth0 para la creación de JWT.

- Swagger UI.




