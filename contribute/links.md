---
title: Links en un documento
pagination:
    next:
        link: ../constants
        name: Constantes
    previous:
        link: ../parameters
        name: Parámetros
---

Los links son muy importantes en un documento ya que ayudan a una mejor navegación y a referenciar información de fuentes externas o del mismo handbook. Por eso es necesario aprender cómo utilizar los diferentes tipos de links.

### Links externos

Los links externos no han tenido ningún cambio y se pueden usar de la misma forma con el formato Markdown:

```
[Este es un link externo](https://paulonia.dev/)
```

- [Este es un link externo](https://paulonia.dev/)

### Links internos o de navegación

Estos links son los que apuntan a otro documento dentro del handbook. Son especiales ya que no se utiliza una url como los links externos. Como ya hemos visto antes, los documentos son archivos y las secciones son carpetas. Siguiendo esta misma lógica, las urls son paths a archivos y carpetas, y un link sería el path que se utiliza para llegar a ese archivo usando el comando [cd de linux](https://linuxize.com/post/linux-cd-command/).

Aquí algunos ejemplos:

```
[Documento en la misma sección](../example)
[Documento en otra sección](../../studios/roles)
[Otro ejemplo en otra sección](../../backend/procesos/desarrollo)
[Otro ejemplo en un index](../../studios/)
[Página principal del handbook](/)
```

- [Documento en la misma sección](../example)
- [Documento en otra sección](../../studios/roles)
- [Otro ejemplo en otra sección](../../backend/procesos/desarrollo)
- [Otro ejemplo en un index](../../studios/)
- [Página principal del handbook](/)

Además de apuntar al documento, se puede apuntar a las secciones del documento de la sigueinte manera:

```
[Sección en el documento actual](#links-externos)
```

- [Sección en el documento actual](#links-externos)
- [Sección en otro documento](../../studios/roles/#roles)
