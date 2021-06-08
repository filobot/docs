---
title: Bienvenidas
description:
published: true
date: Mon Jun 07 2021 16:01:56 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 07 2021 16:01:56 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá enviar un mensaje de bienvenida a los nuevos miembros del servidor.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``USE_EXTERNAL_EMOJIS``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``USE_EXTERNAL_EMOJIS``. **^1^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config welcomes enable</kbd>.

**Ejemplo**: <kbd>f!config welcomes enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config welcomes disable</kbd>.

**Ejemplo**: <kbd>f!config welcomes disable</kbd>.

# Pasos para establecer el canal de bienvenidas

## **Paso 1**: Establecer el canal de bienvenidas

Para establecer el canal de bienvenidas debes ejecutar el siguiente comando: <kbd>f!config welcomes set channel \<#Canal/ID del Canal></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config welcomes set channel #welcomes</kbd>.

# Pasos para establecer el mensaje de bienvenida

## **Paso 1**: Establecer el mensaje de bienvenida

Para establecer el canal de bienvenidas debes ejecutar el siguiente comando: <kbd>f!config welcomes set message \<Mensaje></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puedes establecer variables en el mensaje de bienvenida. Puedes encontrar una lista de todas las variables haciendo **[clic aquí](/es/modules/welcomes/variables)**.
{.is-info}

**Ejemplo**: <kbd>f!config welcomes set message Goodbye {user.tag}!</kbd>.

> ```md
> Welcome {user} to the server **{server}**! 😉
> Thanks to you we are **{server.members}** total members! 🎉
> ```
> **Código del mensaje**
>
> Welcome @DiscordUser to the server **Awesome Server**! 😉
> Thanks to you we are **123,456** total members! 🎉
>
> **Resultado del mensaje**

# Pasos para establecer el tipo de mensaje

## **Paso 1**: Establecer el tipo de mensaje

Para establecer el tipo de mensaje debes ejecutar el siguiente comando: <kbd>f!config welcomes set type \<Normal/Embed></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config welcomes set type embed</kbd>.

> Si los usuarios han desactivado la visualización de embeds, no verán el mensaje de bienvenida.
{.is-danger}

## **Paso 12**: Establecer el color del embed (opcional)

Actualmente, Filo no tiene un comando para establecer el color del embed, sin embargo, hay una forma de cambiarlo. Cuando Filo va a enviar el mensaje de bienvenida a través de un embed, obtiene la información del rol más alto que ella tiene asignado. Si dicho rol tiene un color personalizado, el color del embed será el mismo que dicho rol.

> Consulta este artículo del centro de soporte de Discord haciendo **[clic aquí](https://support.discord.com/hc/en-us/articles/214836687)**
{.is-info}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config welcomes reset \<Channel/Message/Type/Role> (opcional)</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config welcomes reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
