# Capítulo V Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

<strong>Requirements Management</strong> 
<ol>
  <li>Trello: Es una herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente basados en marcos detrabajos ágiles. Será empleado para visualizar y actualizar el estado actual de las tareas e historias de usuariopertenecientes al sprint a desarrollar. Ruta de referencia https://trello.com/es</li>
</ol>

<strong>Product UX/UI Design</strong>
<ol>
  <li>Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizado para el diseño digital. En elcaso del proyecto, será utilizado para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.Ruta de referencia https://www.figma.com/login2.</li>
  <li>Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama declases asociado a la aplicación. Ruta de referencia https://www.lucidchart.com/</li>
</ol>

<strong>Software Testing</strong>
<ol>
  <li>Gherkin: Sistema de etiquetado utilizado para   describir los criterios de aceptación de estructura de una user story.Ruta de referencia https://cucumber.io/docs/gherkin/</li>
</ol>

<strong>Software Development</strong>
<ol>
  <li>WebStorm: Entorno de desarrollo integrado elegido para la elaboración y compilación del código por motivos dedominio por parte de los integrantes del equipo de trabajo. Utilizar este IDE supone de valor para el desarrollo del proyecto puesto que incluye la posibilidad de agregar extensiones de utilidad, soporte de edición de texto en múltipleslenguajes de programación, disponibilidade en múltiples sistemas operativos, entre otros beneficios. Ruta de referencia https://www.jetbrains.com/webstorm/
  </li>

  <li>HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Será empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación. Ruta de referencia https://www.w3schools.com/html/html5_syntax.asp
  </li>

  <li>CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la manocon HTML. Ruta de referencia https://google.github.io/styleguide/htmlcssguide.html
  </li>
  <li>JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz deusuario dentro de la aplicación. Ruta de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript 
  </li>
  <li>Vertabelo: Herramienta para el modelado de bases de datos relacionales. Permite a los usuarios diseñar, mantener y documentar bases de datos de manera eficiente y colaborativa. Con Vertabelo, creamos diagramas de entidad-relación (ER) y diagramas de modelo relacional utilizando una interfaz intuitiva basada en la web.
  </li>
  <li>Vue: Vue.js es un framework progresivo de JavaScript utilizado para construir interfaces de usuario interactivas y de una sola página (Single Page Applications o SPAs). Se centra en la capa de vista de una aplicación web, lo que significa que se utiliza principalmente para manejar la interfaz de usuario y las interacciones del usuario. Se basa en el patrón de diseño Modelo-Vista-Controlador (MVC) y proporciona un enfoque reactivo para actualizar la interfaz de usuario en función de los cambios en los datos. Ruta de referencia: https://primevue.org/ 
  </li>
</ol>
<strong>Software Deployment</strong>
<ol>
  <li>Git: Herramienta de control de versiones que permite registrar y gestionar las diferentes versiones del programa. Seutilizará para mantener un historial de cambios y simplificar la corrección de errores. Los miembros del equipo accederána través de la línea de comandos en sus sistemas locales. Ruta de referencia https://git-scm.com/
  </li>
</ol>

<strong> Software Documentation and Project Management </strong>

<ol>
  <li>Github: Plataforma basada en la nube que alojará los repositorios de código del proyecto. Facilitará la colaboración entiempo real y la revisión de contribuciones de cada miembro del equipo. Los miembros del equipo accederán a través desus navegadores web. Ruta de referencia https://github.com/
  </li>
</ol>

### 5.1.2. Source Code Management

Nuestro proyecto seguirá los lineamientos del modelo GitFlow para controlar las versiones, donde utilizaremos GitHub como plataforma y sistema para el control de dichas versiones. Links del repositorio de GitHub:

- Link de la organización: https://github.com/DevOps-Upc
- Link de la landing page: https://github.com/DevOps-Upc/TeamSync-LandingPage
- Link del informe: https://github.com/DevOps-Upc/TeamSync-InformeDeProyecto
- Link del Front-end: https://github.com/DevOps-Upc/TeamSync-Frontend
- Link del Back-end: https://github.com/DevOps-Upc/TeamSync-Backend

Estructura de las ramas:

- Main Branch: Rama principal de la aplicación. Se encuentran las versiones más actualizadas y estables de desarrollo, por medio de un proceso de admisión se agregan cambios de otras ramas derivadas.

- Develop Branch: Esta rama es donde se reunen de las demás ramas los avances del proyecto y desarollo. Se evalúan todos los cambios para ser registradas posteriormente en nuestra rama main.

