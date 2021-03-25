# Notas Fundamentos de la Programación

##### profesor: Antolin Muñoz

##### Correo Profesor: antolin.munoz@correoaiep.cl

##### AIEP Osorno - Marzo 2021

### Contenidos

- Pseudolenguaje y elementos básicos de la programación estructurada, consideran estructuras básicas que conforman un algoritmo.
- DFD, considerando componentes básicos de una programación estructurada.
- Scratch como lenguaje de programación visual.
- Herramientas para la programación.

## Unidad 1: Algoritmos y programación en Pseudolenguaje

### Términos que debemos conocer

#### **Informática**

Informática (Ciencia de la computación) Conjunto de conocimientos científicos y técnicas que hacen posible el tratamiento automático de la información por medio de ordenadores.

#### **Computador**

Maquina electrónica, analógica o digital, dotada de una memoria de gran capacidad y métodos de tratamiento de la información, capaz de resolver problemas matemáticos y lógicos mediante la ejecución de programas informáticos.

#### Contextualicemos

La computación y la informática se encuentra en muchas partes de nuestra vida. Desde levantarnos y tener nuestro dia programado, hasta apagar o encender el televisor, lavadora, etc. o nuestro dispositivo móvil. Desde un simple sistema informático hasta un satélite que procesa y enviá información al instante.

#### **Hardware**

Componentes que integran la parte material o física de un computador.

#### **Software**

Programas, instrucciones y reglas informáticas para ejecutar tareas en una computadora.

#### **Programar**

Indicar a la computadora qué es lo que tiene que hacer

#### **Programa**

- Secuencia de instrucciones
- Instrucciones que entiende la computadora
- Y que persiguen un objetivo: ¡resolver un problema!

#### **Programadores y equipo multidisciplinario con Múltiples roles**

- Gestores
- Analistas
- Diseñadores
- Programadores
- Testers
- Administradores de sistemas

### La Arquitectura de un Computador

Un computador no solo se compone por una parte física y lógica, sino que también cuenta con una arquitectura fundamental para su funcionamiento, la cual es comprender cualquier instrucción, procesar y tener resultados de la misma en el menor tiempo posible.

Para esto existen diferentes componentes y uno de los mas importantes que nos permite interactuar con el hardware es la CPU.

#### **La CPU puede dividirse funcionalmente en 3 subunidades:**

- La unidad de control, dedicada a ciclos de búsqueda y ejecución.
- La ALU (Arithmetic - Logic Unit) que desempeña funciones aritméticas como por ejemplo, suma y resta, y de lógica por ejemplo AND, OR.
- Y un conjunto de registros dedicados al almacenamiento de datos en la CPU y a ciertas funciones de control.

La CPU contiene un conjunto de localidades de almacenamiento temporal de datos de alta velocidad llamada registro. Algunos de los registros están dedicados al control, y solo la unidad de control tiene acceso a ellos. Los registros restantes son los registros de uso general y el programador es el usuario que tiene acceso a ellos.

- Contador de programa (PC).
- Registro de direcciones de la memoria(MAR - Memory Address Register).
- Registro de datos (RD).
- Registro de instrucciones (ER).
- Palabra de estado de programa (PSW).

En el registro de instrucciones de una unidad de procesamiento (CPU) podemos encontrar clasificaciones las cuales nos permiten realizar tareas, el cual es un registro que conserva el código de operación de la instrucción en todo el ciclo de la maquina.

Se clasifican en 5 categorías:

- Instrucciones de aritmética y lógica.
- Instrucciones de movimientos de datos.
- Operaciones de datos en bloques.
- Instrucciones de control del programa.
- Instrucciones de Entrada - Salida.

Instrucciones de Aritmética y Lógica:

- Operaciones binarias, las cuales requieren dos operadores y producen un resultado único.
- La suma, la resta, la multiplicación, y division, son operadores standard en la mayor parte de las maquinas.
- Las operaciones de lógica incluidas en el conjunto de instrucciones son las operaciones AND, NAND, NOR, XAND, XOR.
- También dentro de las instrucciones de aritmética y lógica se encuentra las operaciones de desplazamiento y las de rotación.

![arquitectura de un computador](img/PRO101ArquitecturaDeUnComputador.png)
![esquema general de un computador](img/PRO101EsquemaGeneralDeUnComputador.png)

### La Arquitectura de Von Neumann

Conocida como modelo Von Neumann, es una arquitectura de computadoras basada en la descrita en 1945 por el matemático y físico John Von Neumann y otros.

Este describe una arquitectura de diseño para una computador digital electrónico con partes que constan de una unidad de procesamiento, unidad aritmético lógica y registros del procesador, unidad de control que contiene un registro de instrucciones y un contador de programa, una memoria para almacenar tanto datos como instrucciones, almacenamiento masivo externo, y mecanismos de entrada y salida.

- Una ALU (Unidad Aritmética-Lógica) es un circuito que permite, como su nombre lo indica, realizar operaciones lógicas y aritméticas.
- Ademas de los operadores lógicos y aritméticos, la ALU cuenta con una serie de registros para almacenar los datos y bits de información sobre los resultados, también llamados banderas.
- Las banderas mas comunes son: Carry, Auxiliary Carry, Borrow, Overflow, Parity, Zero.

![arquitecura de von neumann](img/PROP101ArquitecturaDeVonNeumann.png)

### La Programación de Bajo Nivel

**Los procesadores trabajan con ceros y unos (bits)**.

Unidad de memoria basica: Byte (8 bits) (2 dígitos hexadecimales: 01011011 -> 0101 1011 -> 5B).

#### **Lenguaje Máquina**

Códigos hexadecimales que representan instrucciones, registros de la CPU, direcciones de memoria o datos Instrucción - Significado

- A0 2F Acceder a la celda de memoria.
- 2F 3E 01 Copiar el registro 1 de la ALU.
- A0 30 Acceder a la celda de memoria.
- 30 3E 02 Copiar en el registro 2 de la ALU 1D Sumar.
- B3 31 Guardar el resultado en la celda de memoria 31.

![Arquitectura de Von Neumann 2](img/PRO101ArqVonNeumann2.png)

#### **Ensamblador:**

El lenguaje **ensamblador** o assembly (.asm) es un lenguaje de **programación** de bajo nivel. Consiste en un conjunto de **mnemónicos** que representan instrucciones básicas para los computadores, microprocesadores, microcontroladores y otros circuitos integrados programables.

Este permite la traducción de una instrucción a lenguaje maquina.

![Programacion de bajo nivel](img/PRO101ProgramacionDeBajoNivel.png)