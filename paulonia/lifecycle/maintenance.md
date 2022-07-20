---
title: Mantenimiento
pagination:
    next:
        link: ../frequestions
        name: Preguntas
    previous:
        link: ../ 
        name: Ciclo de vida
---

La fase de mantenimiento comprende únicamente al proceso de cambiar, modificar o actualizar un proyecto, bajo el principio de siempre atender la necesidad de los usuarios o conservar la estabilidad del sistema. Cabe recalcar que este proceso **inicia luego del despliegue en el mercado del proyecto** (haya sido realizado por Paulonia o no), pues es aquí donde se presentarán problemas o errores, o se pretende mejorar el rendimiento y desempeño del proyecto, entre otros procesos.

## Proceso
Si se pregunta como dar mantenimiento a su aplicación, está en el lugar indicado. En esta sección lo guiaremos a través los pasos o procesos que usted y su aplicación pasarán a lo largo del mantenimiento.


|![General Process](../../../images/MaintenanceProcess.png "Maintenance process")|
|:--:|
|*Proceso general de mantenimiento*|


#### Antes de iniciar
Previo a iniciar esta fase, necesita tener conocimientos de los siguientes puntos
+ Usted (el cliente) y Paulonia determinarán un límite de horas por cada mes ([BOLSA](../frequestions/#%C2%BFqu%C3%A9-es-una-bolsa) desde ahora) destinada a la atención de solicitudes de mantenimiento, hasta finalizar su contrato. *Por ejemplo 20 horas al mes, por 5 meses*
    + Las horas invertidas en mantener su aplicación serán facturadas a final de cada mes
    + Si se llegara a exceder el límite de esta [BOLSA](../frequestions/#%C2%BFqu%C3%A9-es-una-bolsa) , esto se verá reflejado en su factura de cada mes. *¡Tenga cuidado!*
+ Se aconseja que predisponga de tiempo durante y después de una solicitud de mantenimiento, dado que en cualquier paso del proceso un encargado de Paulonia puede comunicarse con usted o su equipo.

[¿Tiene preguntas?](../frequestions/#1-conceptos-generales)

#### ¡Iniciemos!

##### 1. Identificación y clasificación
Una solicitud de mantenimiento puede ser hecha por usted (el cliente) o Paulonia, a raíz de la **identificación** de un problema, error, cambio o actualización. La identificación de estos eventos tienen que ser clasificados y priorizados, de tal manera Paulonia le informará que solicitudes serán atendidas con mayor urgencia que otras. 

Estos eventos pueden caer en cualquiera de estas 4 categorías de mantenimiento


| Categoría     | Descripción   |
| :-:             | -             |
| **Perfectivo**<br />(Prioritario)   | Si desea mejorar su aplicación añadiendo nuevas funcionalidades o modificando las ya existentes, que recae en un alto grado de alteración del código fuente.*Tenga en cuenta que si una funcionalidad es demasiado grande o compleja, es recomendable iniciar una nueva fase de desarrollo y no de mantenimiento* |
| **Emergencia**<br />(Crítico)    | Si se detecta un problema o error que impida el funcionamiento total o parcial de la aplicación y cuya atención deba ser inmediata por parte de Paulonia.|
| **Adaptativo**<br />(Importante)    | Cuando se desee actualizar el sistema, servidores, paquetes, porciones de código u otras dependencias.|
| **Preventivo**<br />(Moderado)    | Si se desea reducir la complejidad de la aplicación, así como cambios livianos que reduzcan la ocurrencia de errores futuros.|
| **Correctivo**<br />(Moderado)    | Si se detecta pequeñas fallas en funciones existentes de la aplicación, sea en el diseño o lógica. *Esté muy atento a sus usuarios, pues son quienes lo causarán o reportarán*|

> **Recuerde**: En este punto, Paulonia aún no ha decidido que evento atenderá durante el mes actual, y que no todos los eventos serán atendidos. 

[¿Tiene preguntas?](../frequestions/#identificaci%C3%B3n-y-clasificaci%C3%B3n)

##### 2. Análisis

Una vez identificado, clasificado y solicitado el evento, este tendrá que pasar por un proceso ágil de análisis realizado por Paulonia, en el cual se determinará la urgencia de atención basado en su categoría y nivel de gravedad. 

Este proceso de análisis y determinación de que evento será atendido puede ser realizado mediante dos estratégias
1. **Basada en la experiencia del revisor de Paulonia**: El revisor puede estimar la urgencia y costo de tiempo del evento al leer el reporte.
2. **Basado en pruebas o réplicas**: El revisor necesita iniciar con pequeñas pruebas o réplicas que pudo causar el evento, para determinar el costo de tiempo.
3. **Basado en el criterio del cliente**: Usted (el cliente) puede opinar, indicar y priorizar bajo supuestos, necesidades o experiencia, los eventos a atenderse con mayor urgencia.

Una vez determinada la urgencia y costo de tiempo, se deriva a un encargado de área el mismo día y hora de la aprobación de la resolución del evento. Estas áreas pueden incluir: a) diseño; b) desarrollo frontend; c) desarrollo backend o; c) administración de tiendas.  

> **¡Tenga cuidado!**: Este análisis puede llegar a tomar varias horas de su [BOLSA](../frequestions/#%C2%BFqu%C3%A9-es-una-bolsa), por lo que los eventos reportados en las últimas fechas del mes actual pueden no ser analizadas.

[¿Tiene preguntas?](../frequestions/#an%C3%A1lisis)

##### 3. Diseño y/o implementación
Si el reporte de un evento ha sido analizado y aprobado para su resolución, ¡en hora buena, tu evento pronto será resuelto!

Recuerde que existen varias áreas en Paulonia, y un evento a atender puede demandar la atención de una o todas ellas, y esto determinará que se extienda o contraiga el tiempo de entrega. Así mismo, recuerde que un evento a resolver puede desencadenar más eventos fortuitos, por lo que es de vital importancia que predisponga de tiempo para entablar una conversación con el encargado de resolver su evento.

> **¡Tenga cuidado!**: Un alto índice de eventos suelen demorar su entrega por falta de feedback del cliente.

[¿Tiene preguntas?](../frequestions/#dise%C3%B1o-yo-implementaci%C3%B3n)


##### 4. Validación, verificación y aceptación de pruebas
Cada área de Paulonia tiene un proceso de prueba y aceptación ante cambios de su aplicación. Una vez diseñada y/o implementada la solución de su evento, esta pasa por un proceso de pruebas, simulaciones y control de calidad asegurando que responde a la solicitud de mantenimiento inicial. 

Por ejemplo, en Paulonia Development ([Documento en progreso](https://paulonia.atlassian.net/browse/TOMENTOSA-1631)) se realiza un control de calidad de código, y desempeño de  su aplicación. En Paulonia Studio ([Documento en progreso](https://paulonia.atlassian.net/browse/TOMENTOSA-1632)) se asegura que la solución sea usable y corresponda a todo el branding de su aplicación y finalmente en [Paulonia Cloud](/{{site.handbooks_path}}/backend/procesos/mantenimiento) asegura la disponibilidad de su aplicación así como su escalabilidad y bienestar de servidores.

[¿Tiene preguntas?](../frequestions/#validaci%C3%B3n-verificaci%C3%B3n-y-aceptaci%C3%B3n-de-pruebas)

##### 5. Entrega y despliegue
¡Todo está listo!

+ Si los cambios demandan la generación de una nueva versión y APK, las horas destinadas a ello también se facturarán.
+ Si los cambios demandan la actualización en tiendas, se coordinará con el área de Administración de tiendas para la actualización de contenido multimedia de cada tienda. Así mismo este proceso se hará bajo los acuerdos especificados en ([Documento en progreso](https://paulonia.atlassian.net/browse/TOMENTOSA-1633)).

[¿Tiene preguntas?](../frequestions/#entrega-y-despliegue)
