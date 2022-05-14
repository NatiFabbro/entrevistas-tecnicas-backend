## Tabla de Contenido

- [Cuál es la diferencia entre sincronismo y asincronismo?](#cuál-es-la-diferencia-entre-sincronismo-y-asincronismo)
- [Cuál es la diferencia entre Concurrencia y Paralelismo?](#cuál-es-la-diferencia-entre-concurrencia-y-paralelismo)
- [Qué es la programacion reactiva?](#qué-es-la-programacion-reactiva)
- [Qué mecanismos de seguridad conoces?](#qué-mecanismos-de-seguridad-conoces)
- [Qué es REST?](#qué-es-rest)
- [Conoces otras formas de consumir servicios aparte de rest?](#conoces-otras-formas-de-consumir-microservicios-aparte-de-rest)


# Cuál es la diferencia entre sincronismo y asincronismo? 

Esencialmente, una ejecución síncrona implica que una tarea debe completarse para poder continuar con la siguiente. Mientras que en una ejecución asíncrona podemos disparar una acción y continuar con otras tareas mientras esta se ejecuta, ya que no dependemos de la respuesta para continuar.

[Sync vs Async in JavaScript](https://www.freecodecamp.org/news/synchronous-vs-asynchronous-in-javascript/)

[Ejemplo con Node](https://www.youtube.com/watch?v=bl4Gd0FIG3g)


# Cuál es la diferencia entre Concurrencia y Paralelismo?

[concurrencia-vs-paralelismo](https://www.oscarblancarteblog.com/2017/03/29/concurrencia-vs-paralelismo/)


# Qué es la programacion reactiva? 

https://profile.es/blog/que-es-la-programacion-reactiva-una-introduccion/


# Qué mecanismos de seguridad conoces? 

[JSON Web Token (JWT)]((https://jwt.io/)) es un estándar abierto (RFC-7519) basado en JSON para crear un token que sirva para enviar datos entre aplicaciones o servicios y garantizar que sean válidos y seguros. El caso más común de uso de los JWT es para manejar la autenticación en aplicaciones móviles o web.


[OAuth 2.0](https://oauth.net/2/) es un estándar abierto para la autorización de APIs, que nos permite compartir información entre sitios sin tener que compartir la identidad. 

[Passport](https://www.passportjs.org/) is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped in to any Express-based web application. 


[Spring Security](https://spring.io/projects/spring-security) es un framework que permitirá gestionar todo lo relativo a la seguridad de nuestra aplicación web, desde el protocolo de seguridad, hasta los roles que necesitan los usuarios para acceder a los diferentes recursos de la aplicación.

[Firebase Authentication](https://firebase.google.com/products/auth?gclsrc=ds&gclsrc=ds) busca facilitar la creación de sistemas de autenticación seguros, a la vez que mejora la experiencia de integración y acceso para los usuarios finales. Proporciona una solución de identidad de extremo a extremo, compatible con cuentas de correo electrónico y contraseñas, autenticación telefónica, acceso mediante Google, Twitter, Facebook y GitHub, y mucho más.


# Qué es REST?

REST (Transferencia de Estado Representacional / Representational State Transfer) es conjunto de reglas de arquitectura para cualquier interfaz entre sistemas que use HTTP para obtener datos o generar operaciones sobre esos datos en todos los formatos posibles, como XML y JSON, lo que lo hace independiente del tipo de plataformas o lenguajes.

https://www.bbvaapimarket.com/es/mundo-api/api-rest-que-es-y-cuales-son-sus-ventajas-en-el-desarrollo-de-proyectos/
https://www.redhat.com/es/topics/api/what-is-a-rest-api


# Conoces otras formas de consumir microservicios aparte de rest?

[GraphQL](https://graphql.org/)

[gRCP](https://grpc.io/)