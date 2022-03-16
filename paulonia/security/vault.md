---
title: Vault
pagination:
    next:
        link: ../vault_admins
        name: Vault para admins
    previous:
        link: ../
        name: Seguridad
---

[Vault](https://www.vaultproject.io/) es un sistema de almacenamiento y acceso a secretos. Un secreto es cualquier contraseña, credenciales, accesos, certificados o texto que necesite guardarse bajo llave. Lo que nos permite Vault es guardar de forma segura secretos para que no se lleguen a perder (porque alguien se va de la empresa o simplemente se olvida la contraseña). Además nos permite crear políticas para dar acceso a usuarios a ciertos secretos.

## Login

Ya que este documento es público y por temas de seguridad, no vamos a colocar el link de nuestro Vault aquí. Puedes pedir el link a tu team lead. Evitar compartir el link con cualquier otra persona.
Para poder ingresar a nuestro Vault necesitamos generar un token de acceso desde nuestra cuenta de Github. Para este proceso tenemos un video tutorial que puedes encontrar en esta [carpeta de Loom](https://www.loom.com/team-videos/Vault), con el nombre `1. Vault - Iniciar sesión`. Pide a tu team lead que te de acceso a dicha carpeta o a los videos.

## Uso

Una vez dentro, Vault utiliza una estructura parecida a carpetas, donde dentro pueden haber otras carpetas o secretos. 
La carpeta principal que verás se llama `paulonia`, dentro podrás encontrar diferentes carpetas, entra a la que tiene tu nombre de usuario de github. Sólo podras ver los secretos que se encuentren dentro de esta carpeta. Tu team lead o un administrador son los encargados de compartir secretos a tu carpeta de Vault. Por lo tanto, si necesitas acceso a cualquier cuenta de la empresa (no personal), pídesela a tu team lead para que la agregue a tu carpeta. En la carpeta de Loom podrás encontrar un pequeño video de esto bajo el nombre: `2. Vault - Cuenta de usuario`.

## Recomendaciones

- No compartir el link de nuestro Vault ni los videos explicativos con nadie que no esté dentro de la empresa.
- El token generado en Github debe tener una expiración menor o igual a 30 días.
- Dentro de Vault, usar los botones de copiar sin revelar los secretos. Revelarlos cuando sea necesario leerlos.
- Evitar abrir el Vault cuando tengas una persona cerca.
- Una vez terminado de usar el Vault, cerrarlo.
