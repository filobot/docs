---
title: Bienvenidas
description:
published: true
date: Sun Oct 24 2021 13:38:06 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 13:38:06 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá enviar un mensaje de bienvenida a los nuevos miembros del servidor.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL``, ``SEND_MESSAGES`` y ``EMBED_LINKS``.

- Filo requiere el siguiente permiso básico: ``VIEW_CHANNEL``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES`` y ``EMBED_LINKS``. **^1^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/welcomes enable ``module:Welcome message``</kbd>.

**Ejemplo**: <kbd>/welcomes enable ``module:Welcome message``</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/welcomes disable ``module:Welcome message``</kbd>.

**Ejemplo**: <kbd>/welcomes disable ``module:Welcome message``</kbd>.

# Pasos para establecer el canal de bienvenidas

## **Paso 1**: Establecer el canal de bienvenidas

Para establecer el canal de bienvenidas debes ejecutar el siguiente comando: <kbd>/welcomes channel ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/welcomes channel ``channel:#welcomes``</kbd>.

# Pasos para establecer el mensaje de bienvenida

## **Paso 1**: Establecer el mensaje de bienvenida

Para establecer el canal de bienvenidas debes ejecutar el siguiente comando: <kbd>/welcomes message</kbd>.

> Dispondrás de **1 minuto** para realizar esta acción..
{.is-warning}

**Ejemplo**: <kbd>/welcomes message</kbd>.

> Puedes establecer variables en el mensaje de bienvenida. Puedes encontrar una lista de todas las variables haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/welcomes/variables)**.
{.is-info}

> ```md
> Welcome {{@user}} to the server **{{server.name}}**! 😉
> Thanks to you we are **{{server.members}}** total members! 🎉
> ```
> **Código del mensaje**
>
> Welcome @DiscordUser to the server **Awesome Server**! 😉
> Thanks to you we are **123,456** total members! 🎉
>
> **Resultado del mensaje**

# Pasos para establecer el tipo de mensaje

## **Paso 1**: Establecer el tipo de mensaje

Para establecer el tipo de mensaje debes ejecutar el siguiente comando: <kbd>/welcomes type ``type:<Normal/Embed>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/welcomes type ``type:Embed``</kbd>.

> Si los usuarios han desactivado la visualización de embeds, no verán el mensaje de bienvenida.
{.is-danger}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/welcomes reset</kbd>.

**Ejemplo**: <kbd>/welcomes reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
