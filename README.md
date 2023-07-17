## Creación de una API REST con Spring Boot
Se implementan métodos **GET, POST, PUT y DELETE** aplicando la técnica **TDD (Test Driven Development)**

<br>Con TDD se hacen pruebas antes de implementar el código de la aplicación. Es una técnica probada y verdadera <br>
para ayudar a los desarrolladores de aplicaciones a diseñar software simple pero robusto, además de protegerse <br> contra regresiones de funcionalidad y errores. 
Además, los test son pruebas para guiar la implementación de nuestro código.

<br>Se ha creado la API mediante una arquitectura en capas.
* Spring Security se encuentra en la "parte frontal" de la API.
* Spring Web habilita las comunicaciones HTTP entre la API y sus clientes.
* Spring Data maneja la lectura y escritura en / desde el almacén de datos relacionales.

