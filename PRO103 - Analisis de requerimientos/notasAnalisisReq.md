# Notas Introducción a Requerimientos y Modelos de Negocios

##### Profesor: Diego Coronado

##### AIEP Osorno Marzo/Abril 2021

### Contenidos

**Unidad de competencias:** Al finalizar el modulo, los participantes serán capaces de realizar especificaciones de requerimientos funcionales y no funcionales de software, aplicando estrategias de recolección de datos mediante el modelamiento de procesos de negocio (**BPMN**), según las de la organización.

**Contenidos:**

Organizan requerimientos funcionales y no funcionales a partir de técnicas de obtención de requisitos del ciclo de vida de un software, considerando problemática y tipo de organización

- Definiciones de desarrollo de un software y su ciclo de vida.
- Requerimientos funcionales y no funcionales de distintos tipos de organizaciones.
- Tipos de problemáticas según los tipos de organizaciones: Sociales, empresariales o gubernamentales.
- Procesos incrementales.
- Técnicas de obtención de requerimientos: Entrevistas, reuniones, cuestionarios, escenario, prototipos, arqueología de sistemas, Thinking Design.
- Pirámide de requerimientos según las metodologías ágiles (desde las necesidades de usuario hasta los requisitos de software).

Aplican técnicas de identificación y validación de requerimientos en el ámbito de la elaboración del software.

- Instrumentos de obtención de los requerimientos funcionales y no funcionales (explicación de los roles de los actores y de los casos de uso, y como se relacionan entre ellos).
- Técnicas de elaboración de instrumentos efectivos para la toma de requerimientos.
- Técnicas de validación de los instrumentos de obtención de requerimientos.
- Validación de requerimientos funcionales y no funcionales.
- Resultados de requerimientos funcionales y no funcionales.

Realizan levantamientos de requisitos de software acorde a las problemáticas especificas dentro de una organización, considerando un enfoque iterativo.

- Enfoque iterativo dentro de un equipo de desarrollo de software según las metodologías ágiles.
- Las iteraciones dentro de un ciclo de vida de un software.
- El proceso ágil de desarrollo de software.
- Introducción a UML: Casos de uso / Diagrama de secuencias / Diagrama de actividad.
- Metodologías ágiles SCRUM y XP.
- DFD (Diagramas de Flujo de Datos).

Caracterizan objetivo del modelado de los procesos de negocio, considerando el desarrollo ágil de soluciones a las necesidades de los distintos tipos de organizaciones.

- Diagramas para el modelado de los procesos de negocio.
- Tipos de arquitectura de negocios dentro de las organizaciones (Sociales, Empresa y gobierno).
- Procesos de negocio y gobernabilidad para el desarrollo ágil.
- Diagramación de los procesos de negocio dentro de las organizaciones (Casos de Uso, diagramas de actividad, diagramas de secuencias, etc.)

Relacionan cultura ágil con desarrollos de soluciones a los distintos procesos de negocio.

- Delimitando el alcance del proyecto dentro del desarrollo de software según las metodologías ágiles.
- Comunicación con el cliente dentro de un equipo de desarrollo de software según las metodologías ágiles.
- La cultura ágil: (Valores, principios y practica).
- Valores y creencias de la cultura ágil.
- Principios y modelos mentales de la cultura ágil.
- Comportamiento y artefactos en la cultura ágil.
- Pirámide de la cultura ágil.

Aplican técnicas para la descripción de procesos de negocio mediante diagramas de cosos de uso y de actividades.

- Elementos del modelo de casos de uso en el modelado de procesos de negocio.
- Objetivo del diagrama de actividades en el modelado de los procesos de negocio.
- Especificaciones de los diagramas de actividades en el modelado de los procesos de negocio.

## Unidad 1: Requerimientos de Software

### ¿De qué trata el Desarrollo de Software?

Esto es la programación lógica que todo sistema de cómputo necesita para funcionar correctamente y permitir al usuario disfrutar de aspectos como una interfaz amigable y rápida, asi como las funciones que el programa realice.

Ahora el Desarrollo de Software estudia los componentes necesarios para la creación, gestión, mantenimiento y testeo de Software computacional; a la persona encargada de esto se le llama programador y este es un especialista en informática, capaz de elaborar sistemas informáticos (paquetes de Software), así como de implementarlos y ponerlos a funcionar, utilizando uno o varios lenguajes de programación.

### Problemas en el desarrollo

Una de las mayores deficiencias en la construcción de software es la poca atención que se presenta en la discusión del problema.

En general los desarrolladores se concentran en la solución dejando el problema inexplorado, en consecuencia el problema a resolver debe ser deducido a partir de su solución.

