---
title: Procesos de estructuración
pagination:
    next:
        link: ../desarrollo
        name: Desarrollo
    previous:
        link: ../
        name: Planificación
---

## Estructuración inicial de la base de datos

---

- **Input necesario:**
    - Documento de Requerimientos
- **Input opcional:**
    - Diseños de la aplicación
- **Output:**
    - Documentación de la estructura inicial de la base de datos

---

Esta etapa puede ser paralela con el diseño al tener un documento de requerimientos que especifique los modelos básicos. También se puede esperar a que Paulonia Studios entregue el diseño y fusionar esta etapa con la siguiente (Estructuración final de la base de datos y lógica de la app).
En esta etapa se maqueta la estructura inicial de la base datos, se tendría que tomar en cuenta modelos básicos con sus campos básicos (CRUDS básicos) y no tomar en cuenta todavía cosas que tengan que ver con la lógica de la app, ya que para tener un panorama completo de la lógica, se necesitan el Flujo de desarrollador de los diseños.

## Estructuración final de la base de datos y lógica de la app

---

- **Input necesario:**
    - Documento de Requerimientos
    - Flujo de desarrollador en los diseños
- **Input opcional:**
    - Cualquier documento, gráfico o video que ayude al entendimiento de la lógica de la app
- **Output:**
    - Documentación de la estructura de la base de datos
    - Cualquier gráfico necesario para un mejor entendimiento de la lógica de la app

---

En esta etapa se realiza la estructura final de la base de datos teniendo en cuenta la lógica de la app que se muestra en el flujo de desarrollador. En otras palabras, se tienen que tener en cuenta funcionalidades más complejas que CRUDS básicos (cambios de estados, feeds complejos, estadísticas, etc). En esta etapa también se deben realizar documentación/gráficos que ayuden a entender mejor la lógica más adelante en el desarrollo. Uno de estos es el gráfico de estados, en el documento de la estructura de la base de datos se van a tener todos los estados posibles de un modelo, pero también es necesario el cómo cambiarían cada estado. La idea de esta etapa es tener mapeada toda la lógica de la aplicación en la estructura de la base de datos y en la demás documentación que se entregue, con la finalidad de hacer el desarrollo menos complejo y más rápido.
