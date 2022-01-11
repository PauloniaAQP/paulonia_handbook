---
title: Crear un documento
pagination:
    next:
        link: ../parameters
        name: Parámetros
    previous:
        link: ../
        name: Contribuir
---

## Preparación

Antes de cualquier cosa, es necesario tener configurada las herramientas y las dependencias para poder probar su nuevo documento o lo que vaya a agregar. Para ello es necesario que tenga instalado lo siguiente:

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [jekyll](https://jekyllrb.com/docs/installation/ubuntu/)

Clone el repositorio del [handbook-theme](https://github.com/PauloniaAQP/handbook-theme) junto con el submódulo del [paulonia_handbook](https://github.com/PauloniaAQP/paulonia_handbook) con el siguiente comando:

```
git clone --recurse-submodules https://github.com/PauloniaAQP/handbook-theme.git
```

En la carpeta principal del repositorio ejecutar el siguiente comando para compilar la página:

```
jekyll serve
```

Corra a su [localhost](http://127.0.0.1:4000/) y verifique que la página funciona.

Los documentos se colocan en la carpeta `paulonia_handbook`, este es un [submódulo](https://git-scm.com/book/en/v2/Git-Tools-Submodules). Los submódulos actuan como repositorios dentro de otros repositorios, es decir si haces cambios dentro de la carpeta `paulonia_handbook` y haces commits de esos cambios, todo se va a subir al repositorio de `paulonia_handbook`; de la misma manera, si haces cambios fuera de `paulonia_handbook`, todo se va a subir al repositorio de `handbook-theme`.

Si sólo quiere crear un documento no tiene que hacer cambios fuera de `paulonia_handbook`, así que trabajaremos ahí el resto del tutorial. Pero antes de hacer cualquier cambio, cree una rama nueva con el siguiente comando:

```
git branch -b <nombre-de-su-rama>
```

El nombre lo eliges tú. Si haces cambios en la rama `main`, probablemente no puedas subir esos cambios al repositorio. Con esto ya estaría listo para crear su documento.


## Creación

Antes de crear y empezar a escribir un documento, detente a pensar si es necesario crear uno nuevo o se puede agregar en otro documento. Si es algo nuevo, entonces detente a pensar en qué parte del handbook se va a colocar: ¿Es de un área específica de la empresa o es algo general? ¿Se necesita una nueva sección para este documento? Si aún tienes dudas sobre esto, puedes preguntar al encargado actual del Handbook ({{site.handbook_leader_name}}).

Si es necesario crear una nueva sección/sub-sección, crea la carpeta donde corresponda con un nombre que pueda ser entendido a simple vista. 

Crear el documento con la extensión markdown donde corresponda. El nombre del archivo debe lucidar el contenido del documento, puede ser el título, pero no es obligatorio que sea éste tal cual. El nombre que se le ponga va a ser el nombre por el cual se va a llegar al documento mediante la url. Ej. para un documento `myFirstDoc.md` dentro de `development`, su url será `paulonia_handbook/development/myFirstDoc`. A partir de acá, por fines de este tutorial, supongamos que hemos creado este documento.

## Redacción

### Parámetros del documento

Es lo primero a tener en cuenta para tener configurado bien un documento. Se coloca en la parte superior del documento y tiene la siguiente forma:

```
---
variable1: Valor
variable2: Valor
variableMapa:
    variable3: valor
    variable4: valor
---
```

La única variable obligatoria es `title`, que es necesaria para renderizar el título del documento. Otra variable importante (pero no obligatoria) es `pagination`, que se utiliza para saber cuál documento es el anterior y cuál es el siguiente. Para más información sobre este y más parámetros, revisar [Parámetros de un documento](../parameters).

### Escribir el documento

Una vez colocados los parámetros, ya podemos ver nuestro documento renderizado en la página. Si ya haz ejecutado el comando `jekyll serve`, entonces sólo basta con que vayas a la url de tu documento. Ex. `http://127.0.0.1:4000/paulonia_handbook/development/myFirstDoc`. Mientras escribes tu documento, puedes ir guardando los cambios y refrescando la página para ver el renderizado.

El contenido del documento es libre y puedes utilizar markdown para escribir cosas simples y HTML para agregar cosas más complejas y estilizadas. Además es necesario saber los recursos que nos probee jekyll y el tema para la escritura de un documento:

- [Links en un documento](../links)
- [Constantes de sitio](../constants)
- [Ejemplo de un documento](../example)

## Creación del Pull Request

Una vez terminado el documento, tienes que agregar tus cambios a un commit con los siguientes comandos (recuerda ejecutarlos dentro de `paulonia_handbook`)

```
> git add --all
> git commit -m '<mensaje-del-commit>'
```

Asegurate de que el mensaje del commit describa a detalle los cambios que se están agregando. **Recuerda escribir este mensaje en Inglés.** Luego sube tus cambios al repositorio:

```
git push -u origin <nombre-de-su-rama>
```

Si todo fue bien, debería aparecerle un mensaje con el link para crear el Pull Request, o lo puede hacer desde la [web de Github](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

El Pull Request siempre debe apuntar a `main`. En la descripción del Pull Request coloque un pequeño detalle de sus cambios. Luego de crear su Pull Request, éste va a pasar por un proceso de revisión y luego publicado en el repositorio. 

