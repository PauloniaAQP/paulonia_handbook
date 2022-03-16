---
title: Seguridad en Paulonia
pagination:
    next: 
        link: ./vault
        name: Vault
---

En las empresas de Software como Paulonia, en donde la gran mayoría de documentos, conversaciones y trabajo se hacen de forma virtual, la seguridad informática cobra una mayor relevancia. En toda esta sección se va a hablar sobre herramientas, procesos y lineamientos que toda persona en Paulonia debe conocer para evitar cualquier amenaza que pueda atentar contra la empresa.

## Sobre nuestra computadora

Lo primero que siempre tenemos que tener segura es nuestra herramienta principal: nuestra laptop o computadora con la cual trabajamos. Es el punto de entrada a mucha información: cuentas, documentos, código, etc. Por esta razón debemos de tener en cuenta los siguientes puntos:

- Es necesario trabajar en una computadora segura en una red segura.
- Nunca trabajar en redes públicas o en redes cuyo propietario no sea de confianza.
- La computadora que uses debe ser de tu propiedad y evitar que otras personas la usen.
- Si la computadora que usas no es de tu propiedad, entonces asegúrate de que el propietario sea de confianza y al momento de trabajar evitar usar cuentas críticas o información que pueda ser comprometida.
- Si tu computadora es usada también por otra persona, entonces esa persona debe tener un perfil (sesión) diferente.
- En tu computadora, debes tener un perfil (sesión) para poder trabajar. Este perfil debe tener una contraseña para iniciar sesión y ninguna otra persona debe saber la contraseña ni poder entrar a tu sesión de trabajo.
- Si vas a cambiar de computadora y dejar de usar la anterior, cierra todas las sesiones abiertas y elimina o exporta documentos y código que tengas en dicha computadora.
- En caso de robo, avisar a tu team lead para hacer una rotación de las credenciales que se te proporcionaron y se usaron en la computadora.

## Sobre nuestro celular

En muchos casos nuestros celular se convierte también en una de nuestras herramientas de trabajo: para probar aplicaciones o poder ver y administrar cuentas desde ahí. Si usas tu celular para lo anterior, entonces debes tener en cuenta lo siguiente:

- El celular no debe ser usado por ninguna otra persona.
- Nunca usar tu celular en redes públicas o en redes cuyo propietario no sea de confianza.
- Evitar usar cuentas críticas o información que pueda ser comprometida.
- Si vas a cambiar de celular, cierra todas las sesiones abiertas. Además exporta las credenciales 2FA creadas en la [siguiente sección](#sobre-nuestras-cuentas).
- En caso de robo, avisar a tu team lead para hacer una rotación de las credenciales que se te proporcionaron y se usaron en el celular.


## Sobre nuestras cuentas

Dependiendo del área en que se trabaje, se van a usar diferentes cuentas. Dependiendo de su importancia, cada team lead se va a encargar de dar los lineamientos adecuados. Pero hay cuentas que todos dentro de Paulonia usamos: Correo de Google, Slack, Github. Para estas cuentas se debe tener en cuenta lo siguiente:

- Estas cuentas deben de tener activado la [Autenticación de dos factores (2FA)](https://www.onespan.com/es/topics/autenticacion-de-dos-factores). Puede utilizar cualquier aplicación para administrar el 2FA, pero acá le recomendamos usar el [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=es_PE&gl=US)
- Si eres desarrollador y eres activo en Github, es necesario que configures llaves de acceso a Github. Ya que al activar el 2FA, ahora es necesario hacer todas las operaciones mediante SSH. Para configurar esto, puede seguir [este tutorial](https://docs.github.com/es/authentication/connecting-to-github-with-ssh).
