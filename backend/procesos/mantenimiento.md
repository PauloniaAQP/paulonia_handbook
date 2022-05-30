---
title: Procesos de mantenimiento
pagination:
    previous:
        link: ../desarrollo
        name: Desarrollo
---

## Mantenimiento (producción)

---

- **Input necesario:**
    - Eventos reportados por el cliente/usuario
    - Eventos reportados por Sentry
    - Eventos reportados por desarrolladores
- **Input opcional:**
    - Cualquier otro canal que proporcione eventos
- **Output:**
    - Pull request que arreglen los errores

---

Todo el proceso de mantenimiento se encuentra explicado en el [Documento de Mantenimiento](/{{site.handbooks_path}}/paulonia/lifecycle/maintenance), antes de seguir leyendo aquí es mejor leer el proceso de mantenimiento de la empresa.
En este documento explicaremos lo que un desarrollador backend hace a lo largo de este proceso.

##### 1. Identificación y clasificación

En esta parte del proceso, los desarrolladores backend pueden dar su opinión a la hora de la clasificación de los eventos.

##### 2. Análisis

En el análisis, dependiendo del evento existe un proceso.

Para los eventos reportados por el cliente/usuario y desarrolladores el análisis lo hace un desarrollador asignado por el team lead; es recomendable que el encargado sea alguien que ya haya trabajado antes en el proyecto/funcionalidad. Lo que tiene que hacer el desarrollador es analizar el evento y dar una estimación de cuánto podría tomar, en horas, implementar o arreglar dicho evento. **El análisis de cada tarea no puede durar más de 3 horas en los peores casos**.

Para los eventos reportados por Sentry, se asignará un desarrollador que analize todos los errores de Sentry. Una ver por sprint, el encargado tendrá que hacer una revisión al listado debugs. En esta revisión se deberá organizar, analizar y limpiar el listado. En Sentry los eventos generalmente son de categoría **Correctiva**. **Esta tarea no debería demorar más de 4 horas**:

- Deberá identificar los bugs que ya fueron resueltos (issues de anteriores versiones)  y marcarlos como resueltos para esa versión.
- En algunos casos el Sentry genera issues separados que terminan siendo el mismo. Para estos casos identificar si son el mismo problema y combinar los issues.
- Para los nuevos issues crear un ticket en Jira, colocar el link del issue en el ticket y colocar el link del ticket en un comentario en el issue en Sentry. Analizar cuánto puede tomar el issue y agregar una estimación.

Para los eventos **Adaptativos** que tengan que ver con actualización de dependencias en el proyecto se tendrá el siguiente proceso si el cliente lo aprueba:

- En el sprint del inicio de cada mes se creará un evento para actualizar dependencias del proyecto. **Esta tarea no debería tomar más de 8 horas**
- Si esta tarea es aprobada para su resolución, entonces se pasará a su implementación.

**Nota: Tener en cuenta el despliegue de la aplicación en cuentas en la estimación de las tareas. Generalmente se debe dar al teminar el sprint luego de resolver las tareas de mantenimiento asignadas en ese sprint**


##### 3. Diseño y/o implementación

En esta parte, dependiendo de la índole de la tarea, los procesos son los mismos descritos en los [Procesos de Desarrollo](../desarrollo)

##### 4. Validación, verificación y aceptación de pruebas

En esta parte del proceso las personas encargadas de [revisar cada tarea implementada](../desarrollo#proceso-de-desarrollo-de-una-funcionalidad) son los encargados de revisar y validar la calidad del código y la escalabilidad de lo implementado.

##### 5. Entrega y despliegue

En esta parte, se debe seguir el [El proceso de subida a tiendas](../desarrollo#subida-a-las-tiendas).
