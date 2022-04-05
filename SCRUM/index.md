---
title: SCRUM
lead: true
---

Es el marco de trabajo de desarrollo ágil que utilizamos en Paulonia. Este incluye un conjunto de reuniones, herramientas y funciones que, de forma coordinada, ayudan a los equipos a estructurar y gestionar su trabajo.

# Roles
## Scrum master
Es la persona que ayuda a facilitar scrum al equipo, asegurándose de que se sigue el marco de trabajo. Su compromiso es con los valores y prácticas de scrum, pero también debe ser flexible y estar abierto a las oportunidades de mejora del flujo de trabajo del equipo
## Product owner
Es la persona encargada de crear las historias de usuario que se trabajaran en los sprints. Conoce muy bien del negocio y es el puente entre el cliente y Paulonia


# Ceremonias

## Reuniones diarias

Es un evento de 15 minutos donde el equipo sincroniza sus actividades y crea un plan para las próximas 24 horas. Es importante entender que no solamente se debe dar una actualización de las tareas que estas trabajando, sino que se debe enfatizar en los obstaculos y las oportunidades de mejora.

### Preguntas a responder
Cuando una persona inicie su intervención, debe responder las siguientes preguntas:

 1. ¿Qué tareas hice ayer?
 2. ¿Qué tareas haré hoy?
 3. ¿Veo algun impedimento en mis tareas?
 4. ¿Todo lo que menciono está actualizado en JIRA?

Cabe recalcar que la intervención del participante solo debe ser de los objetivos del sprint, en caso hubiera realizado tareas extras no previstas, debe indicarlo como 'entre otras cosas'. Esto se hace con la finalidad de no desenfocar al equipo de los objetivos del sprint.

Luego de finalizada su intervención deberá indicar el nombre de la siguiente persona.

### Objetivos de la reunión diaria
Se debe evitar a toda costa que las intervenciones de los participantes sean a modo de reporte, por ello antes de participar de una reunión diaria se debe considerar los siguientes objetivos:

 1. Analizar si el avance diario permitirá alcanzar el objetivo del sprint.
 2. Definir un plan para tener un día efectivo.
 3. Detectar estancamientos al comparar las tareas previstas del dia anterior con las tareas realizadas.

### Facilitador de la reunión
No es necesario que la persona que guie la reunión diaria sea el SCRUM Master, por ello cada día se designa a una persona distinta para que guie esta.
Las acciones que debe realizar el facilitador son las siguientes:
1. Verificar que todo el equipo esté listo para iniciar la reunión.
2. Recordar a los participantes que deben cumplir con la estructura de la reunión diaria.
3. Recopilar dudas o anuncios al final de la reunión.
4. Recordar el punto de acción del sprint y despedir la reunión.

## Revisión del sprint
En esta ceremonia se realiza lo siguiente:
- El equipo muestra los logros del sprint, utilizando los recursos que vea por conveniente. Cada partipante tiene entre 5-7 minutos para realizar esto.
- Se revisan las métricas obtenidas. (En caso hubieran)
- Se dá un vistazo general al siguiente sprint.

El Scrum Master va guiando la reunión, velando porque la reunión mantenga un buen ritmo y se respeten los tiempos.

## Retrospectiva
En esta ceremonia se realizan las siguientes actividades:
- Energizante: Dinámica para que las personas entren en confianza y se suelten.
- Retrospectiva: Dínamica para recolectar ideas sobre el sprint pasado. Por lo general se enfoca en problemas y soluciones.
- Filtrado: Dínamica para seleccionar el punto de acción que se realizará en el sprint. Se recolecta las ideas y aquellas que no sean puntos de acción se convierten en tickets que irán  al backlog.
- Estado del equipo: Espacio para compartir el sentir de cada uno respecto a las tareas que realiza, relación con compañeros de trabajo y relación con clientes.

Para obtener ideas de dinámicas se debe revisar la siguiente página:
https://www.funretrospectives.com/

## Planificación
Para definir las historias de usuario o tareas que se realizarán en el siguiente sprint, primero se debe tener un backlog bien trabajado, el cual contiene los requerimientos que el dueño de producto necesita.
### ¿Quién es el dueño de producto?
En Paulonia tenemos diferentes clientes, los cuales generalmente no tienen a alguien que asuma el rol de dueño de producto, es por ello que  designamos a una persona para que cumpla este rol en todos los proyectos, y se encargue de priorizar tareas y revisar la entrega de producto que hacen los equipos.

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
Se deben tener todas las tareas de clientes definidas hasta el lunes de la segunda semana. Ese día se celebrará una reunión corta con los líderes de equipo para definir que otras tareas se añadirán al sprint y tambien se refinarán aquellas que falten. 
Luego de que todas las tareas estén definidas el dia de la retrospectiva se seleccionará con todo el equipo las tareas que se harán en el siguiente sprint.

