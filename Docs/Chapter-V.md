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

Gherking : Lenguaje de dominio especializado utilizado en el Behavior Driven Development (BDD), diseñado para mejorar la comunicación entre equipos de negocios y técnicos al abordar problemas específicos. Emplea saltos de línea y palabras clave como "Given", "When", "Then" y "And" para mejorar la legibilidad y la organización de los escenarios en BDD, facilitando la estructuración clara y efectiva de diferentes tipos de casos. Estas prácticas nos ayudan a estructurar de manera clara y efectiva los diferentes tipos de escenarios en BDD.

### 5.1.4 Software Deployment Configuration

#### Landing Page Deployment

Para desplegar la landing page de TeamSync resultó necesario cumplir una serie de requisitos, entre ellos, es necesario contar con una cuenta personal, una organización y un repositorio al cual cargar los documentos (se utilizará la plataforma Github Pages y Github Actions, para la implementación y despegue). Cumplido lo anterior, será posible comenzar el despliegue de la landing page. Estos son los pasos a seguir:

<ol>
  <li>Crear una carpeta Docs para alojar el landing page y especificar en Github Pages como fuente de la página.
  </li>
  <li>Asegurarse de que los archivos sigan los terminales correctos "index.html", para la landing page; "style.css" para los estilos y una carpeta "img" que contendrá las imágenes.
  </li>
  <li>Cargar los archivos mediante un push a la rama main del repositorio.</li>
  <li>Verificar que se haya desplegado correctamente.</li>


</ol>

## 5.2 Landing Page, Services & Applications Implementation

### 5.2.1 Sprint 1

#### 5.2.1.1 Sprint Planning 1

<table>
  <caption>Sprint #1</caption>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Backlog</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fecha</td>
      <td>12/04/2024</td>
    </tr>
    <tr>
      <td>Hora</td>
      <td>17:00 horas (GMT -5)</td>
    </tr>
    <tr>
      <td>Ubicación</td>
      <td>Modalidad remota a través de plataforma Discord</td>
    </tr>
    <tr>
      <td>Preparado por</td>
      <td>Ventura Allasi, Randel</td>
    </tr>
    <tr>
      <td>Asistentes (a la reunión de planificación)</td>
      <td>Todos los miembros de DevOps-Upc</td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint n - 1 Review</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        Se creará la organización de DevOps-Upc en Github y el repositorio de la organización. Además, se implementará el single page landing page.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint n - 1 Retrospective</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        La implementación para el landing se ha realizado mediante html y css.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint Goal and User Stories</strong>
      </td>
    </tr>
    <tr>
      <td>Sprint 1 Velocity</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Sum of Story Points</td>
      <td>8</td>
    </tr>
  </tbody>
</table>


#### 5.2.1.2 Sprint Backlog 1

#### 5.2.1.3 Development Evidence for Sprint Review

A continuación se presentan informacion de los commits de la Landing page de TeamSync, con el uso de HTML, CSS y JavaScript.

<p align="center">
  <img src="../Assets/Img/Chapter V/gitflowLandingPage.png">
</p>

#### 5.2.1.4 Testing Suite Evidence for Sprint Review

<p align="justify">En el transcurso del primer sprint, no se realizaron pruebas en la aplicación ya que nuestro enfoque estuvo dirigido exclusivamente a la construcción de la página de inicio.</p>

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este sprint en particular, no hemos utilizado servicios web, ya que nos hemos concentrado exclusivamente en la creación de la página de inicio estática. Por lo tanto, en esta presentación no se proporciona documentación relacionada con la utilización de servicios web.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Hasta ahora, no hemos utilizado servicios web en el proceso de desarrollo de la página de inicio. Esto significa que no hemos realizado actividades como la creación de cuentas, la configuración de recursos en proveedores de servicios en la nube, la creación de proyectos de desarrollo para la integración o automatización de tareas de implementación, entre otras acciones relacionadas.

En cuanto al despliegue de la página de inicio, lo hemos realizado en la plataforma de Github Pages.

Se puede acceder a la página de inicio a través del siguiente enlace: https://DevOps-Upc.github.io/LandingPage/

#### 5.2.1.8. Team Collaboration Insights during Sprint

A continuación se presentan capturas de los insights del repositorio del landing page en Github

<p align="center">
  <img src="../Assets/Img/Chapter V/CapturaSprintReview1.png">

  <img src="../Assets/Img/Chapter V/gitflowLandingPage.png">
  
