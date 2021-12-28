---
title: Procesos de mantenimiento
lead: false
---

## Mantenimiento (producción)

---

- **Input necesario:**
    - Errores reportados por usuarios
    - Errores reportados en Sentry
- **Input opcional:**
    - Cualquier otro canal que proporcione listados de errores
- **Output:**
    - Pull request que arreglen los errores

---

Por ahora se tienen dos tipos de errores: los que son reportados por usuarios y dueños de negocio, y los que llegan al listado de errores de Sentry.
Los primeros suelen ser los más críticos ya que afectan de una u otra manera a la experiencia del usuario (ya que han sido detectados por los usuarios). Siendo o no críticos siempre tiene que haber un ticket en jira con la descripción del mismo y cómo reproducirlo (si se tiene esa info). 

Para los errores reportados en Sentry se necesita realizar un acuerdo con el cliente, ya que requieren horas de trabajo de mantenimiento. Si el acuerdo existe, entonces el encargado tendrá que hacer una revisión al listado de bugs antes de que comienze cada sprint. En esta revisión deberá organizar y limpiar el listado debugs, y no debe demorar más de 2 horas de trabajo:

- Deberá identificar los bugs que ya fueron resueltos (issues de anteriores versiones)  y marcarlos como resueltos para esa versión.
- En algunos casos el Sentry genera issues separados que terminan siendo el mismo. Para estos casos identificar si son el mismo problema y combinar los issues.
- Para los nuevos issues crear un ticket en Jira, colocar el link del issue en el ticket y colocar el link del ticket en un comentario en el issue en Sentry.

Dependiendo de la gravedad de los issues creados en esta revisión, los tickets pueden entrar al siguiente sprint o pueden servir como tareas adicionales para las personas que necesiten tareas en el sprint. Es recomendable que una persona que haya estado involucrado en el proyecto realize esta revisión, para que así él pueda identificar errores críticos.

Luego, en el sprint se comenzaría una ronda de resolución de bugs y terminaría subiendo una nueva versión a tiendas.
