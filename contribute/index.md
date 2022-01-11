---
title: Contribuir al Handbook
lead: true
quote:
    content: Sharing knowledge is the most fundamental act of friendship. Because it is a way you can give something without loosing something.
    author: Richard Stallman
    authorPosition: Free Software Foundation
pagination:
    next:
        link: ./howToDocument
        name: Crear un documento    
---

Gracias por el interés de contribuir al Handbook de Paulonia. Recibimos con los brazos abiertos a los comentarios, correcciones y adiciones, así como sugerencias para documentos y secciones adicionales a discutir. En estos documentos encontrarás la estructura, redacción, tips y procesos para poder contribuir a nuestro
Handbook.

## Glosario

Antes de comenzar a detallar cualquier parte del handbook es necesario tener en claro algunas definiciones para evitar cualquier confusión.

- **Documento:** Son las piezas fundamentales del handbook y transmiten cierta información de forma individual. Los documento son archivos Markdown (`.md`) y cada documento tiene una url asociada y debe estar dentro de una sección del Handbook.
- **Sección del Hanbook:** (o en muchos casos sólo Sección) Son grupos de documentos y sub-secciones. Las secciones y sub-secciones son carpetas y son los principales grupos que aparecen en el menú de la barra lateral derecha de la página.
- **Sección de un Documento:** Son las partes de un documento separados por un header, pueden ser referenciados mediante la url.

## Herramientas

Para construir este Handbook utilizamos tres herramientas principales:

- **Markdown:** Es el principal formato utilizado para escribir los documentos. Este documento está escrito en Markdown! Pará empezar, es necesario saber la [sintaxis de Markdown](https://www.markdownguide.org/cheat-sheet/). 
- **Github:** Herramienta utilizada para versionar y revisar los documentos del Handbook. Aquí es donde se suben nuevos documentos o cambios a los ya existentes y se empieza una discusión de los mismos. 
- **Jekyll:** Es el [framework](https://jekyllrb.com/) utilizado para generar la página web del Handbook a partir de los documentos en Markdown. 

## Estructura

El proyecto está dividido en dos repositorios:

- [Documentos del Handbook](https://github.com/PauloniaAQP/paulonia_handbook): En este repositorio están todos los documentos del handbook. Aquí las carpetas deben ser vistas como secciones en el handbook, pueden haber sub-secciones (sub-carpetas) y cada sección debe tener por lo menos un documento. Las secciones son las que aparecen en el menú derecho.
- [Proyecto en Jekyll](https://github.com/PauloniaAQP/handbook-theme): El proyecto es un fork de un tema opensource. El proyecto tiene un submódulo apuntando al repositorio de los documentos del handbook. El proyecto ya se encuentra configurado para poder compilar la página con el submódulo. Para más info leer el README del repositorio y para más info para contribuir a este tema, revisar la [Documentación de Jekyll](https://jekyllrb.com/docs/).


Continue con el siguiente documento de un pequeño [tutorial de cómo crear un documento](./howToDocument).