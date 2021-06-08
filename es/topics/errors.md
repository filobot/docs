---
title: Errores Comunes
description:
published: true
date: Thu Jun 03 2021 14:35:05 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Jun 03 2021 14:35:05 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

Aquí encontrarás documentados todos los errores de Filo junto con sus posibles soluciones.

# Algo salió mal al intentar ejecutar esa acción

## Sin ID de Seguimiento

Este es un error que se otorgará siempre que algo falle de tu parte, por ejemplo, la falta de permisos de Filo puede hacer que se envíe este error.

**Solución**: Verifica que los permisos de Filo estén colocados correctamente y que la jerarquía de roles sea adecuada para cada situación.

## Con ID de Seguimiento

Este error ocurre cuando algo no funciona de nuestro lado o la API de Discord no devuelve respuestas satisfactorias.

**Solución**: Informa al equipo de desarrollo de Filo y espere una solución al problema.

> Es posible que no haya una solución definitiva, dependiendo de las causas del error.
{.is-warning}

# El módulo ``EJEMPLO`` está deshabilitado

Este es un error que se envía cuando intenta usar un comando o función que solo está disponible si tiene habilitado el módulo necesario.

**Solución**: Habilite el módulo necesario que se especifica en el mensaje de error.

# El módulo ``EJEMPLO`` no funciona aunque está habilitado

Este error se da cuando algo en la configuración del módulo no funciona como debería; Las causas podrían ser: falta de permisos necesarios, problemas en la jerarquía de roles, el canal necesario dejó de existir, malformación de la información enviada por el módulo, el webhook dejó de existir, etc.

**Solución**: Compruebe que la configuración sea correcta, los permisos sean correctos y si la jerarquía es correcta.

> Si no puedes determinar el problema por el que el módulo no funciona, **[contáctanos](https://filobot.xyz/discord)**.
{.is-warning}

# No tienes permisos para ejecutar el comando ``EJEMPLO``

Este error se da cuando intentas ejecutar un comando al que no deberías tener acceso, por ejemplo, un comando de moderación sin ser moderador del servidor.

**Solución**: Solicite a un superior de su servidor que establezca los permisos necesarios para la ejecución del comando en cuestión.

> Si no puedes determinar qué permiso es necesario, **[contáctanos](https://filobot.xyz/discord)**.
{.is-warning}

# No tienes permisos para ejecutar el comando ``EJEMPLO`` con ``DiscordUser#0000``

Este error se da cuando intentas ejecutar un comando con un usuario que tiene una jerarquía de roles más alta que la tuya.

**Solución**: Solicite a un superior que revise su jerarquía de roles y la del usuario con el que desea ejecutar el comando.

# Se produjo un error al intentar comunicarse con la API

Este error se da cuando el comando o módulo depende de una API de terceros y no devuelve una respuesta satisfactoria.

**Solución**: Intente probar la acción tomada más tarde, si continúa igual, **[contáctanos](https://filobot.xyz/discord)**.

# Filo no responde a ningún comando

Este error ocurre cuando la API de Discord no envía la información necesaria sobre los permisos de Filo en el canal de ejecución de comandos.

**Solución**: Vuelve a intentarlo más tarde y, si el problema persiste, **[contáctanos](https://filobot.xyz/discord)**.

> Actualmente no hay una solución definitiva a este error.
{.is-danger}