</p>

### 5.2.2 Sprint 2

#### 5.2.2.1 Sprint Planning 1


<table>
  <caption>Sprint #2</caption>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Backlog</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fecha</td>
      <td>18/04/2024</td>
    </tr>
    <tr>
      <td>Hora</td>
      <td>18:00 horas (GMT-5)</td>
    </tr>
    <tr>
      <td>Ubicación</td>
      <td>Modalidad remota a través de plataforma Discord</td>
    </tr>
    <tr>
      <td>Preparado por</td>
      <td>Morales Quispe, Brayan</td>
    </tr>
    <tr>
      <td>Asistentes a la reunión de planificación</td>
      <td>Todos los miembros de Dev-Ops</td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint n - 2 Review</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        Se creará el repositorio del Web Application, se asignarán secciones y tareas individuales a realizar para su desarrollo y el trabajo continuo para las correcciones del informe.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint n - 2 Retrospective</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        La implementación del Web Application se desarrolló con html, css, JavaScript y como framework: Vue.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint Goal and User Stories</strong>
      </td>
    </tr>
    <tr>
      <td>Sprint 2 Velocity</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Sum of Story Points</td>
      <td>8</td>
    </tr>
  </tbody>
</table>

#### 5.2.2.2 Sprint Backlog 2

En el segundo Sprint, se implementará la Web Application de Dev-Ops. La herramienta para gestionar a los miebros del equipo y visualizar los avanzes del proyecto será Trello.

<img src="../Assets/Img/Chapter V/sprintBacklog02.png" alt="Trello Sprint planning 02" width="100%">

Evidencia del Trello: 
https://trello.com/invite/b/RC9DLAsT/ATTIdcd2feef1cb600e47c6b08fd06407c8f3B139A41/dev-ops-sprint-02 

<div align ="center">
<table>
  <tr>
    <th>US Id</th>
    <th>Title</th>
    <th>WorkItem Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation(Hours)</th>
    <th>Assigned To</th>
    <th>Status(Todo/InProcess/ToReview/Done)</th>
  </tr>
  <tr>
    <td>US01</td>
    <td>Gestion de Cuenta</td>
    <td>TK01</td>
    <td>Creación de opciones para la gestión de la cuenta del usuario</td>
    <td>Implementar todas las opciones a desarrollar sobre la gestión de la cuenta del usuario</td>
    <td>6</td>
    <td>Sebastian</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US02</td>
    <td>Gestion de Perfil</td>
    <td>TK02</td>
    <td>Implementación de las opciones sobre el perfil del usuario</td>
    <td>Crear las opciones a desarrollar sobre la gestión del perfil del usuario</td>
    <td>6</td>
    <td>Gonzalo Andre</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US03</td>
    <td>Gestion de Bibliotecas</td>
    <td>TK03</td>
    <td>Creación de opciones para la gestión de las bibliotecas guardadas por usuario</td>
    <td>Implementar todas las opciones a desarrollar sobre la gestión de las bibliotecas del usuario</td>
    <td>4</td>
    <td>Fabian</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US04</td>
    <td>Revision de desarolllo</td>
    <td>TK04</td>
    <td>Revisión de la documentación y del avance de las implementacion</td>
    <td>Documentar e implementar todas las us desarrolladas sobre el usuario estudiante</td>
    <td>6</td>
    <td>Randel Ventura</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US05</td>
    <td>Gestion de Solicitudes</td>
    <td>TK05</td>
    <td>Creación de opciones para la gestión de las solicitudes del usuario</td>
    <td>Todas las opciones a crear sobre la gestión de las solicitudes del usuario estudiante</td>
    <td>6</td>
    <td>Gabriel Martel</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US05</td>
    <td>Gestion de Proyectos</td>
    <td>TK05</td>
    <td>Creación de opciones para la gestión de los proyectos del usuario</td>
    <td>Desarrollar todas las opciones a crear sobre la gestión de los proyectos del usuario estudiante</td>
    <td>8</td>
    <td>Brayan Smith</td>
    <td>Done</td>
  </tr>
</table>

</div>

#### 5.2.2.3 Development Evidence for Sprint Review


<p align="justify">A continuación se presenta  la tabla con la informacion de los commits dados para la Web Application de TeamSync, con el uso de HTML, CSS y JavaScript y Vue</p>

