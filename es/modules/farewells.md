---
title: Despedidas
description:
published: true
date: Mon Jun 14 2021 13:21:38 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:21:38 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá enviar un mensaje de despedida a los antiguos miembros del servidor.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``USE_EXTERNAL_EMOJIS``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``USE_EXTERNAL_EMOJIS``. **^1^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config farewells enable</kbd>.

**Ejemplo**: <kbd>f!config farewells enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config farewells disable</kbd>.

**Ejemplo**: <kbd>f!config farewells disable</kbd>.

# Pasos para establecer el canal de despedidas

## **Paso 1**: Establecer el canal de despedidas

Para establecer el canal de despedidas debes ejecutar el siguiente comando: <kbd>f!config farewells set channel \<#Canal/ID del Canal></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config farewells set channel #farewells</kbd>.

# Pasos para establecer el mensaje de despedida

## **Paso 1**: Establecer el mensaje de despedida

Para establecer el canal de despedidas debes ejecutar el siguiente comando: <kbd>f!config farewells set message \<Mensaje></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puedes establecer variables en el mensaje de despedida. Puedes encontrar una lista de todas las variables haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/farewells/variables)**.
{.is-info}

**Ejemplo**: <kbd>f!config farewells set message Goodbye {user.tag}!</kbd>.

> ```md
> Goodbye **{user.tag}**! 😧
> We look forward to your return in **{server}**. 👋
> ```
> **Código del mensaje**
>
> Goodbye **DiscordUser#0000**! 😧
> We look forward to your return in **Awesome Server**. 👋
>
> **Resultado del mensaje**

# Pasos para establecer el tipo de mensaje

## **Paso 1**: Establecer el tipo de mensaje

Para establecer el tipo de mensaje debes ejecutar el siguiente comando: <kbd>f!config farewells set type \<Normal/Embed></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config farewells set type embed</kbd>.

> Si los usuarios han desactivado la visualización de embeds, no verán el mensaje de despedida.
{.is-danger}

## **Paso 12**: Establecer el color del embed (opcional)

Actualmente, Filo no tiene un comando para establecer el color del embed, sin embargo, hay una forma de cambiarlo. Cuando Filo va a enviar el mensaje de despedida a través de un embed, obtiene la información del rol más alto que ella tiene asignado. Si dicho rol tiene un color personalizado, el color del embed será el mismo que dicho rol.

> Consulta este artículo del centro de soporte de Discord haciendo **[clic aquí](https://support.discord.com/hc/en-us/articles/214836687)**
{.is-info}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config farewells reset \<Channel/Message/Type> (opcional)</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config farewells reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
