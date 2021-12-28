---
title: Procesos de desarrollo
lead: false
---

## Desarrollo del backend

---

- **Input necesario:**
    - Documento de Requerimientos
    - Flujo de desarrollador de los diseños
    - Documentos de la estructura de la base de datos
- **Input opcional:**
    - Cualquier documento/gráfico que ayude a la tarea
- **Output:**
    - Backend implementado
    - Repositorio de la app implementado
    - DevOps implementado

---

Antes de comenzar explicando esta etapa, es bueno entrar en contexto de la diferencia entre el backend y la lógica de la app. El backend son todas las funcionalidades, código y servicios que no están del lado del cliente, por ejemplo, servidores, APIs, funciones en la nube, etc. La lógica de la app es todo lo que se encuentra del lado del cliente y tiene alguna conexión con el backend y el frontend, se podría decir que es la capa intermedia entre estas dos. Por ejemplo, los modelos, repositorios y controladores que están del lado del cliente.

Teniendo esto en cuenta, el desarrollo del backend puede abarcar diferentes cosas dependiendo de los requerimientos tecnológicos del proyecto. Por ejemplo, en un proyecto normal que utiliza la arquitectura estándar de Paulonia, el desarrollo de backend sólo implicaría la configuración de Firebase, las cloud functions y la configuración de los servicios extra que necesite la aplicación. Otro ejemplo sería un proyecto el cual un requerimiento tecnológico sea la creación de una API GraphQL, en este caso, el desarrollo del backend implicaría la implementación del servidor, de la base de datos y de la API GraphQL lista para ser usada en la lógica de la app.

En esta etapa también se configura el repositorio que va a ser usado para el desarrollo, siguiendo los lineamientos de la arquitectura de repositorios de Paulonia. Además también involucra la configuración DevOps del repositorio y del proyecto. Es recomendable realizar esta tarea primero que nada ya que otros desarrolladores pueden necesitar del repositorio.

## Desarrollo de la lógica de la app

---

- **Input necesario:**
    - Documento de Requerimientos
    - Flujo de desarrollador de los diseños
    - Backend implementado
- **Input opcional:**
    - Cualquier documento/gráfico que ayude a la tarea
- **Output:**
    - Lógica de la aplicación implementada

---

Recapitulando el contexto, la lógica de la app es todo lo que va en el lado del cliente y es el canal entre el backend y el frontend. La finalidad y principal objetivo que siempre se tiene que tener en cuenta al desarrollar en esta etapa es que los datos del backend sean lo más presentables y funcionales posibles para que el frontend pueda utilizarlos.

Todas las aplicaciones (salvo excepciones extraordinarias) deben seguir la arquitectura de la lógica de la app de Paulonia. Las tecnologías o paquetes a utilizar en cada capa de la arquitectura queda a criterio del líder de equipo de backend del proyecto

En esta etapa pueden salir entregables iterativos que el frontend ya puede ir usando en sus implementaciones. Además esta etapa es la más larga y compleja, ya que requiere de revisiones, tests y arreglos constantes a issues o bugs (tanto en backend como en lógica) que pueden ir surgiendo a lo largo del desarrollo.

### Proceso de desarrollo de una funcionalidad

El proceso comienza con la creación del ticket respectivo en Jira y siendo asignado a él. Desarrollar lo especificado en el ticket y ser proactivo en las cosas que faltarían desarrollar para cumplir la funcionalidad pero no está especificado en el ticket. Mientras se está desarrollando es recomendable ir subiendo tus cambios a un draff pull request para que tus avances sean visibles al equipo.

Al terminar el desarrollo de la funcionalidad, subir tus cambios al pull request, agregar una descripción de lo que se ha desarrollado y las funciones que el frontend utilizará para cumplir con la funcionalidad. Además agregar el link del ticket al que pertenece el pull request. Colocar el ticket en ‘Waiting for’ y avisar al revisor que está listo para revisar (por ahora al líder del equipo).
El revisor debe percatarse de que los test y el build pasen, revisar todo el código, y revisar que todas las funciones que el frontend usará cumplan con el requerimiento y funcionalidades especificadas en el ticket.
El revisor es el encargado de aprobar el Pull request y realizar el merge, asegurarse de que la branch es eliminada. 
En este punto la tarea está terminada y se puede mover el ticket a ‘Done’

## Arreglo de bugs en lógica de la app

---

- **Input necesario:**
    - Issues en Github de los bugs
- **Input opcional:**
    - Cualquier otro documento que ayude a la resolución del issue
- **Output:**
    - Pull requests que arreglan los issues

---

Esta etapa puede darse durante la etapa de Desarrollo de la lógica de la app o después de esta al realizarse la etapa de testing del proyecto. En el primer caso los desarrolladores frontend son los encargados de crear los Issues, en el segundo caso, el encargado del testing es el encargado de crear los Issues.
Si el bug detiene el desarrollo del frontend es considerado de alta prioridad y debe resolverse lo más pronto posible.
En otro caso, si es que el deadline del proyecto lo permite, pueden ser planificados dentro de un sprint.

## Subida a las tiendas

---

- **Input necesario:**
    - Una versión lista y testeada
- **Input opcional:**
    - Cualquier otro documento que ayude a la tarea
- **Output:**
    - Una versión subida a las tiendas

---

Luego de terminado el desarrollo o durante el desarrollo, si se necesitan entregables constantes, es necesario subir una versión a las tiendas. Para esto se necesita tener configurado el backend de producción. Además de tener configurado la rama de repositorio que va a contener el código de producción. Todo esto lo puedes consultar en la documentación para configurar Firebase en producción y la documentación de la subida a tiendas.
Para un futuro se está pensando automatizar la configuración de Firebase a producción y la subida a tiendas (Continuous Delivery).

## Desarrollo de nuevas funcionalidades

Dependiendo del Project Manager, las nuevas funcionalidades pueden venir en una conjunto grande (una nueva fase para sacar una nueva versión grande) o en grupos pequeños. 
Dependiendo de la complejidad de las tareas, en unos casos se debería empezar todo el proceso desde la etada de investigación, pero en otros casos se podría emprezar desde el desarrollo del backend; esto queda a criterio del lider de equipo.