<table border="0" width="100%" height="100%">
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commited on</th>
  </tr>
  <tr>
    <td>TeamSync - Frontend</td>
    <td>develop</td>
    <td>1c23922a980579e72d882443b3c4d49823bbcbac</td>
    <td>feat: navbar</td>
    <td>23/04/2024</td>
  </tr>
   <tr>
    <td></td>
    <td>feat/experts</td>
    <td>da69f4f555e422402b0aecb71d5044b304bf6373</td>
    <td>feat(proyects): fix style toolbar and home commponent</td>
    <td>24/04/2024</td>
  </tr>
  <tr>
    <td></td>
    <td>feat/experts</td>
    <td>3ed58ac70fba5ac93635032ee181856f107ccb33</td>
    <td>feat(footer): added subscribe section in footer</td>
    <td>25/04/2024</td>
  </tr>
  <tr>
    <td></td>
    <td>feature/register-form:</td>
    <td>3062460a3a6bad39837b35f59ea14064b5f30d5a</td>
    <td>feat(register-form): added Register Form</td>
    <td>25/04/2024</td>
  </tr>
  <tr>
    <td></td>
    <td>feature/register-form:</td>
    <td>a42dea04f4bf6571f0409c65d9e337a4231e02f6</td>
    <td>feat(form-login): added form login</td>
    <td>26/04/2024</td>
  </tr>
  <tr>
    <td></td>
    <td>feature/especialists</td>
    <td>a6b9c0f3ec45231e74a78db230eb48c555b32229</td>
    <td>feat(specialists): added specialists adding function</td>
    <td>26/04/2024</td>
  </tr>
  <tr>
    <td></td>
    <td>feature/especialists</td>
    <td>511e1349ec64547faf9ec058b36b84a438a59398</td>
    <td>feat: index de los services</td>
    <td>26/04/2024</td>
  </tr>
  <tr>
    <td></td>
    <td>feature/especialists</td>
    <td>5e8cfa0e61ca39da6d150a304ac2c50f20dfe9e5</td>
    <td>feat: css de services</td>
    <td>26/04/2024</td>
  </tr>
   <tr>
    <td></td>
    <td>feature/especialists</td>
    <td>95d0e5d69e162c6805163ba5cbc179ee5c7d1a42</td>
    <td>feat(footer): added hover in icons</td>
    <td>26/04/2024</td>
  </tr>
  </table>


#### 5.2.2.4 Testing Suite Evidence for Sprint Review

<p align="justify">En el transcurso del segundo sprint, no se realizaron pruebas de testing en la Web Application ya que nuestro enfoque se dirigió exclusivamente a la construcción de la Aplicación Web.</p>

#### 5.2.2.5 Execution Evidence for Sprint Review

<p align="justify">A continuación se presentan capturas de la aplicacion web en Vue</p>

<img src="../Assets/Img/Chapter V/appExecutionImg1.jpg" alt="Imagen 01 Execution Evidence." width="100%">
<img src="../Assets/Img/Chapter V/appExecutionImg2.jpg" alt="Imagen 01 Execution Evidence." width="100%">

#### 5.2.2.6 Services Documentation Evidence for Sprint Review

<p>
Para el segundo sprint, se decidió enfocarse exclusivamente en la creación de la página de inicio y el desarrollo del front-end. Para evitar limitaciones en las pruebas debido a la falta de un back-end, se utilizó una API falsa (fake-api). Inicialmente, se trabajó con un servidor JSON local y luego se cambió a My JSON Server, el cual se emplea en la aplicación web front-end desplegada.
</p>


#### 5.2.2.7 Software Deployment Evidence for Sprint Review

<p align="justify">Se hizo uso de Firebase Hosting, un servicio publico de Google, dado que nos permitirá hospedar y desplegar nuestro sitio web de manera ágil y sencilla. Además, porque se podrá vincular con nuestro repositorio Git. </p>

<img src="../Assets/Img/Chapter V/firebase_Logo.png" alt="Logo Firebase" width="100%">


#### 5.2.2.8 Team Collaboration Insights during Sprint

<p align = "justify">A continuación se presentan capturas de los Insights del repositorio Github del Informe de documentación: </p>




<p> Link del repositorio del Informe del proyecto: 
<a> https://github.com/DevOps-Upc/TeamSync-InformeDeProyecto</a>
</p>

<p align = "justify">De la mimsma manera se presentan capturas de los Insights del repositorio Github del Frontend: </p>

<p> Link del repositorio del Frontend de la Web Application: <a> https://github.com/DevOps-Upc/teamsync-frontend </a> </p>