Perder de vista el origen de un problema puede provocar que la aparición de nuevos problemas no se detecten a tiempo y en consecuencia interfieran con la solución inicial.

### ¿Qué es el ciclo de vida del Software?

El ciclo de vida del desarrollo del Software (también conocido como SDLC O Systems Development Life Cycle) contempla las fases necesarias para validar el desarrollo del software y así garantizar que este cumpla los requisitos para la aplicación y verificación de los procedimientos de desarrollo, asegurándose de que los métodos usados son apropiados.

Su origen radica en que es muy costoso rectificar los posibles errores que se detectan tarde en la fase de implementación. Utilizando metodologías apropiadas, se podría detectar a tiempo para que los programadores puedan centrarse en la calidad del software, cumpliendo los plazos y los costes asociados.

### Fases del proceso de desarrollo de Software

Las fases del desarrollo de Software son los procesos a seguir sistemáticamente para idear, implementar y mantener un producto de Software desde que surge la necesidad del producto hasta que se cumple el objetivo por el cual fue creado.

De esta forma, las etapas del desarrollo de software son las siguientes:

- Planificación.
- Análisis.
- Diseño.
- Desarrollo.
- Pruebas.
- Implementación.
- Mantenimiento.

#### 1. Planificación

En esta fase se prepara el diseño y posterior implementación del sistema. Es necesario definir el alcance del proyecto, justificarlo y escoger una metodología para su desarrollo. También es preciso asociar las diferentes actividades a plazos de tiempo y designar roles y responsabilidades.

#### 2. Análisis

Por supuesto, hay que averiguar qué es exactamente lo que tiene que hacer el software. Por eso, la etapa de análisis en el ciclo de vida del Software corresponde al proceso a través del cual se intenta descubrir qué es lo que realmente se necesita y se llega a una comprensión adecuada de los requerimientos del sistema (las características que el sistema debe poseer).

#### 3. Diseño

En este estadio el equipo de proyecto tendrá que determinar cómo el nuevo sistema cumplirá con los requisitos recolectados. Es por ello que se debe identificar soluciones potenciales, evaluarlas y elegir la más conveniente. Ésta será o la más efectiva, o la más eficiente en costes o la menos compleja. Una vez completadas esas tareas, habrá que continuar haciendo la selección tecnológica de Software y Hardware.

#### 4. Desarrollo

El desarrollo de Software marca un antes y un después en la vida del sistema y significa, además, el inicio de la producción. El cambio es una constante durante esta etapa, en la que suele ser recomendable poner el foco en la formación y capacitación de los usuarios y el equipo técnico.

#### 5. Pruebas

Como errar es humano, la fase de pruebas del ciclo de vida del Software busca detectar los fallos cometidos en las etapas anteriores para corregirlos. Por supuesto, lo ideal es hacerlo antes de que el usuario final se los encuentre. Se dice que una prueba es un éxito si se detecta algún error.

Es recomendable que las pruebas sean realizadas por una persona distinta al programador, lo que no quiere decir que el programador no deba hacer sus propias pruebas.

#### 6. Implementación

En esta etapa del ciclo de vida de un sistema de información hay que proceder a la instalación del Hardware y Software elegidos, someterlos a pruebas, crear la documentación pertinente y capacitar a los usuarios. La conversión de datos es importante en este estadio, en el que ya se empieza a trabajar en el nuevo sistema.

Es posible que haya componentes que funcionen correctamente por separado, pero que al combinarlo provoquen problemas. Por ello, hay que usar combinaciones conocidas que no causen problemas de compatibilidad.

#### 7. Mantenimiento

Esta es una de las fases más importantes del ciclo de vida de desarrollo del Software. Puesto que el Software ni se rompo ni se desgasta con el uso, su mantenimiento incluye tres puntos diferenciados:

- Eliminar los defectos detectados durante su vida útil (mantenimiento correctivo).
- Adaptarlo a nuevas necesidades (mantenimiento adaptativo).
- Añadirle nuevas funcionalidades (mantenimiento perfectivo).

Aunque suene contradictorio, cuando mejor es el Software más tiempo hay que invertir en su mantenimiento. La principal razón es que se usará más (incluso de formas que no se habían previsto) y, por ende, habrá más propuestas de mejoras.

### Tipos de Organizaciones

Al hablar de organizaciones económicas comúnmente se piensa sólo en aquellas cuyo objetivo final es la generación de utilidades, pero en realidad existen organizaciones cuyos objetivos no se limitan a ese esquema.

A continuación las características de tres tipos de organizaciones económicas que juegan un papel relevante dentro de la actividad económica de un país:

- Organizaciones empresariales.
- Organizaciones sociales.
- Organizaciones gubernamentales.