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
A continuacion mostrare pruebas ejecucion del landing page.
![](/Assets/Img/Chapter%20V/ecidencia%20landigpage2.png)
Como se puede evidenciar el despliege fue correcto y con un funcionamiento al 100%

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
No contamos pruebas de documentacion debido a la razon mencionada anteriormente.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
El deploymento del landing page se realizó mediante GithubPages.
![](/Assets/Img/Chapter%20V/evidencia%20landingpage.png)
Como se puede evidenciar nuestro despliege fue realizado en GitHubPages por su facilidad.
**Link:** [https://devops-upc.github.io/TeamSync-LandingPage/](https://devops-upc.github.io/TeamSync-LandingPage/)
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

### 5.2.3 Sprint 3

#### 5.2.3.1 Sprint Planning 3

<table>
  <tr>
    <th>Sprint #</th>
    <td>3</td>
  </tr>
  <table>
  <caption>Sprint #3</caption>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Backlog</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fecha</td>
      <td>05/06/2024</td>
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
        En el Sprint anterior, la meta fue el desarrollo del FrontEnd Web Application. En este FrontEnd se mostro la interfaz del cliente con sus datos y  ahora se puede manejar diferentes projectos.
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
      <td>Resumen</td>
      <td>
        	La meta de este Sprint es la mejora del FrontEnd Web Application y tambien el desarrollo de la primera versión del Web Services
      </td>
    </tr>
    <tr>
      <td>Sprint 2 Velocity</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Sum of Story Points</td>
      <td>18</td>
    </tr>
  </tbody>
</table>
<h3>5.2.3.2. Sprint Backlog 3</h3>

En nuestro tercer sprint, nos enfocamos en desarrollar una versión inicial de nuestro backend, estableciendo la estructura que emplearemos para el proyecto. Asimismo, incorporamos más funcionalidades en el frontend y optimizamos tanto el proceso de registro como el de inicio de sesión en la aplicación. Además, logramos completar la mayoría de las tareas que nos propusimos para este sprint.

<div align ="center">
<table border="1">
  <tr>
    <th>Sprint #</th>
    <th>User Story</th>
    <th>Work-item/Task</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status (To-do / In-Process / To-Review / Done)</th>
  </tr>
  <tr>
    <td rowspan="3">Sprint 3</td>
    <td rowspan="3">Registro de usuario en la base de datos</td>
    <td>TA01</td>
    <td>Modelado de datos del usuario</td>
    <td>Definir un modelo de datos para el usuario en el sistema de gestión de bases de dato.</td>
    <td>2</td>
    <td>Brayan Morales</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Creación de la API de registro</td>
    <td>Implementación de un endpoint en la API que acepte solicitudes POST para crear un nuevo usuario.</td>
    <td>4</td>
    <td>Brayan Morales</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA03</td>
    <td>Validación de datos</td>
    <td>Implementación de validación de los datos enviados a la API de registro.</td>
    <td>4</td>
    <td>Brayan Morales</td>
    <td>Done</td>
  </tr>
  
  <tr>
    <td rowspan="2">Sprint 3</td>
    <td rowspan="2">Obtención de los datos personales del usuario</td>
    <td>TA01</td>
    <td>API de perfil de usuario</td>
    <td>Implementar un endpoint en la API que acepte solicitudes GET para obtener los datos del perfil del usuario.</td>
    <td>4</td>
    <td>Gabriel Martel </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Recuperación de datos del usuario</td>
    <td>Cuando se recibe una solicitud en el endpoint de perfil de usuario, buscar al usuario en la base de datos.</td>
    <td>4</td>
    <td>Gabriel Martel</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="3">Sprint 3</td>
    <td rowspan="3">Obtención de las credenciales del usuario</td>
    <td>TA01</td>
    <td>API de inicio de sesión</td>
    <td>Implementación de un endpoint en la API que acepte solicitudes POST para iniciar sesión.</td>
    <td>4</td>
    <td>Sebastian Bustinza</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Validación de credenciales</td>
    <td>Verificar que las credenciales proporcionadas por el usuario coincidan con las almacenadas en la base de datos.</td>
    <td>4</td>
    <td>Sebastian Bustinza</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA03</td>
    <td>Generación de tokens</td>
    <td>Generar un token con JWT, json web token, que permita al usuario autenticarse en futuras solicitudes.</td>
    <td>3</td>
    <td>Gabriel Martel</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">Sprint 3</td>
    <td rowspan="2">Almacenamiento de la foto de perfil</td>
    <td>TA01</td>
    <td>API de carga de imagen</td>
    <td>Implementa un endpoint en la API que acepte solicitudes POST para cargar la imagen de perfil del usuario.</td>
    <td>3</td>
    <td>Brayan Morales</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Almacenamiento de la imagen</td>
    <td>Cuando se recibe una solicitud en el endpoint de carga de imagen esta se almacena en la base de datos</td>
    <td>3</td>
    <td>Fabian</td>
    <td>Done</td>
  </tr>
   <tr>
    <td rowspan="1">Sprint 3</td>
    <td rowspan="1">Creacion bounded Context de los grupos</td>
    <td>TA01</td>
    <td>API de grupos</td>
    <td>Definir los límites claros y específicos dentro del sistema donde los grupos operan, estableciendo sus responsabilidades, interacciones y reglas de negocio</td>
    <td>4</td>
    <td>Gonzalo Quedena </td>
    <td>Done</td>
    <tr>
    <td rowspan="1">Sprint 3</td>
    <td rowspan="1">Creacion bounded Context de los Proyectos</td>
    <td>TA01</td>
    <td>API de proyectos</td>
    <td>Establecer límites claros entre las responsabilidades y funcionalidades de cada equipo.</td>
    <td>4</td>
    <td>Randel Ventura </td>
    <td>Done</td>
  
</table>

</div>

<h3>5.2.3.3. Development Evidence for Sprint Review</h3>
En esta sección se presentan los avances de implementación con relación a los productos desarrollados en el presente Sprint. La implementación de la segunda version del Web Application Front End  y BackEnd. Se implementaron ramas a partir de la rama develop para que cada integrante. <br><br>

![capture](/Assets/Img/Chapter%20V/sprint%203/sprint3capture.PNG)






<h3>5.2.3.4. Testing Suite Evidence for Sprint Review</h3>

Hemos desarrollado un conjunto de pruebas automatizadas que cubren los Endpoints relacionados con los User Stories definidos para este Sprint. Estas pruebas incluyen Unit Tests, Integration Tests y Acceptance Tests para garantizar la calidad y la funcionalidad de nuestros Web Services.

![test1](/Assets/Img/Chapter%20V/sprint%203/testlogin.png)
![test2](/Assets/Img/Chapter%20V/sprint%203/testsignup.png)

<h3>5.2.3.5. Execution Evidence for Sprint Review</h3>

Vistas implementadas para este sprint se realizaron para los segmentos:

![deployBackEnd](/Assets/Img/Chapter%20V/sprint%203/backEnd-Captura%201.png)
Como se puede apreciar para esta entrega se desarrollaron los siguientes endPoints FileAsset y Project.

[Link Para El BackEnd](https://teamsync-wa.azurewebsites.net/swagger/index.html)

<h3>5.2.3.6. Services Documentation Evidence for Sprint Review</h3>

|EndPoint|Http Verb|Action|
|---|---|---|
|https://teamsync-wa.azurewebsites.net/api/v1/file-asset| Post|Agregar un FILE a un projecto determinado|
|https://teamsync-wa.azurewebsites.net/api/v1/file-asset/project/{projectId}|Get|Obtener todos los archivos relacionados con un projecto.|
|https://teamsync-wa.azurewebsites.net/api/v1/project|Post|Crear un projecto nuevo |
|https://teamsync-wa.azurewebsites.net/api/v1/project/profile/{profileId}|Get|Obtener los projectos teniendo en cuenta el id del perfil|
|https://teamsync-wa.azurewebsites.net/api/v1/project{ProjectId}|Get|Obtener projecto por id|
|https://teamsync-wa.azurewebsites.net/api/v1/project/{ProjectId}/{ProfileId}|Delete|borrar projecto con id del projecto y perfil id.|

Hemos desarrollado una serie de endpoints para la gestión de roles y usuarios en nuestra aplicación. 
<h3>5.2.3.7. Development Evidence for Sprint Review</h3>
<br>
A continuación procederemos a mostrar los pasos del deployment de la aplicación backEnd.

![Imagen de la base de datos](/Assets//Img/Chapter%20V/sprint%203/prueba%20de%20despliege%201.jpg)

aqui se muestra la configuracion de nuestra base de datos desplegada en azure con su configuracion establecida.

![Imagen de la backEnd](/Assets/Img/Chapter%20V/sprint%203/prueba%20de%20despliege%202.jpg)
Se muestra el despliege y configuracion de la backend en azure.

<h3>5.2.2.8. Team Collaboration Insights durante el Sprint</h3><br>
Se creó una organización en GitHub con un dominio público para que el profesor pueda visualizar el proyecto.<br>

Cabe destacar la participación activa de todo el equipo en el desarrollo del proyecto, abarcando desde el Landing Page hasta las capas técnicas del Frontend y Backend, como se evidencia en las imágenes que muestran sus commits. *Team Collaboration Insights* se erige como un recurso fundamental, no solo para comprender la eficacia del equipo desde una perspectiva técnica, sino también para apreciar el esfuerzo conjunto que ha llevado al éxito del proyecto.


<br>


BackEnd Web Application
<br>

![](/Assets/Img/Chapter%20V/sprint%203/Commits%20barras.png)
<br>
La cantidad de commits realizados por el integrante Brayan Smith en la backend

![](/Assets/Img/Chapter%20V/sprint%203/linea%20de%20tiempo.png)
<br>
Linea de tiempo de los commits realizados antes de la fecha de entrega aplicando gitflow.

### 5.2.3 Sprint 4

#### 5.2.3.1 Sprint Planning 4

<table>
  <tr>
    <th>Sprint #</th>
    <td>4</td>
  </tr>
  <table>
  <caption>Sprint #4</caption>
  <thead>
    <tr>
      <th colspan="2">Sprint Planning Backlog</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fecha</td>
      <td>15/06/2024</td>
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
        <strong>Sprint n - 3 Review</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        En el Sprint anterior, la meta fue el desarrollo del FrontEnd Web Application.La creación del Backend. En este FrontEnd se mostro la interfaz del cliente con sus datos y  ahora se puede manejar diferentes projectos. Adicionalmente, añadimos 2 endpoints y nos dimos cuenta que necesitábamos más comunicación en el equipo.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint n - 3 Retrospective</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        La implementación del Web Application se desarrolló con html, css, JavaScript y como framework: Vue. Adicional para el Backend utilizamos Rider como IDE, se desarrolló en C#, como framework ASP.NET Core.
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <strong>Sprint Goal and User Stories</strong>
      </td>
    </tr>
    <tr>
      <td>Resumen</td>
      <td>
        	La meta de este Sprint es la mejora del FrontEnd Web Application, del Web Services, del informe y la integración de ambos, asimismo la mejora continua.
      </td>
    </tr>
    <tr>
      <td>Sprint 4 Velocity</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Sum of Story Points</td>
      <td>21</td>
    </tr>
  </tbody>
</table>
<h3>5.2.3.2. Sprint Backlog 4</h3>

En nuestro cuarto sprint, nos enfocamos en desarrollar la versión final de nuestro backend, estableciendo las tareas que implementaremos para el proyecto. Asimismo, incorporamos más funcionalidades en el frontend, para tener las vistas de los segmentos completos y optimizamos tanto el proceso asignación de tareas como añadir y modificar comentarios. Además, logramos completar la mayoría de las tareas que nos propusimos para este sprint junto con la mejora continua, levantando así las observaciones señaladas en las entregas pasadas.



<h3>5.2.3.3. Development Evidence for Sprint Review</h3>
En esta sección se presentan los avances de implementación con relación a los productos desarrollados en el presente Sprint. La implementación de la segunda version del Web Application Front End  y BackEnd. Se implementaron ramas a partir de la rama develop para que cada integrante. <br><br>






<h3>5.2.3.4. Testing Suite Evidence for Sprint Review</h3>

Hemos desarrollado un conjunto de pruebas automatizadas que cubren los Endpoints relacionados con los User Stories definidos para este Sprint. Estas pruebas incluyen Unit Tests, Integration Tests y Acceptance Tests para garantizar la calidad y la funcionalidad de nuestros Web Services.


<h3>5.2.3.5. Execution Evidence for Sprint Review</h3>

Vistas implementadas para este sprint se realizaron para los segmentos:

<h3>5.2.3.6. Services Documentation Evidence for Sprint Review</h3>

<h3>5.2.3.7. Development Evidence for Sprint Review</h3>
<br>


<h3>5.2.2.8. Team Collaboration Insights durante el Sprint</h3><br>
Se creó una organización en GitHub con un dominio público para que el profesor pueda visualizar el proyecto.<br>

Cabe destacar la participación activa de todo el equipo en el desarrollo del proyecto, abarcando desde el Landing Page hasta las capas técnicas del Frontend y Backend, como se evidencia en las imágenes que muestran sus commits. *Team Collaboration Insights* se erige como un recurso fundamental, no solo para comprender la eficacia del equipo desde una perspectiva técnica, sino también para apreciar el esfuerzo conjunto que ha llevado al éxito del proyecto.


<br>








<h3>5.3. Validation Interviews</a></h3><br>
<h3>5.3.1 Diseño de Entrevistas. </a></h3><br>
<h4>PREGUNTAS INTRODUCTORIAS:</h4>
<p>¿Cuál es su nombre completo?<br>
¿Qué edad tiene?<br>
¿En qué distrito reside actualmente?<br>
¿Cuál es su ocupación?</p>

<h4>PREGUNTAS PRINCIPALES:</h4>
<h5>ESTUDIANTES Y PROFESORES:</h5>
<ul>
  <li>¿Crees que siempre está claro en qué parte de la aplicación te encuentras? (Visibilidad del estado del sistema)</li>
  <li>¿La aplicación sigue un flujo lógico y natural para realizar tareas específicas? (Coincidencia entre el sistema y el mundo real)</li>
  <li>¿La aplicación te permite moverte libremente y realizar acciones sin restricciones innecesarias? (Control y libertad del usuario)</li>
  <li>¿Encuentras que los elementos de la interfaz son consistentes en toda la aplicación? (Consistencia y estándares)</li>
  <li>¿Te resulta sencillo corregir un error si lo cometes durante el uso de la aplicación?(Prevención de errores)</li>
  <li>¿Encuentras que las opciones y funciones son fáciles de reconocer sin necesidad de recordar su ubicación? (Reconocimiento en lugar de recuerdo)</li>
  <li>¿Te sientes limitado en cuanto a la forma en que puedes interactuar con la aplicación? (Flexibilidad y eficiencia de uso)</li>
  <li>¿Existen aspectos del diseño que podrían mejorarse para una mejor comprensión y atractivo visual? (Diseño estético y minimalista)</li>
</ul>
<h3>5.3.2 Registro de entrevistas. </a></h3>



<h3>5.3.3 Evaluaciones segun heuristicas. </a></h3>

**SITE o APP A EVALUAR**

<a name="_hlk149810676"></a>**TeamSync**

**Meta:** El propósito general de la evaluación es encontrar problemas existentes en la aplicación web TeamSync.

**Cómo:** Los hallazgos del sitio web se llevarán a cabo utilizando la Lista Heurística de Nielsen, inicialmente investigada y creada por Jakob Nielsen.

**TAREAS A EVALUAR:**

1. Visualización de los planes para el registro del cliente

    Observación:
        La aplicación muestra una sección clara y detallada sobre los diferentes planes de registro, destacando los beneficios de cada uno y los precios asociados.
    Cumplimiento:
        Esta funcionalidad está adecuadamente implementada, facilitando a los usuarios la comprensión de las opciones de registro disponibles.

2. Indicadores claros de progreso o estado del proceso

    Observación:
        La aplicación incluye barras de progreso e indicadores visuales que guían a los usuarios a través de los diferentes pasos del registro y otros procesos.
    Cumplimiento:
        Los usuarios pueden seguir fácilmente el progreso de sus acciones, mejorando la experiencia de usuario y reduciendo la incertidumbre.

3. Iconografía comprensible y consistente con el mundo real

    Observación:
        La iconografía utilizada es adecuada y clara, con símbolos fácilmente reconocibles y consistentes en toda la aplicación.
    Cumplimiento:
        Los iconos ayudan a los usuarios a entender rápidamente las funciones y acciones disponibles.

4. Mensajes de error que reflejen el registro de datos incorrectos

    Observación:
        La aplicación proporciona mensajes de error claros y específicos que indican al usuario exactamente qué datos necesitan corrección y por qué.
    Cumplimiento:
        Los mensajes de error son informativos y ayudan a los usuarios a corregir sus errores sin frustración.

5. Acciones de retroceso dentro de la aplicación

    Observación:
        La aplicación incluye botones de retroceso en todas las secciones donde los usuarios puedan necesitar regresar a una página anterior.
    Cumplimiento:
        Los usuarios pueden navegar hacia atrás fácilmente, lo que mejora la navegación y la experiencia general.

6. Evaluar existencia de patrones de diseño o navegación

    Observación:
        La aplicación sigue un patrón de diseño coherente, con un diseño limpio y elementos bien organizados.
    Cumplimiento:
        La consistencia en el diseño facilita a los usuarios la familiarización y navegación por la aplicación.

7. Elementos de la interfaz de usuario consistentes

    Observación:
        La interfaz mantiene una estética uniforme y consistente en todos los elementos, incluyendo botones, tipografía, colores y espacios.
    Cumplimiento:
        La consistencia en la interfaz mejora la experiencia de usuario al proporcionar un entorno predecible y agradable.

8. Pestañas de navegación dentro de la aplicación

    Observación:
        Las pestañas de navegación son visibles y claras, permitiendo a los usuarios moverse fácilmente entre secciones.
    Cumplimiento:
        La navegación es intuitiva y accesible, mejorando la usabilidad de la aplicación.

9. Botones interactivos y de uso intuitivo

    Observación:
        Los botones son claros, interactivos e intuitivos, proporcionando retroalimentación visual al ser presionados.
    Cumplimiento:
        Los usuarios pueden interactuar fácilmente con los botones, lo que mejora la eficiencia y efectividad de la aplicación.

10. Navegación y orientación dentro de la aplicación

    Observación:
        La estructura de navegación es lógica y fácil de seguir, con un menú lateral que facilita el acceso a diferentes secciones.
    Cumplimiento:
        Los usuarios pueden orientarse fácilmente y encontrar la información o funcionalidad que necesitan sin dificultad.

11. Visualización de perfil del estudiante

    Observación:
        La sección de perfil del estudiante permite ver y editar información personal y académica de manera intuitiva.
    Cumplimiento:
        Los estudiantes pueden gestionar su información de manera eficiente y segura.

12. Visualización del perfil del profesor

    Observación:
        La visualización del perfil del profesor es clara y completa, mostrando información relevante como experiencia, especialidades y disponibilidad.
    Cumplimiento:
        Los perfiles de los profesores están bien diseñados y proporcionan toda la información necesaria para los estudiantes.

13. Visualización de la vista solicitar profesor

    Observación:
        La funcionalidad para solicitar un profesor es clara y accesible, indicando disponibilidad y especialidades.
    Cumplimiento:
        Los estudiantes pueden solicitar profesores de manera fácil y rápida, mejorando la interacción y el aprendizaje.

14. Visualización de los comentarios al trabajo

    Observación:
        La aplicación incluye una sección donde los estudiantes pueden recibir y ver comentarios sobre su trabajo.
    Cumplimiento:
        La retroalimentación es fácil de acceder y comprender, facilitando la mejora continua del desempeño del estudiante.

15. Visualización de los proyectos en los que está asociado el profesor

    Observación:
        Los proyectos en los que está asociado el profesor son claramente visibles, con detalles sobre su rol y contribuciones.
    Cumplimiento:
        La información sobre los proyectos está bien organizada y es accesible para los usuarios interesados.

16. Estética general de la interfaz atractiva y agradable visualmente

    Observación:
        La interfaz es atractiva y bien diseñada, con una estética moderna y limpia.
    Cumplimiento:
        La estética visual es agradable, lo que contribuye a una experiencia de usuario positiva y atractiva.

En resumen, la aplicación web cumple con las heurísticas de usabilidad propuestas, ofreciendo una experiencia de usuario coherente, intuitiva y agradable. La información es clara y accesible, y la navegación está bien estructurada, facilitando a los usuarios la realización de tareas dentro de la aplicación.




**No están incluidas en esta versión de la evaluación las siguientes tareas:**

1. **Desktop landing page**
- Precio de los planes 
- Política de privacidad y condiciones de uso
1. **Web Application** 
- Registro de un nuevo usuario 
- Recuperación de contraseña 
- Comprar de los planes 
- Solicitar apoyo a un profesor.
- Acceso a recursos de ayuda dentro de la aplicación
- Actualizar la información del usuario.
- Información del alumno en la vista del profesor.
- Política de privacidad y condiciones de uso

**ESCALA DE SEVERIDAD:**

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad 

|Nivel|Descripción |
| :- | :- |
|1|<p>Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco </p><p>frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.</p>|
|2|<p>Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de </p><p>superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente </p><p>reléase</p>|
|3|<p>Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es </p><p>importante que sean corregidos y se les debe asignar una prioridad alta.</p>|
|4|<p>Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de </p><p>la herramienta. Es imperativo que sea corregido antes del lanzamiento.</p>|



<h3>5.4. Video About the Product</a></h3>

TeamSync es una plataforma en línea diseñada para facilitar la gestión eficiente de proyectos en equipos de trabajo en entornos educativos. Ofrece una experiencia colaborativa centrada en la formación de grupos, asignación de tareas, seguimiento de proyectos y comunicación fluida entre estudiantes y docentes.
<br><br>
 <p align ="center">
            <img src="">
         </p>
<br><br>
<a href="">Link del Video About the Product </a>
