---
title: Preguntas frecuentes
pagination:
    previous: 
        link: ../maintenance
        name: Mantenimiento 
---

## Introducción
Se ofrece aquí respuesta a una selección de las preguntas más frecuentes planteadas por nuestros clientes del servicio de mantenimiento.

#### Índice
+ [Conceptos generales](#conceptos-generales)
+ Proceso
1. [Identificación y clasificación](#1-identificaci%C3%B3n-y-clasificaci%C3%B3n)
2. [Análisis](#2-an%C3%A1lisis)
3. [Diseño y/o implementación](#3-dise%C3%B1o-yo-implementaci%C3%B3n)
4. [Validación, verificación y aceptación de pruebas](#4-validaci%C3%B3n-verificaci%C3%B3n-y-aceptaci%C3%B3n-de-pruebas)
5. [Entrega y despliegue](#5-entrega-y-despliegue)

## Conceptos generales
#### ¿Qué es una solicitud de mantenimiento?
Se refiere a toda petición de cambio, modificación, actualización, resolución de errores, que velen por el bienestar de un sistema, asegurando su completo funcionamiento y usabilidad.

Cada solicitud de mantenimiento puede nacer a raíz de:
+ Eventos reportados por el personal de Paulonia por SENTRY (cuando un sistema ya esta en producción). Estos eventos son producidos por la interacción de los usuarios con el sistema.
+ Eventos reportados por el cliente. Estos evetos son producidos por la intención de prevenir, mejorar o corregir el sistema

#### ¿Qué es SENTRY?
SENTRY es un servicio integrado a cada aplicación donde llegan reportes de errores o comportamientos anómalos, estos reportes se convierten en nuevas solicitudes de mantenimiento. Estos errores pueden ser visibles o no ante los usuarios, lo que significa que es posible detectar problemas internos o de lógica de cada aplicación. Este servicio está totalmente automatizado.

#### ¿Qué es una BOLSA?
Cada mes durante la vigencia del contrato de mantenimiento, se generan solicitudes de mantenimiento. Estas solicitudes pasan a un contenedor (MRC). Este contenedor almacena todos las solicitudes, pero no significa que todas estas vayan a ser atendidas y resueltas en el mismo mes que hayan sido reportados.

Todas las solicitudes de mantenimiento del MRC tienen que pasar por un proceso de análisis, en el cual el personal de Paulonia determina el nivel crítico y urgencia de cada uno de ellos. Todos las solicitudes aprobadas entran a una BOLSA.

Una BOLSA almacena todas las solicitudes que serán atendidas y resueltas a lo largo de un mes.

![Whats a bag](../../../images/BAG.png "Whats a bag")

Tambien le puede interesar
- [¿Cómo se determina la capacidad de una BOLSA?](#%C2%BFc%C3%B3mo-se-determina-la-capacidad-de-una-bolsa)
- [¿Qué sucede con las solicitudes no aprobadas?](#%C2%BFqu%C3%A9-sucede-con-las-solicitudes-no-aprobadas)


## 1. Identificación y clasificación

#### ¿Cuántas solicitudes de mantenimiento pueden ser reportadas?
No existe un límite mínimo ni máximo de solicitudes que se puedan realizar. 

#### ¿Existe una fecha límite para reportar o no una solicitud de mantenimiento?
No, el cliente o el personal de Paulonia pueden hacer solicitudes de mantenimiento tantas veces sea necesario o requerido.

Sin embargo, si se realiza una solicitud de mantenimiento en las fechas finales de un mes y se espera que se resuelvan ese mismo mes, existe un alto riesgo de no ser analizado ni atendido en el plazo deseado o esperado.

#### ¿Qué hacer si la solicitud de mantenimiento no se puede clasificar en ninguna de las categorías?
Las [categorías de mantenimiento](../maintenance/#1-identificaci%C3%B3n-y-clasificaci%C3%B3n), están basadas y estandarizadas a nivel internacional, aplicándose a distintos sistemas, por lo que se tiene que tener la seguridad que la solicitud de mantenimiento va a ser clasificada en al menos una categoría.




## 2. Análisis

#### ¿Cómo se determina la capacidad de una BOLSA?
Cada mes durante la vigencia del contrato de mantenimiento, el personal de Paulonia destinará cierto monto de horas para atender las solicitudes de mantenimiento aprobadas. 

El personal de Paulonia escogerá cada solicitud de mantenimiento bajo las siguientes condiciones:
1. El nivel crítico de la solicitud de mantenimiento
2. La urgencia de la solicitud de mantenimiento
3. Las horas estimadas para su solución no excedan el monton de horas destinadas mensualmente

> **Por ejemplo**
> Paulonia destina 20 horas en todo el mes de Enero para resolver sus solicitudes de mantenimiento. Se tienen 3 solicitudes cuyas horas estimadas de resolución son: 

>> **Solicitud A** = 12 horas; **Solicitud B** = 9 horas y; **Solicitud C** = 7 horas

> Por lo tanto, las solicitudes A y C son las que irán a su BOLSA y la solicitud B quedará en espera.

#### ¿Cuánto puede demorar el análisis de una solicitud de mantenimiento para ser aprobada su resolución?
Cada solicitud de mantenimiento tiene un grado crítico dependiendo de su clasificación. Es casi seguro que las solicitudes correctivas y preventivas pueden analizarse en cuestión de minutos u horas. Sin embargo, las solicitudes adaptativas y de emergencia pueden tomar desde horas hasta 2 días para su análisis y posterior aprobación o desaprobación.

#### ¿Qué sucede con las solicitudes no aprobadas?
Estas solicitudes pasan a ser aprobadas y resueltas (ya no se analizan, a no ser que haya surgido algún cambio) al siguiente mes.

#### ¿Cómo se analiza las solicitudes [perfectivas](../maintenance/#1-identificaci%C3%B3n-y-clasificaci%C3%B3n)?
Este tipo de solicitudes pasa por un proceso especial de análisis, en el que pueden incluir varias áreas de Paulonia. Estas solicitudes, al traer consigo nuevas funcionalidades, nuevo comportamiento y hasta nueva lógica, puede influir en un bajo o alto número de cambios o agregaciones. 

En este proceso también se analiza a fondo la complejidad y urgencia de resolución. Bajo la experiencia en el mercado de Paulonia, se detecta un gran índice de funcionalidades altamente complejas.

Una vez analizada esta solicitud perfectiva, se puede tomar dos decisiones
1. Realizarla, bajo el riesgo de exceder las horas límite de la [BOLSA](#%C2%BFqu%C3%A9-es-una-bolsa), que recae en el cobro de horas extras en la factura mensual del cliente.
2. Crear una nueva fase de desarrollo ([Documento en progreso](https://paulonia.atlassian.net/browse/TOMENTOSA-1630))

## 3. Diseño y/o implementación
#### No se me ocurren preguntas



## 4. Validación, verificación y aceptación de pruebas
#### ¿Cómo saber si se realizó un control de validación y verificación?



## 5. Entrega y despliegue
#### ¿Existe un pago extra por cada entregable?
No, todos los costos facturados son por conceptos de solicitudes de mantenimiento y lo que estos impliquen.