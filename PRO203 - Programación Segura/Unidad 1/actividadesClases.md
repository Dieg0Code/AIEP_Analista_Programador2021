# Actividad

## ¿Que es QA?

QA es la abreviatura de *Quality Assurance*, es decir, la evaluación de la calidad de una aplicación. Es un conjunto de actividades que se realizan en el desarrollo de software para verificar que los requisitos de calidad de la aplicación se cumplan.

### ¿Que tipo de pruebas de software existen?

Las pruebas de software son mecanismos de evaluación de la calidad de una aplicación. Se centra en proporcionar información objetiva e independiente sobre la calidad de la aplicación.

Dependiendo del tipo de pruebas, estas actividades podrían ser implementadas en cualquier momento de dicho proceso de desarrollo. Existen distintos modelos de desarrollo de software, así como modelos de pruebas.

De manera general, existen dos tipos de pruebas de software:

- Las pruebas manuales: Son realizadas por personas que deben realizar las pruebas manualmente.

- Las pruebas automáticas: Son realizadas por programas que realizan las pruebas automáticamente mediante la ejecución de `test scripts` que ya han sido escritos previamente.

Los diferentes tipos de test pueden ser:

- **Unit tests**: Son pruebas que se realizan sobre una unidad de código. Muy utilizada en el **TDD** (Test Driven Development o Desarrollo guiado por pruebas).
- **Integration tests**: Las pruebas de integración verifican que los módulos y/o servicios funcionen correctamente en conjunto.
- **Funcional tests**: Las pruebas funcionales se centran en los requerimientos de negocio de la aplicación. Estas pruebas verifican la salida (resultado) de una acción, sin prestar atención a los estados intermedios del sistema mientras se lleva a cabo la ejecución.
- **End-to-end tests**: Las pruebas de end-to-end verifican que la aplicación funciona correctamente en un entorno de producción.
- **Regression testing**: Las pruebas de regresión verifican un conjunto de escenarios que funcionaron correctamente en el pasado, para asegurar que continúen así.
- **Smoke tests**: Las pruebas de humo son pruebas que verifican la funcionalidad básica de una aplicación. Se pretende que sean pruebas rápidas de ejecutar y su objetivo es asegurar que las características mas importantes del sistema funcionan correctamente.

### ¿Que son las pruebas de caja negra y caja blanca?

Las pruebas de caja negra, es una técnica de pruebas de software en la cual la funcionalidad se verifica sin tomar en cuenta la estructura interna de código, detalles de implementación o escenarios de ejecución internos en el software

Las pruebas de caja blanca (también conocidas como pruebas de caja de cristal o pruebas estructurales) se centran en los detalles procedimentales del software, por lo que su diseño está fuertemente ligado al código fuente. El ingeniero de pruebas escoge distintos valores de entrada para examinar cada uno de los posibles flujos de ejecución del programa y cerciorarse de que se devuelven los valores de salida adecuados.

### ¿Como implementar la ISO 27001?

La ISO 27001 es una norma internacional creada por la Organización Internacional de Normalización (ISO) para garantizar buenas prácticas de seguridad de la información.

La implementación de un sistema de gestión de seguridad de la información que garantice la integridad y confidencialidad de la información y se ajuste a las necesidades de la organización, requiere seguir estos pasos:

1. Obtener el compromiso de la dirección.
2. Definir el alcance.
3. Conformar el equipo de trabajo.
4. Crear un plan de implementación.
5. Realizar un análisis de brechas.
6. Evaluar riesgos.
7. Implementar controles, procedimientos y programas de capacitación.
8. Monitoreo y auditoría.

### ¿Como implementar la ISO 9000?

ISO 9000 designa un conjunto de normas sobre calidad y gestión continua de calidad, establecidas por la Organización Internacional para la estandarización (ISO).

1. Entender los elementos básicos de la ISO 9000.
2. Analizar la situación actual de la organización, dónde está y dónde debe llegar.
3. Construir desde cada acción puntual un Sistema de Gestión de la Calidad.
4. Documentar los procesos que sean requeridos por la norma.
5. Detectar las necesidades de capacitación propias de la empresa.
6. Realizar Auditorías Internas.
7. Utilizar el Sistema de Calidad (SGC), registrar su uso y mejorarlo durante varios meses.
8. Solicitar la Auditoría de Certificación.

