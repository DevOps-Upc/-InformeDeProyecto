# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping 
- **Segmento 1**

||Creación de proyecto|Ayuda activa|Uso de funciones|
| :- | :- | :- | :- |
|DOING|Juan está creando un nuevo proyecto en la plataforma, invitando a sus compañeros y asignando tareas.|Está colaborando activamente con sus compañeros para completar las tareas asignadas en el proyecto.|Juan está utilizando la función de seguimiento de progreso para monitorear el avance del proyecto y realizar ajustes según sea necesario.|
|FEELING|Se siente motivado y comprometido al trabajar en equipo y ver el progreso del proyecto.|Se siente seguro al utilizar la plataforma para organizar y colaborar en el proyecto académico.|Se siente emocionado al ver el progreso del proyecto y al acercarse a la fecha de entrega.|
|THINKING|Está pensando en la eficiencia del trabajo en equipo y en la importancia de seguir el progreso del proyecto.|Está reflexionando sobre cómo la plataforma simplifica la gestión de proyectos y mejora la colaboración entre los miembros del equipo.|Está considerando cómo puede aplicar lo aprendido en futuros proyectos académicos y cómo puede mejorar su habilidad para gestionar proyectos.|

- **Segmento 2**

||Revisión de proyectos|Uso de funciones|Comunicación con estudiantes|
| :- | :- | :- | :- |
|DOING|María está revisando los proyectos presentados por sus estudiantes en la plataforma.|Luego, utiliza las funciones de evaluación integradas para asignar calificaciones y proporcionar retroalimentación detallada.|María está utilizando la plataforma para comunicar los resultados de las evaluaciones a sus estudiantes y proporcionar orientación adicional según sea necesario.|
|FEELING|Se siente satisfecha al poder evaluar los proyectos de manera eficiente y proporcionar una retroalimentación valiosa a sus estudiantes.|Se siente segura al utilizar la plataforma para gestionar y evaluar proyectos académicos.|Se siente orgullosa del progreso y los logros de sus estudiantes al ver los resultados de sus proyectos|
|THINKING|Está reflexionando sobre cómo la plataforma simplifica su proceso de evaluación y mejora su eficiencia como profesora.|Está considerando cómo puede utilizar mejor la plataforma para facilitar la comunicación con sus estudiantes y mejorar su experiencia académica.|Está pensando en cómo puede utilizar los datos recopilados de las evaluaciones para mejorar su enseñanza y hacer ajustes en futuros proyectos académicos.|

![Usuario]()


