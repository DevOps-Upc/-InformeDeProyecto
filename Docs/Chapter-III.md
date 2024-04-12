# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping 

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
  </tbody>
</table>

## 3.3. Impact Mapping


## 3.4. Product Backlog

Imagen de Product Backlog en Pivotal Tracker:

![texto_alternativo](/assets/img/chapter-III/ProductBackLogPT.png)


[Link del Pivotal Tracker](https://www.pivotaltracker.com/n/projects/2677710)