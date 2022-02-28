---
title: Recien llegados

pagination:
  previous:
    link: ../herramientas
    name: Herramientas
---

En esta sección, responderemos algunas preguntas comunes que puede tener como nuevo miembro del equipo de desarrollo front-end.

**¿No puedo iniciar sesión usando Facebook o Google en un aplicativo, como lo soluciono?**

En el caso de Google, se requiere que autentifiques usando tu SHA1 o SHA256, consulta con el project lead de backend, en caso no estuviera agregado generalo y enviaselo para que sea agregado.

Para generar tu clave SHA en Linux usa el siguiente comando:

```console
keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android
```

para Windows sigue los siguientes pasos:

1.- Ingresa el comando, usando como clave android:

```console
keytool -exportcert -v -alias androiddebugkey -keystore %USERPROFILE%/.android/debug.keystore
```

2.- Genera un SHA legible con el comando:

```console
keytool -list -v -alias androiddebugkey -keystore %USERPROFILE%/.android/debug.keystore
```

Para el caso de Facebook, consulta con el project lead de backend, puede que necesites permisos como desarrollador de facebook o el proyecto aún no esté configurado para iniciar sesión con facebook.

**¿Tengo algunas preguntas sobre una interfaz que tengo que implementar, quien puede resolver mis dudas?**

Si el diseño fue hecho por Paulonia Studio, pregunta directamente en el canal de Slack de diseño del proyecto o deja un comentario en Figma etiquetando al encargado de diseño.

**¿No encuentro la funcionalidad en backend para crear la lógica de una interfaz, con quien consulto esto?**

En caso el backend fuera desarrollado por Paulonia, pregunta por ello en el canal de slack de desarrollo de otro modo consulta con el team lead.

**¿Encontré incongruencias en el diseño y el backend, que debo hacer?**

Coméntalo en el canal de diseño de Slack de ser algo simple, en caso sea algo más complejo pide una reunión con los project leads de diseño y backend para solucionar los problemas.

**¿Qué hago si no puedo cumplir con una tarea asignada por dependencias en diseño y/o backend?**

Lo primero que debes hacer es contactar a los responsables de esas dependencias por slack (en el canal del proyecto) o en jira (por comentarios de la tarea), etiquetando al encargado del proyecto. En caso no se pudiera completar la tarea para el sprint, comunicar al encargado de proyecto.
