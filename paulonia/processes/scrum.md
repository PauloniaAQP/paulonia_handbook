---
title: SCRUM
lead: true
---

Es el marco de trabajo de desarrollo ágil que utilizamos en Paulonia. Este incluye un conjunto de reuniones, herramientas y funciones que, de forma coordinada, ayudan a los equipos a estructurar y gestionar su trabajo.

# Roles
## Scrum master
Es la persona que ayuda a facilitar SCRUM al equipo, asegurándose de que se sigue el marco de trabajo. Su compromiso es con los valores y prácticas de SCRUM, pero también debe ser flexible y estar abierto a las oportunidades de mejora del flujo de trabajo del equipo
## Director de proyectos
 Conoce muy bien el alcance de los proyectos y define una ruta para que se cumpla con los tiempos de entrega. Es el encargado de mantener al cliente actualizado respecto al estado del proyecto.
## Product Owner
Es la persona encargada de crear requisitos para el desarrollo o diseño del producto. Debe conocer las necesidades del negocio, para poder priorizar tareas. Por lo general este rol lo desempeñan los dueños de negocio, pero en caso estos deleguen la responsabilidad a otra persona, se debe asegurar que tenga la preparación y el conocimiento adecuado.


# Ceremonias

## Reuniones diarias

Es un evento de 15 minutos donde el equipo sincroniza sus actividades y crea un plan para las próximas 24 horas. Es importante entender que no solamente se debe dar una actualización de las tareas que estas trabajando, sino que se debe enfatizar en los obstáculos y las oportunidades de mejora. 

El lider de equipo asignado es el encargado de guiar estas reuniones.

En Paulonia por lo general se trabaja en diversos proyectos por sprint, por ello se crean reuniones diarias para cada equipo. La asignación de personas por equipo y la creación de reuniones en Google Meet las hace el director de proyectos.

### Preguntas a responder
Cuando una persona inicie su intervención, debe responder las siguientes preguntas:

 1. ¿Qué tareas hice ayer?
 2. ¿Qué tareas haré hoy?
 3. ¿Tengo o podría tener algún impedimento en mis tareas?
 4. ¿Todo lo que menciono está actualizado en JIRA?

Cabe recalcar que la intervención del participante solo debe ser de los objetivos del sprint, en caso hubiera realizado tareas extras no previstas, debe indicarlo como 'entre otras cosas'. Esto se hace con la finalidad de no desenfocar al equipo de los objetivos del sprint.

### Objetivos de la reunión diaria
Se debe evitar a toda costa que las intervenciones de los participantes sean a modo de reporte, por ello antes de participar de una reunión diaria se debe considerar los siguientes objetivos:

 1. Analizar si el avance diario permitirá alcanzar el objetivo del sprint.
 2. Definir un plan para tener un día efectivo.
 3. Detectar estancamientos al comparar las tareas previstas del dia anterior con las tareas realizadas.

### Facilitador de la reunión
No es necesario que la persona que guíe la reunión diaria sea el SCRUM Master, por ello se recomienda que cada día se designe a una persona distinta para que la guíe.
Las acciones que debe realizar el facilitador son las siguientes:
1. Verificar que todo el equipo esté listo para iniciar la reunión.
2. Recordar a los participantes que deben cumplir con la estructura de la reunión diaria.
3. Recopilar dudas o anuncios al final de la reunión.
4. Recordar el punto de acción del sprint y despedir la reunión.

## Revisión del sprint
En esta ceremonia se realiza lo siguiente:
- El equipo muestra los logros del sprint, utilizando los recursos que vea por conveniente. Cada partipante tiene entre 5-7 minutos para realizar esto.
- Se revisan las métricas obtenidas (en caso hubieran).
- Se dá un vistazo general del siguiente sprint.

El Scrum Master va guiando la reunión, velando porque la reunión mantenga un buen ritmo y se respeten los tiempos.

## Retrospectiva
En esta ceremonia se realizan las siguientes actividades:
- Energizante: Dinámica para que las personas entren en confianza y se suelten.
- Retrospectiva: Dínamica para recolectar ideas sobre el sprint pasado. Por lo general se enfoca en problemas y soluciones.
- Filtrado: Dinámica para seleccionar el punto de acción que se realizará en el sprint. Se recolecta las ideas y aquellas que no sean puntos de acción se convierten en tickets que irán al backlog.
- Estado del equipo: Espacio para compartir el sentir de cada uno respecto a las tareas que realiza, relación con compañeros de trabajo y relación con clientes.

Para obtener ideas de dinámicas se debe revisar la siguiente página:
https://www.funretrospectives.com/

## Planificación
Para definir las historias de usuario o tareas que se realizarán en el siguiente sprint, primero se debe tener un backlog bien trabajado, el cual contiene los requerimientos que el dueño de producto necesita.
### ¿Quién es el dueño de producto?
En Paulonia tenemos diferentes clientes, los cuales generalmente no tienen a alguien que asuma el rol de dueño de producto, es por ello que designamos a una persona para que cumpla este rol en todos los proyectos, y se encargue de priorizar tareas y revisar la entrega de producto que hacen los equipos.

Adicional a ello, el encargado también define las tareas relacionadas a Paulonia, las cuales no son especificadas a nivel técnico, sino que detalla a nivel general y especifica el valor que añade a la empresa.

### Product Backlog
El Product Backlog es una lista de todo el trabajo pendiente en la empresa. Está compuesta por:
 - Tareas.
 - Historias de Usuario.
 
Ambas deben tener los siguientes campos:
- **Titulo**: Es un texto con la siguiente estructura: Proyecto | Descripción corta 
- **Descripción**: Es un texto en el cual se especifican 3 cosas:
	- Información general
	- Criterios de aceptación
	- Definición de terminado
 - **Responsable**: Persona que está encargada de la tarea.
 - **Revisor**: Persona que verifica el cumplimiento de una tarea según la definición de terminado y mueve el estado de un ticket de la columna Ready a Done.
 - **Sprint**: Sprint al que pertenece esta tarjeta.

Adicional a estos campos se pueden añadir de forma opcional:
- Video de Loom explicando de forma general
- Imagen
- Enlace a diseño de Figma

### ¿Quién crea las tarjetas?
Dependerá del tipo de tarjetas:
- Las historias de usuario las creará el **dueño de producto**.
- Las tareas son creadas generalmente por el **lider de equipo** pero tambien hay algunas que pueden ser creadas por cualquier persona del equipo (subtareas, tareas desde Slack)

### ¿Cuando se crean las tarjetas?
Eso dependerá de a que sprint pertenezca la tarjeta
- **Sprint  Actual**: Se pueden crear a lo largo del sprint siempre y cuando no afecte el alcance inicial. Generalmente son las tarjetas creadas desde Slack.
- **Sprint Futuro:** Se crean en cualquier momento y se añaden al Backlog.
Para proyectos nuevos, las historias se crean al inicio del proyecto y se crean tarjetas con cada una de ellas.

### ¿Cómo se definen las tareas para el siguiente Sprint?
La elección y/o creación de tareas se harán en las siguientes reuniones:
- **Reuniones con líderes:** Se celebrará el jueves de la segunda seman de sprint. Estas pueden ser individuales (1:1) o grupales, según el criterio del director de proyectos.
- **Reuniones con accionistas:** Se destinará un tiempo en cada junta de accionistas para la definición de tareas relacionadas a la dirección de la empresa en diversas áreas.

Finalment se añadirán las tarjetas al tablero del siguiente sprint en Jira.


