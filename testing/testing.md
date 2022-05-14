## Tabla de Contenido

- [Qué tipos de testing conoces?](#qué-tipos-de-testing-conoces)
- [Qué herramientas de testing conoces](#qué-herramientas-de-testing-conoces)
- [Qué librerías de testing conoces?](#qué-librerías-de-testing-conoces)
- [Conoces TDD y BDD?](#conoces-tdd-y-bdd)
- [Conoces gherkin/AAA?](#conoces-gherkinaaa)
- [Enfocas tus pruebas sólo en coverage o también en robustez?](#enfocas-tus-pruebas-sólo-en-coverage-o-también-en-robustez)


# Qué tipos de testing conoces?

    - Pruebas unitarias: de muy bajo nivel. Están compuestas de pruebas de métodos y funciones individuales de las clases, componentes o módulos del software. 

    - Pruebas de integración: verifican que los distintos módulos o servicios utilizados por la aplicación funcionan bien en conjunto. 

    - Pruebas funcionales: se centran en los requisitos empresariales de una aplicación. Solo verifican el resultado de una acción y no comprueban los estados intermedios del sistema al realizar dicha acción.

    - Pruebas integrales: replican el comportamiento de un usuario con el software en un entorno de aplicación completo. Además, verifican que diversos flujos de usuario funcionen según lo previsto.

    - Pruebas de rendimiento: comprueban el comportamiento del sistema cuando está sometido a una carga importante. Estas pruebas no son funcionales y pueden tener la forma variada de entender la fiabilidad, la estabilidad y la disponibilidad de la plataforma.

    - Pruebas de humo: sirven para comprobar la funcionalidad básica de la aplicación. Están concebidas para ejecutarse rápido, y su objetivo es ofrecerte la seguridad de que las principales funciones de tu sistema funcionan según lo previsto.

https://www.atlassian.com/es/continuous-delivery/software-testing/types-of-software-testing


# Qué herramientas de testing conoces? 

[Postman](https://www.postman.com/)
        
[SoapUi](https://www.soapui.org/)
        
[Insomnia](https://insomnia.rest/download)
    

# Qué frameworks/librerías de testing conoces? 

[Junit](https://junit.org/junit5/)


# Conoces TDD y BDD? 

El [test-driven development (TDD)](https://www.paradigmadigital.com/dev/tdd-como-metodologia-de-diseno-de-software/) es una metodología de diseño de software que se basa en test o pruebas para guiar el proceso. Al contrario de lo que ocurre en metodologías que posponen los test a un punto ulterior, los casos de prueba en TDD se realizan al inicio del proceso de diseño.

[BDD - Behavior Driven Development](https://www.federico-toledo.com/que-es-bdd/): desarrollo dirigido por comportamiento. Como bien lo indica su nombre, no se trata de una técnica de testing, sino que es una estrategia de desarrollo. Lo que plantea es definir un lenguaje común para el negocio y para los técnicos, y utilizar eso como parte inicial del desarrollo y el testing. Por esto es que es importante que vos como tester entiendas bien qué es BDD.

[TDD vs BDD. Expectativas de calidad de tus desarrollos](https://www.itdo.com/blog/tdd-vs-bdd-expectativas-de-calidad-de-tus-desarrollos/)

# Conoces gherkin/AAA?

[Gherkin](https://cucumber.io/docs/gherkin/) es un DSL o Lenguaje Específico de Dominio (Domain-Specific Languaje), es decir, un lenguaje que está creado para resolver un problema.

Habitualmente los proyectos tienen dos tipos de perfiles: de negocio y tecnológicos.

Hay entornos donde es muy importante que haya mucha cohesión entre esos perfiles, por lo que es vital tener un lenguaje común como Gherkin, que entiendan estos dos perfiles e incluso que entiendan las máquinas.

https://openwebinars.net/blog/que-es-gherkin/



[AAA](https://automationpanda.com/2020/07/07/arrange-act-assert-a-pattern-for-writing-good-tests/) es un patrón para estructurar tests. Divide cada test en 3 partes: Arrange, Act, and Assert, donde cada parte es un paso necesario para el siguiente. 

# Enfocas tus pruebas sólo en coverage o también en robustez? 

    - Coverage: se refiere a crear tests que pasen por la mayor cantidad posible de líneas de código de nuestro software

    - Robustez: se refiere a crear tests que aseguren el funcionamiento del software, además de la cobertura
