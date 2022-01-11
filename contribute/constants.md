---
title: Constantes de sitio
pagination:
    next:
        link: ../example
        name: Ejemplo
    previous:
        link: ../links
        name: Links
---

Jekyll nos ofrece la funcionalidad de crear constantes de sitio que se pueden utilizar en todos los documentos. Puedes ver el listado completo de estas constantes en el archivo [`handbook-theme/_config.yml`](https://github.com/PauloniaAQP/handbook-theme/blob/theme/_config.yml). Puedes utilizar una constante en cualquier documento de la siguiente manera, sin los espacios entre las llaves:

```
El encargado principal del handbook es { {site.handbook_leader_name} }
```

El encargado principal del handbook es {{site.handbook_leader_name}}

