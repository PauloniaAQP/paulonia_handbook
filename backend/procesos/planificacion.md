---
title: Procesos de planificación
lead: false
---

## Etapa de investigación

---

- **Input necesario:**
    - Documento de Requerimientos
- **Input opcional:**
    - Cualquier otro documento que pueda servir para la investigación
- **Output:**
    - Documentación para cada incertidumbre encontrada

---

Antes de comenzar un nuevo proyecto o una nueva épica que agregue un nuevo módulo o una gran funcionalidad debe haber una etapa de investigación. Aquí se resuelven todas las incertidumbres respecto a la arquitectura, algoritmos complejos y tecnologías nuevas a usar en el proyecto.
El tiempo que demore esta etapa depende del número de incertidumbres a investigar, pero no debe demorar más de un sprint, porque esta etapa mayormente es considerada en el sprint 0.

## Planeación de la arquitectura

---

- **Input necesario:**
    - Documento de Requerimientos
- **Input opcional:**
    - Cualquier otro documento que pueda servir para la planeación de la arquitectura
- **Output:**
    - Documentación de la arquitectura a usar

---

En esta etapa se crea la arquitectura principal de la aplicación, sus servicios y la base de datos. Se tiene que ver en dónde va a estar alocado el backend de la aplicación y la integración con los diferentes servicios. En Paulonia estamos especializados en Google Cloud Platform y Firebase, así que ya se tiene una arquitectura base para las aplicaciones que utilicen estos servicios. Si por razones tecnológicas o del cliente se va a utilizar otras tecnologías (servidores físicos u otro proveedor de la nube), entonces el pensar cómo armar la arquitectura en esa tecnología se realiza en esta etapa.

Además, se necesita ver cómo integrar servicios externos a la arquitectura, como por ejemplo un servicio de streaming de video, o un servicio de mensajería. Lo mismo ocurre con la base de datos, dependiendo de la tecnología, se necesita saber cómo se va a integrar esta a la arquitectura de la aplicación.