## 3.2. User Stories
<table>
  <thead>
    <tr>
      <th>Epic/User Story ID</th>
        <th>Titulo</th>
        <th>Descripción</th>
        <th>Criterios de aceptación</th>
        <th>Relacionado con (Epic ID)</th>    
    </tr>
  </thead>
  
  <tbody>
      <tr>
        <td><strong>EP01/US01</strong></td>
        <td>Registro de cuenta</td>
        <td>
            Como usuario, quiero crear una cuenta para ingresar a la aplicación.
        </td>
        <td>
          <strong>Escenario 1: Registro correcto
          </strong> <br>
          <strong>Dado que</strong> el usuario encuentra la sección de registro de sesión, <br>
          <strong>Cuando</strong> rellena el formulario
          y presiona registrar, <br>
          <strong>Entonces</strong> muestra un mensaje “Registro correcto” y manda al usuario al home.
          <strong>Escenario 2: Registro Incorrecto
          </strong> <br>
          <strong>Dado que</strong> el usuario encuentra la sección de registro de sesión, <br>
          <strong>Cuando</strong> rrellena el formulario
          y presiona registrar
          , <br>
          <strong>Entonces</strong> muestra el mensaje “Correo ya registrado o invalido".
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US02</strong></td>
        <td>Inicio de sesión</td>
        <td>
            Como usuario, quiero iniciar sesion con mi cuenta creada.
        </td>
        <td>
          Escenario 1: Inicio de sesión correcto <br>
          Dado que el usuario encuentra la sección de inicio de sesión cuando ingresa su correo y contraseña y presiona iniciar
          entonces lo manda al menu de la aplicación <br>
          Escenario 2: Inicio de sesión incorrecta <br>
          Dado que el usuario encuentra la sección de inicio de sesión cuando ingresa su correo y contraseña
          y presiona iniciar entonces le muestra el mensaje “Correo o contraseña incorrecta”.
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US03</strong></td>
        <td>Inicio de sesión</td>
        <td>
            Como usuario, quiero poder cerrar mi sesión en la aplicación.
        </td>
        <td>
          Escenario 1:Cierre correcto de la sesión
          Dado que usuario encuentra el botón de cerrar sesión
          cuando el presiona este mismo
          entonces el sistema cierra por completo su sesión actual.
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US04</strong></td>
        <td>Actualizar información de cuenta</td>
        <td>
            Como usuario, quiero mantener mi información de mi perfil actualizada.
        </td>
        <td>
          Escenario 1:Cambio correcto de la información
          Dado que usuario quiere cambiar su contraseña
          cuando el ingresa a su editar perfil
          y llega a la casilla contraseña correctamente y lo manda entonces el sistema le manda un mensaje “Contraseña cambiada”
          Escenario 2:Cambio incorrecto de la información
          Dado que usuario quiere cambiar su contraseña
          cuando el ingresa a su editar perfil
          y llega a la casilla contraseña incorrectamente y lo manda
          entonces el sistema le dice ”Que esa no es una contraseña segura”
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US05</strong></td>
        <td>Visualizar información de la cuenta </td>
        <td>
           Como usuario, quiero visualizar la información de mi cuenta para verificarla
        </td>
        <td>
          Escenario 1:Visualización correcta de la información.
          Dado que el usuario quiere ver sus datos de perfil
          cuando hace click en su foto de perfil
          entonces el sistema le muestra todos sus datos de este.
          Escenario 2:No se visualiza nada de la información.
          Dado que el usuario quiere ver sus datos de perfil
          cuando hace click en su foto de perfil
          entonces el sistema le muestra en blanco todos sus datos.
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US06</strong></td>
        <td>Eliminar permanentemente la cuenta</td>
        <td>
            Como usuario, quiero eliminar mi cuenta al no querer usar más la app.
        </td>
        <td>
          Escenario 1: Eliminación correctamente del perfil.
          Dado que el usuario quiere eliminar su cuenta
          cuando el hace click en su perfil
          y  luego hace click en el botón “Eliminar”
          entonces el sistema le manda un mensaje “Cuenta eliminada”
          Escenario 2:Eliminación incorrectamente del perfil
          Dado que el usuario quiere eliminar su cuenta
          cuando el hace click en su perfil
          y luego hace click en el boton “Eliminar”
          entonces el sistema le manda un mensaje “Cuenta no eliminada”
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US07</strong></td>
        <td>Agregar integrantes a equipos de trabajo</td>
        <td>
            Como alumno, quiero poder agregar integrantes a mi equipo de trabajo de mi proyecto.
        </td>
        <td>
          Escenario 1:Agregar un usuario
          Dado que un usuario creó un grupo
          cuando el quiere agregar a otros
          y envia una invitacion
          entonces el sistema notifica al otro usuario.
          Escenario 2:No se agrego un usuario
          Dado que un usuario creó un grupo
          cuando el quiere agregar a otros
          y envia una invitacion
          entonces el sistema no notifica al otro usuario.
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US08</strong></td>
        <td>Creación de equipo de trabajo</td>
        <td>
            Como alumno, quiero empezar a crear mi equipo de trabajo para organizar mi proyecto.
        </td>
        <td>
          Escenario 1:Equipo creado correctamente
          Dado que el usuario 
          cuando crea un grupo 
          y presiona el botón para confirmar los datos de este
          entonces el sistema le confirma la creación del grupo con “Grupo creado correctamente”
          Escenario 2:Equipo no creado
          Dado que el usuario 
          cuando crea un grupo 
          y presiona el botón para confirmar los datos de este
          entonces el sistema le manda el mensaje “Error al crear un grupo”
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US09</strong></td>
        <td>Creación de tareas</td>
        <td>
            Como alumno, quiero poder crear tareas para el avance del proyecto.
        </td>
        <td>
          Escenario 1:Tarea creada correctamente
          Dado que el usuario
          cuando crea una tarea
          y este confirma los datos que tendrá esta
          entonces el sistema confirma su creación de la tarea con “Tarea creada”
          Escenario 2:Tarea no creada
          Dado que el usuario
          cuando crea una tarea
          y este confirma los datos que tendrá esta
          entonces el sistema manda el mensaje “Tarea no creada”
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US10</strong></td>
        <td>Asignar tareas a un integrante</td>
        <td>
            Como alumno, quiero poder agregar otros usuarios a mi proyecto para poder organizar su desarrollo.
        </td>
        <td>
          Escenario 1:Tarea asignada correctamente.
          Dado que usuario selecciona la tarea para asignar 
          cuando él escoge el usuario que tendrá esa tarea
          y confirma
          entonces el sistema muestra el mensaje “Tarea Asignada”
          Escenario 2:Tarea no asignada.
          Dado que usuario selecciona la tarea para asignar 
          cuando él escoge el usuario que tendrá esa tarea
          y confirma
          entonces el sistema muestra el mensaje “Error al asignar tarea”
        </td>
        <td>
          EP03
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US11</strong></td>
        <td>Crear calendario para la asignación de tareas</td>
        <td>
            Como alumno, quiero poder marcar un calendario para limitar las fechas de las tareas. 
        </td>
        <td>
          Escenario 1:Creación de un calendario con fechas marcadas
          Dado que el usuario crea un calendario para limitar fechas de tareas 
          cuando confirma
          entonces el sistema manda el mensaje “Fecha asociada a la tarea”
          Escenario 2:No se guardó el calendario creado
          Dado que el usuario crea un calendario para limitar fechas de tareas 
          cuando confirma
          entonces el sistema manda el mensaje “Error al asociar con la tarea”
        </td>
        <td>
          EP03
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US12</strong></td>
        <td>Visualizar las tareas del grupo</td>
        <td>
            Como usuario, quiero visualizar las tareas que se crearon para poder asignarlas
        </td>
        <td>
          Escenario 1:Visualización de tareas del grupo
          Dado que el usuario quiere ver las tareas
          cuando el usuario selecciona ver las tareas
          entonces el sistema muestra las tareas del proyecto
          Escenario 2: No se visualiza las tareas.
          Dado que el usuario quiere ver las tareas
          cuando el usuario selecciona ver las tareas
          entonces el sistema muestra un mensaje “Error al cargar las tareas”.
        </td>
        <td>
          EP03
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US13</strong></td>
        <td>Compartir archivos y videos</td>
        <td>
            Como alumno, quiero compartir archivos y videos de forma segura.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US14</strong></td>
        <td>Creación de proyecto</td>
        <td>
            Como alumno,quiero poder crear proyectos para mii equipo de trabajo
        </td>
        <td>
          Escenario 1: Inicio de sesión correcto <br>
          Dado que el usuario encuentra la sección de inicio de sesión cuando ingresa su correo y contraseña y presiona iniciar
          entonces lo manda al menu de la aplicación <br>
          Escenario 2: Inicio de sesión incorrecta <br>
          Dado que el usuario encuentra la sección de inicio de sesión cuando ingresa su correo y contraseña
          y presiona iniciar entonces le muestra el mensaje “Correo o contraseña incorrecta”.
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US15</strong></td>
        <td>Crear comentarios sobre un proyecto de alumnos</td>
        <td>
            Como profesor, quiero poder comentar sobre el avance del proyecto
        </td>
        <td>
          Escenario 1:
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US16</strong></td>
        <td>Actualizar estado del avance del proyecto del equipo/td>
        <td>
            Como profesor, quiero actualizar el estado de la ayuda y avance del proyecto.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US17</strong></td>
        <td>Crear solicitud de ayuda a un docente</td>
        <td>
            Como alumno,quiero crear una solicitud de ayuda para mi proyecto.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US18</strong></td>
        <td>Realizar comentarios a los avances de los alumnos</td>
        <td>
            Como profesor, quiero realizar comentarios sobre el avance de las tareas de los alumnos.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US19</strong></td>
        <td>Aceptar o rechazar solicitud de grupo</td>
        <td>
            Como alumno, quiero aceptar o rechazar solicitudes de unirse a un grupo
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US20</strong></td>
        <td>Buscar trabajos por etiqueta o tema relacionado</td>
        <td>
            Como alumno,quiero buscar trabajos en la biblioteca con una cierta etiqueta.
        </td>
        <td>
          Escenario 1
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US21</strong></td>
        <td>Descargar Trabajo de la biblioteca/td>
        <td>
            Como alumno, quiero descargar el documento de la biblioteca para verlo sin conexión.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US22</strong></td>
        <td>Implementar un landing Page Responsive</td>
        <td>
            Como visitante, quiero interactuar en una landing page responsive, para que se adapte a la resolución de mi dispositivo.
        </td>
        <td>
          Escenario 1:
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US23</strong></td>
        <td>Implementar un cambio de idioma en el Landing Page</td>
        <td>
            Como visitante, quiero poder cambiar de idioma para poder comprender el mensaje del landing page.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US24</strong></td>
        <td>Sección sobre el producto TeamSync en el lan</td>
        <td>
            Como visitante, quiero que el landing page me muestre una sección que da a conocer el producto.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US25</strong></td>
        <td>Sección sobre las membresías de TeamSync </td>
        <td>
            Como visitante, quiero que el landing page me muestre una sección
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US26</strong></td>
        <td>Sección sobre el segmento objetivo de TeamSync  </td>
        <td>
            Como visitante, quiero que el landing page me muestre una sección a quien esta dirigido la aplicación
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US27</strong></td>
        <td>Sección sobre nosotros de TeamSync </td>
        <td>
            Como visitante, quiero que el landing page me muestre una sección sobre los desarrolladores del producto.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US28</strong></td>
        <td>Sección de contacto de TeamSync  </td>
        <td>
            Como visitante, quiero que el landing page me muestre una sección que me ponga en contacto con el startup.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US29</strong></td>
        <td>Subir fotos de perfil </td>
        <td>
            Como usuario, quiero subir una imagen a mi perfil para poder personalizarlo a mi comodidad
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US30</strong></td>
        <td>Crear Proyectos Académicos </td>
        <td>
            Como estudiante, quiero crear proyectos, invitar a compañeros y asignar tareas para colaborar eficientemente en trabajos grupales académicos.
        </td>
        <td>
          <p>Escenario 1: Creación de proyectos.</p><p>Dado que el estudiante se encuentra en la página principal de TeamSync.</p><p>Cuando el estudiante de clic en “Crear Proyecto”</p><p>E invite a sus compañeros</p><p>Y asigne diferentes tareas</p><p>Entonces, sus trabajos grupales serán eficientes.</p>
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US31</strong></td>
        <td>Notificaciones de Progreso </td>
        <td>
            Como estudiante, necesito notificaciones de progreso y actualizaciones de equipo para estar informado y ajustar el proyecto según sea necesario.
        </td>
        <td>
          <p>Escenario 1: Edición de información de perfil</p><p>Cuando el estudiante se encuentra en su perfil</p><p>Y de clic en “notificaciones”</p><p>Entonces el estudiante podrá recibir notificaciones sobre su progreso y actualizaciones.</p>
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US32</strong></td>
        <td>Revisión y Evaluación de Proyectos</td>
        <td>
            <p>Como profesor, deseo revisar, calificar y dar retroalimentación a proyectos estudiantiles para guiar y evaluar eficientemente.</p>
        </td>
        <td>
          <p>Escenario 1: Revisar y evaluar proyectos.</p><p>Dado que el profesor se encuentra en la pagina de un proyecto</p><p>Entonces tendrá funciones de calificación, comentar y revisar de forma correcta el proyecto.</p>
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US33</strong></td>
        <td>Gestión de Notificaciones para Profesores</td>
        <td>
            Como profesor, necesito notificaciones sobre nuevos proyectos y tareas pendientes para gestionar mi tiempo efectivamente.</p>
        </td>
        <td>
          <p>Escenario 1: Notificaciones para profesores.</p><p>Cuando el profesor se encuentre en su perfil</p><p>Y de clic en notificaciones</p><p>Entonces podrá recibir notificaciones sobre nuevos proyectos y diferentes tareas.</p>
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US34</strong></td>
        <td>Acceso a Recursos Académicos</td>
        <td>
            Como estudiante, busco acceso a una biblioteca de recursos para enriquecer mis proyectos académicos.
        </td>
        <td>
          <p>Escenario 1: Acceso a recursos</p><p>Cuando el estudiante se encuentre en la pagina de recursos</p><p>Y de clic en “Recursos digitales”</p><p>Entonces tendrá acceso a diferentes repositorios con mucha información.</p>  
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US35</strong></td>
        <td>Comunicación en la Plataforma</td>
        <td>
            Como estudiante, quiero comunicarme con mi equipo y profesor para discutir ideas y resolver dudas sobre proyectos.
        </td>
        <td>
          Escenario 1:
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US36</strong></td>
        <td>Métricas de Progreso Estudiantil </td>
        <td>
            Como profesor, requiero métricas de progreso estudiantil para identificar áreas de mejora y proporcionar orientación personalizada.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
      <tr>
        <td><strong>EP01/US37</strong></td>
        <td>Recordatorios de Plazos y Reuniones</td>
        <td>
            Como estudiante, necesito recordatorios de plazos y reuniones para planificar mi tiempo y cumplir con las expectativas del curso.
        </td>
        <td>
          Escenario 1: 
        </td>
        <td>
          EP01
        </td>
      </tr>
  </tbody>
</table>


## 3.3. Impact Mapping


## 3.4. Product Backlog

Imagen de Product Backlog en Pivotal Tracker:

![texto_alternativo](/assets/img/chapter-III/ProductBackLogPT.png)


[Link del Pivotal Tracker](https://www.pivotaltracker.com/n/projects/2677710)
