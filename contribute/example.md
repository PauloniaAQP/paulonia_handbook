---
title: Documento de ejemplo
quote:
    content: Frase a mencionar
    author: Nombre del autor
    authorPosition: 1876 - 1958
pagination:
    previous:
        link: ../constants
        name: Constantes
---

Este documento sirve de ejemplo para mostrar las funcionalidades de Jekyll y algunas sintaxis de markdown y HTML. Puedes ver este documento en [GitHub](https://github.com/PauloniaAQP/paulonia_handbook/blob/main/contribute/example.md).

La tabla que se forma arriba son los [parámetros del documentos](../parameters), puedes ver el raw del documento [aquí](https://raw.githubusercontent.com/PauloniaAQP/paulonia_handbook/main/contribute/example.md)

---

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***

## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

- [link text](https://paulonia.dev/)
- [link with title](https://paulonia.dev/ "title text!")

- [Document in the same section](../links)
- [Document in another section](../../studios/roles)
- [Other example of document in another section](../../backend/procesos/desarrollo)
- [Index document](../../studios/)
- [Root of handbook](/)

- [Current document section](#code)
- [Section in other document](../../studios/roles/#roles)


## Site constants

- {{site.title}}
- {{site.description}}
- {{site.handbook_leader_name}}
- {{site.contact}}

## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


## [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

## HTML

<center><b>CALIDAD</b></center>
<p></p>
<center>Creamos diseños de alta calidad y brindamos apoyo para que los nuevos miembros
lo sean capaz. Todos los diseñadores tienen una amplia experiencia en el manejo de
herramientas UX y UI, y familiarizadas con la mayoría de tecnologías empleadas en
los proyectos de Paulonia.</center>

&nbsp;&nbsp;&nbsp;

<center><b>EMPATÍA</b></center>
<p></p>
<center>Nos enfocamos en entender y comprender como se sienten nuestros clientes y
miembros de nuestro equipo frente a los proyectos, con el objetivo de ser cordiales,
abiertos y resilientes.</center>