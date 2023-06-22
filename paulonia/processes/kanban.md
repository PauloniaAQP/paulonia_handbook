---
title: Kanban
pagination:
    next:
        link: ../vacation
        name: Vacaciones
    previous:
        link: ../
        name: Introducción
---

Es el principal marco de trabajo de desarrollo ágil que utilizamos en Paulonia. Antes usabamos Scrum, pero con el pasar del tiempo nos dimos cuenta de que no encajaba con nuestro ritmo de trabajo, sin embargo, se han sacado ideas de Scrum para integrarlas a nuestro nuevo marco de trabajo junto con Kanban.

# Tablero y Tareas

El tablero es Kanban y la prioridad de las tareas tiene mucho peso aquí. La razón por la que usamos Kanban en vez de Scrum es que nuestros clientes y trabajos son volátiles provocando que entren tareas en medio del sprint o que las prioridades de las tareas cambien constantemente, lo que rompía toda la armonía que Scrum dicta.

Kanban nos permite crear tareas para que puedan ser realizadas en cualquier momento cambiando las prioridades de las tareas existentes.

## Estructura del tablero

- **Backlog:** Una tarea recién creada va a esta columna. Es un listado de tareas creadas que no tienen la prioridad o aún no han sido seleccionadas para ser realizadas.
- **Selected:** Aquí van las tareas que han sido seleccionadas para ser realizadas.
- **Recurring:** Son tareas que se hacen en diferentes periodos y no tienen un tiempo de fin definido. Ej. Realizar las boletas de pago mensuales.
- **In progress:** Son las tareas que se están realizando actualmente. Una persona no debe tener más 3 tareas en esta columna.
- **Waiting for:** Son las tareas bloqueadas. Una tarea puede estar bloqueada, por ejemplo, porque es necesaria la intervención de otra persona, es necesaria que se termine otra tarea, ha entrado otra tarea mucho más prioritaria, etc. Una persona no debe tener más de 3 tareas en esta columna. Si ese límite se alcanza, contacte con su [Team Lead](#team-lead) para ver como desbloquear tareas.
- **Ready:** Son las tareas que han sido terminadas y están listas para ser revisadas por el [Reviewer](#reviewer) de la tarea.
- **Done:** Son las tareas terminadas y aprobadas por el [Reviewer](#reviewer) de la tarea. Si es código, el Pull Request debe estar aprobado y mergeado.

# Ceremonias

## Weekly report

Este es un reporte escrito semanal que toda persona dentro de Paulonia debe realizar. Se debe realizar el día viernes al finalizar tu jornada de trabajo antes del [Weekly meeting](weekly-meeting). Los reportes se postean en el canal [pau-weekly-reports](https://paulonia.slack.com/archives/C04Q85ARNKW) en Slack.

Deben tener la siguiente estructura:

**Tareas realizadas**: En esta sección se van a enlistar las tareas que uno ha terminado (está en DONE) en esta semana. La tarea tiene que ir con su link respectivo a Jira. En cada tarea explicar con sus propias palabras lo que se hizo en la tarea y su experiencia en ella, por ejemplo, si tuvo algun problema, cómo lo resolvió, etc

```
- KIRI-2790: Envié documentos de la empresa oficiales al área legal. Esta ha sido mi primer acercamiento con el área legal.
- KIRI-2784: Deplegué la última versión de Bizzychain en Apple ya que había caducado. Esta tarea la tuve que hacer rápido ya que el cliente lo necesitaba por una reunión que tenía y necesitaba mostrar la app.
```

**Tareas en progreso**: En esta sección se van a enlistar las tareas que aún están en progreso, en revisión o bloqueada en esta semana. La tarea tiene que ir con su link respectivo a Jira. En cada tarea explicar con sus propias palabras el estado actual: lo que ya hizo y lo que falta para hacer. Agregar si tiene algún problema para avanzar con la tarea, o la razón por la que está bloqueada.
(Recordar que este reporte esta dirigido a todos los equipos, cualquier poblema con las tareas ya debe haberlos comunicado antes al lider de equipo, no esperar hasta este momento para comunicar los problemas)

```
- KIRI-2746: He revisado algunos costos del viaje de Jhunior a Tacna, pero necesito más información desde comercial para continuar.

- KIRI-2745: He creado la estructura para el reporte semanal. Está en revisión por los fundadores.
```

**Kudos (opcional):** En esta sección va a enlistar los [Kudos](https://www.collinsdictionary.com/es/diccionario/ingles/kudos) que va a enviar a otras personas. Taguee a la persona y envíele sus kudos con sus propias palabras. Puede agradecer una ayuda por una tarea bloqueada, que haya entregado una tarea rápido, por su lindo código, lo que sea!!

```
- Kudos a Juan por ayudarme en un bug en una tarea de Shaka

- Kudos a Oscar por su gran avance en Shaka.
```

**Otras cosas (opcional):** Al final colocar cualquier ocurrencia que pueda tener la siguiente semana. Por ejemplo, vacaciones o reducción de horas (sólo para avisar a todos los equipos, esto ya debió de coordinarlo con recursos humanos), alguna festividad, reunión o alguna cosa de la siguiente semana que quisiera recordarles a los equipos, o simplemente para decir “Nos vemos mañana!”

```
La siguiente semana voy a estar de vacaciones los dias 16 y 17. Nos vemos mañana en la reunión chicos!
```

## Weekly meeting

Esta reunión se hace cada sábado a la 8:00 AM PET de forma remota. Esta reunión tiene como objetivo la comunicación entre los diferentes equipos de Paulonia para que todas las personas dentro de la empresa estén en sintonía de lo que se ha hecho en la semana y de lo que se va a hacer la siguiente, y para que en conjunto podamos discutir y tomar decisiones que nos ayuden a cumplir el objetivo.

La reunión se divide en dos partes, en la primera cada equipo da un reporte de lo que se hizo en la semana; en la segunda parte se ve el trablero principal y se comenta lo que se va a hacer en la siguiente semana.

### Primera parte

La comunicación se da por turnos. Cada equipo puede dar su reporte de la forma que le sea mejor, siempre respetando el contenido y el tiempo. Por ejemplo, el equipo puede escojer un representante que de el reporte general del equipo o que cada integrante del equipo de su reporte.

El reporte debe estar enfocado en lo que se hizo en la semana, el porqué se hizo bien o porqué no se hizo, y que se necesita para llegar al objetivo.

### Segunda parte

Luego de que todos los equipos hayan dado su reporte, se pasa a revisar el tablero general. Aquí se discuten los objetivos de la siguiente semana y las tareas que cada equipo debe realizar para poder cumplirlos. Se crean dichas tareas o se sacan del backlog para que sean seleccionadas.


### Consideraciones

- Se debe escoger a una persona que guie la reunión.
- El tiempo máximo de la reunión es de 1 hora.
- La reunión debe de ser grabada. Debe de haber un encargado que pueda grabar con el Loom de la empresa.
- Se debe trackear la reunión.
- Todas las personas deben de tener su cámara prendida.


# Roles
## Team Lead

Es la persona encargada de un equipo. Tiene las siguientes responsabilidades:

- Crea las tareas para el equipo.
- Asigna las tareas de acuerdo a las prioridades de la empresa o los clientes.
- Revisa el tablero de su equipo para ver su avance o si hay alguna tarea estancada.
- Responder cualquier pregunta o inquietud que tenga un Assignee o Reviewer de un tarea.
- Tiene la última palabra a la hora de desbloquear una tarea.

## Assignee

Es la persona encargada de realizar una tarea. Esta persona pone todo su empeño para que la tarea sea realizada de forma correcta y a tiempo. Puede ser cualquier miembro del equipo. Tiene las siguientes responsabilidades.

- Realizar la tarea de forma correcta y a tiempo según los objetivos propuestos para la semana.
- Responder cualquier inquietud del reviewer.
- Mover las tareas en el tablero dependiendo de su estado.
- Mover las tareas a `Ready` cuando este lista para ser revisada. Comunicar al reviewer.
- Resolver los cambios requeridos por el reviewer.
- Comunicarte con el reviewer si aún no se revisa la tarea o si no se ha colocado la tarea en `Done`.

## Reviewer

Es la persona encargada de revisar una tarea. Se encarga de que los criterios de aceptación de la tarea se cumplan y haya sido realizada con una alta calidad. Puede ser cualquier miembro del equipo. Tiene las siguientes responsabilidades:

- Revisar las tareas en la columna `Ready` en la que es reviewer.
- Realizar preguntas o sugerir cambios según se requiera.
- Colocar las tareas revisadas que necesitan cambios a `In progress`. Comunicar al Assignee.
- Colocar las tareas revisadas aprovadas en `Done`. Comunicar al Assignee.