- CapituloI Branch: En esta rama se actualizará toda la información y documentación del capítulo I del producto presentado.


- CapituloII Branch: En esta rama se actualizará toda la información y documentación del capítulo II del producto presentado.


- CapituloIII Branch: En esta rama se actualizará toda la información y documentación del capítulo III del producto presentado.

- CapituloIV Branch: En esta rama se actualizará toda la información y documentación del capítulo IV del producto presentado.

- CapituloV Branch: En esta rama se actualizará toda la información y documentación del capítulo V del producto presentado.

### 5.1.3 Source Code Style Guide & Conventions

HTML: Varias de las mejores prácticas que hemos seguido para alcanzar un código limpio, ordenado, legible y escalable son mostradas a continuación:

- Se usan elementos HTML que tengan un significado claro y  preciso para el contenido que se está marcando. Por ejemplo, utiliza header, nav, main, article, section, aside, footer, entre otros, al estructurar la landing page, sin redundancia, por algún uso incorrecto o querer reinventar la rueda.
- HTML5 permite algunas etiquetas sin cierre (como "img" y "input"), sin embargo utilizamos la buena práctica de cerrar todas las etiquetas correctamente para evitar problemas de renderizado. Por ejemplo:``` <p> Hola! Somos DevOps-Upc!.</p>```
- Para mejorar la accesibilidad a nuestras clases, siempre incluimos el atributo alt en las etiquetas, "img" por ejemplo, para describir brevemente el contenido de la imagen. Por ejemplo: ```<img src="image.img" alt="nombre corto de imagen">```
- En HTML, es posible utilizar tanto mayúsculas como minúsculas en los nombres de elementos y atributos, pero nosotros utilizamos solo minúsculas para mantener el orden y facilitar la legibilidad del código.
- No omitir etiquetas principales e importantes como ```<html>```, ```<body>```,  ```<header>``` y más.
- Escribir en una línea los comentarios cortos.

CSS: Entre nuestras prácticas están:

- Los nombres de clases son claros, precisos y autodescriptivos.
- Separar los nombres de las clases y ID con guión, por ejemplo: ```#userWorker-id``` o ```button-shape{}```.
- Usar comentarios claros para explicar el código.
- Aplicar sangría al contenido de un bloque entero.
- Separar las declaraciones y selectores en nuevas líneas para tener una buena legibilidad y orden.

JavaScript: Principales buenas prácticas:

- Uso de prácticas de nomenclatura, en este caso camelCase para nombrar únicas variables y funciones. Por ejemplo, ```miVariable``` o ```miFuncion```.
- Uso de PascalCase para nombrar clases y constructores.Por ejemplo, ```MiClase```.
- Evitamos el uso de nombres de variables genéricos o ambiguos.
- Uso general de comentarios para explicar el propósito y funcionalidad de la porción del código.
- Uso de punto y coma al final de cada declaración.
- Uso de comillas simples ('') o comillas dobles ("") de forma consistente para las cadenas de texto.
- Uso de operadores ternarios, por ejemplo, ```(condición ? resultadoTrue : resultadoFalse)``` de manera cuidadosa según la legibilidad y dificultad del bloque de código.
- Evitación y eliminación del uso de funciones obsoletas o en desuso.
- Uso de ```try-catch``` para manejar y gestionar errores.
- Organización del código en bloques lógicos separados por líneas en blanco para mejorar la legibilidad.

Gherking : Lenguaje de dominio especializado utilizado en el Behavior Driven Development (BDD), sdiseñado para mejorar la comunicación entre equipos de negocios y técnicos al abordar problemas específicos. Emplea saltos de línea y palabras clave como "Given", "When", "Then" y "And" para mejorar la legibilidad y la organización de los escenarios en BDD, facilitando la estructuración clara y efectiva de diferentes tipos de casos. Estas prácticas nos ayudan a estructurar de manera clara y efectiva los diferentes tipos de escenarios en BDD.

### 5.1.4 Software Deployment Configuration


## 5.2 Landing Page, Services & Applications Implementation

### 5.2.1 Sprint 1

#### 5.2.1.1 Sprint Planning 1

Sprint #1 <br>

#### 5.2.1.2 Sprint Backlog 1

#### 5.2.1.3 Development Evidence for Sprint Review

A continuación se presentan informacion de los commits de la Landing page de TeamSync, con el uso de HTML, CSS y JavaScript.

#### 5.2.1.4 Testing Suite Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint

