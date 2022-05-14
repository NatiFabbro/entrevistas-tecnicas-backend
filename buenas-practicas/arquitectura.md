## Tabla de Contenido

- [Clean architecture (Arquitectura limpia)](#clean-architecture-arquitectura-limpia)
- [Qué es un microservicio?](#qué-es-un-microservicio)
- [Qué diferencias hay entre monolito y microservicios?](#qué-diferencias-hay-entre-monolito-y-microservicios)

# Clean architecture (Arquitectura limpia)

[Clean Architecture](https://www2.deloitte.com/es/es/pages/technology/articles/clean-architecture.html) es un nombre popularizado por Robert C Martin, que se basa en la premisa de estructurar el código en capas contiguas, es decir, que solo tienen comunicación con las capas que están inmediatamente a sus lados. Basados en esta idea podemos encontrar artículos que hablan sobre Clean Architecture, Onion Architecture, Hexagonal Architecture, todas ellas tienen diferentes enfoques, pero comparten la idea de que cada nivel debe realizar sus propias tareas y se comunica únicamente con sus niveles inmediatamente contiguos.


# Qué es un microservicio?

La [Arquitectura de microservicios](https://es.wikipedia.org/wiki/Arquitectura_de_microservicios) es una aproximación para el desarrollo de software que consiste en construir una aplicación como un conjunto de pequeños servicios, los cuales se ejecutan en su propio proceso y se comunican con mecanismos ligeros


# Qué diferencias hay entre monolito y microservicios?

Mientras que una app de microservicios está constituida por diversos módulos y componentes que se comunican entre sí (pero sin por ello perder su grado de independencia), las aplicaciones monolíticas destacan por agrupar todas las funciones en un solo gran código.

[Detalle de las diferencias](https://codster.io/blog/aplicacion-monolitica-vs-microservicios/)