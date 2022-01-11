---
title: Parámetros de un documento
pagination:
    next:
        link: ../links
        name: Links
    previous:
        link: ../howToDocument
        name: Crear un documento
---

Es la primera parte del documento y es donde se manejan diferentes variables usadas en el tema de Jekyll para poder agregar funcionalidades o renderizar nuevas partes dentro del documento. Esta parte se ubica en la parte superior del documento y tiene la siguiente forma:

```
---
variable1: Valor
variable2: Valor
variableMapa:
    variable3: valor
    variable4: valor
---
```

Puedes ver un ejemplo de su uso en el [Documento de Ejemplo](../example)

Existen los siguientes parámetros:

- **title:** Un string, es el título del documento que se renderiza en la página.

- **pagination:** Un mapa con el documento siguiente y anterior. Al agregar este mapa, en el documento se agregan botonos siguiente y anterior para una mejor navegación. Tiene los siguientes parámetros:
    - **next:** Mapa que contiene los datos del siguiente documento. se puede omitir en el caso no haya un documento siguiente. Tiene los siguientes parámetros:
        - **link:** El link relativo del documento. Para más información de cómo colocar links, ver [Links](../links).
        - **name:** Nombre que va a ser mostrado junto al botón de siguiente.
    - **previous:** Mapa que contiene los datos del anterior documento. Se puede omitir en el caso no haya un documento anterior. Tiene los siguientes parámetros:
        - **link:** El link relativo del documento. Para más información de cómo colocar links, ver [Links](../links).
        - **name:** Nombre que va a ser mostrado junto al botón anterior.
- **quote:** Mapa para generar una cita al inicio del documentos. Tiene los siguientes parámetros:
    - **content:** El contenido de la cita.
    - **author:** El nombre del autor de la cita. Es opcional.
    - **authorPosition:** Sub título del autor, generalmente su posición u ocupación. Es opcional.
