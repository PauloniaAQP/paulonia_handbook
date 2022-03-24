---
title: Vault para Administradores
pagination:
    previous:
        link: ../vault
        name: Vault
---

Si no eres team lead o administrador de Vault, entonces no es necesario que leas este documento. Los team lead y administradores son los encargados de crear secretos y compartirlos en Vault. Además pueden crear y eliminar usuarios.

Para lo anterior mencionado, existen video tutoriales que explican estos procesos. Para obtener acceso a ellos, comuníquese con el encargado de seguridad: {{site.security_leader_name}}

## Recomendaciones

- Tener en cuenta las [recomendaciones para usuarios](../vault#recomendaciones)
- Cuando crees una cuenta, crearla con correo y contraseña. Usar el correo principal de la empresa y usar un [generador de contraseñas](https://www.lastpass.com/es/features/password-generator) para mayor seguridad (de 32 caracteres como recomendación).
- Evitar colocar datos críticos en los títulos de los secretos.
- Si un secreto cambia, crear una nueva versión del secreto.
- Borrar secretos sólo si es estrictamente necesario (la cuenta es eliminada o ya no se usa).
- Si vas a compartir un secreto, asegúrate de que sea indispensable para el trabajo del usuario (lo va usar muchas veces). Si, por el contrario, lo va a usar sólo una vez, es mejor que tú como team lead hagas lo que el usuario iba a hacer en esa cuenta y no compartir el secreto.
- Los administradores también pueden hacer uso de su cuenta como usuario.