## ¿Repositorios de código existentes?

Los mas conocidos y usados son GitHub, Bitbucket y GitLab. Sin embargo existen [otros](https://www.neoguias.com/alternativas-github/) como SourceForge, Kiln, Codeplane, CodePlex, Beanstalk, SVN, etc.

### ¿Diferencias entre repositorios?

#### **GitHub**

Tiene una interfaz de usuario simple que rápidamente lleva a los desarrolladores a trabajar con algoritmos de Git. Otra característica definitoria es su velocidad: el servicio empuja y extrae solicitudes y fusiona versiones rápidamente.

La versión gratuita de GitHub permite a los desarrolladores trabajar con repositorios públicos y privados, contribuir a ellos y colaborar. El costo depende del número de usuarios.

#### **GitLab**

GitLab se fundó en 2011 como una alternativa a GitHub y BitBucket. Su principal punto de venta es una amplia funcionalidad, que está perfectamente empaquetada en una gran interfaz de usuario independientemente de su versatilidad.

Recientemente, los equipos han estado cambiando activamente a GitLab desde otros servicios. Particularmente debido al soporte perfecto de GitLab para la canalización de CI (Integración continua) y Docker.

#### **BitBucket**

Al igual que GitHub, BitBucket se lanzó en 2008. Fue creado por un equipo australiano y luego adquirido por Atlassian en 2010. Sin embargo, el servicio no admitía el control de versiones basado en Git hasta 2011.

El principal punto de venta de BitBucket es la posibilidad de alojar un número ilimitado de repositorios privados para equipos pequeños (de 1 a 5 usuarios). Sin embargo, la interfaz de usuario de Bitbucket originalmente no era tan sencilla como la de GitHub y la funcionalidad estaba poco desarrollada. Ahora, sin embargo, los dos servicios se están volviendo cada vez más similares, y la popularidad de BitBucket está creciendo.

### Ventajas y desventajas

#### **GitHub..**

Ventajas:

- Servicio gratuito, aunque también tiene servicios de pago.
- Repositorios públicos y privados.
- Actualmente le pertenece a Microsoft.

Desventajas:

- No es absolutamente abierto.
- Tiene limitaciones de espacio, ya que no puedes exceder de 100MB en un solo archivo, mientras que los repositorios están limitados a 1GB en la versión gratis.

#### **GitLab..**

Ventajas:

- Plan gratuito y sin limitaciones, aunque tiene planes de pago.
- Es de código abierto.
- Está muy bien integrado con git.

Desventajas:

- Su interfaz puede ser algo mas lenta comparada con la competencia.
- Nos llena la vista de más información de la necesaria, por lo que la página a veces resulta de difícil comprensión.

#### **BitBucket..**

Ventajas:

- Repositorios privados para equipos pequeños. Equipos pequeños, hasta 5 integrantes, pueden obtener un número ilimitado de repositorios.
- Tiene un enfoque empresarial de Bitbucket significa que encontrará funciones como la lista blanca de IPs y verificación en dos pasos para dar a los administradores mayor control sobre quién puede ver, enviar o clonar un repositorio de código privado.

Desventajas:

- No es de código abierto.

### ¿Que es una rama en Git?

Una rama en Git es una bifurcación de un repositorio. Una rama es una versión de un repositorio, y es una forma de mantener una copia de este en un estado específico, sin modificar el original. Las ramas o **branchs** son de uso común, por lo general se tiene la rama **master** o **main** la cual es la rama principal y la rama **development**, en donde se hacen los cambios, luego de testearlos, se integran los cambios realizados en la rama **development** a la rama **main** para que los cambios sean publicados.

## OWASP top 10

### Buscar 2 soluciones para cada vulnerabilidad

#### 1. Tips para evitar [SQL Injection](https://www.owasp.org/index.php/SQL_Injection):

- `Usar sentencias preparadas (con consultas parametrizadas)`: El uso de sentencias preparadas con variables vinculadas (también conocidas como consultas parametrizadas) es la forma en que todos los programadores deberían escribir sus consultas SQL. Parametrizar las consultas fuerza al desarrollador a primero definir todo el código SQL, y luego pasar cada parámetro a la consulta luego.

Hacer esto asegura que un atacante no pueda modificar la intención de una consulta, incluso si intenta introducir una sentencia SQL maliciosa.

Ejemplo Java EE - PreparedStatement( ):

```java
String custname = request.getParameter("customerName");
// Consulta SQL
String query = "SELECT account_balance FROM user_data WHERE user_name = ?";
// Preparar la consulta
PreparedStatement pstmt = connection.prepareStatement(query);
pstmt.setString(1, custname);
ResultSet results = pstmt.executeQuery();
```

La consulta SQL se define en una variable, y se pasa como parámetro luego.

- `Procedimientos almacenados`: Los procedimientos almacenados tienen el mismo efecto que las consultas parametrizadas. La diferencia es que los procedimientos almacenados son definidos y almacenados en la base de datos, y son llamados desde la aplicación.

```java
String custname = request.getParameter("customerName");
try {
    // Consulta SQL
    CallableStatement cstmt = connection.prepareCall("{call sp_getAccountBalance(?)}");
    cstmt.setString(1, custname);
    ResultSet results = cstmt.executeQuery();
} catch (SQLException e) {
    // error handling
}
```

#### 2. Tips para Broken Authentication:

- Donde sea posible, implementar autenticación multi-factor para prevenir ataques automatizados, fuerza bruta, credenciales robadas, etc.
- Implementar un chequeo de contraseñas débiles, comprobar la seguridad de la contraseña en base al [top 1000 peores contraseñas](https://github.com/danielmiessler/SecLists/tree/master/Passwords).

#### 3. Tips para Sensitive Data Exposure:

- Clasificar la data procesada, almacenada o transmitida por la aplicación. Identificar cual data es sensible de acuerdo con las leyes de privacidad, requerimientos regulares, o necesidades del negocio.
- Asegurarse de encriptar la data sensible.

#### 4. Tips para XML External Entities (XXE):

- Cuando sea posible, usar formatos menos complejos como JSON, y evitar serializar data sensible.
- Parchear o actualizar todos los procesadores XML y librerías que usa la aplicación o el sistema operativo. Usar *dependency checkers*. Actualizar SOAP a SOAP 1.2 o superior.

#### 5. Tips para Broken Access Control:

- Con la excepción de recursos públicos, denegar por defecto todo acceso a los usuarios que no están autorizados.
- Implementar mecanismos de control de acceso una vez y luego reusarlos a través de la aplicación.

#### 6. Tips para Security Misconfigurations:

- Tener una plataforma mínima sin ninguna funcionalidad innecesaria. Remover o desintalar cualquier componente innecesario.
- Los entornos de desarrollo, QA y producción deben tener la misma configuración, con las respectivas diferentes credenciales usadas en cada ambiente.

#### 7. Tips para Cross-Site Scripting (XSS):

- Usar frameworks los cuales tengan protección contra XSS por defecto, como Ruby on Rails, React JS, etc.
- Descartar peticiones HTTP no confiables en el contexto del HTML output.

#### 8. Tips para Insecure deserialization:

- Implementar controles en las entradas de datos, como firmas digitales o cualquier objeto serializado para prevenir la creación de objetos hostiles o la manipulación de datos.
- Monitoreo de las deserializaciones de datos, alertar si un usuario intenta hacerlo constantemente.

#### 9. Tips para Using Components with Known Vulnerabilities:

- Remover dependencias sin usar, funcionalidades innecesarias, componentes, archivos y documentación innecesaria.
- Obtener componentes solo de fuentes oficiales mediante links seguros. Preferir paquetes firmados para reducir el chanse de incluir un componente malicioso modificado.

#### 10. Tips para Insufficient Logging and Monitoring:

- Asegurar todos los loggins, las fallas de control de acceso, y verificar toda data procesada por el servidor.
- Asegurar que todos los logs sean registrados en un formato el cual pueda ser consultado fácilmente.