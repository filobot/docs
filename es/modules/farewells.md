---
title: Despedidas
description:
published: true
date: Sun Oct 24 2021 14:37:45 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:37:45 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá enviar un mensaje de despedida a los antiguos miembros del servidor.

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

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/farewells enable</kbd>.

**Ejemplo**: <kbd>/farewells enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/farewells disable</kbd>.

**Ejemplo**: <kbd>/farewells disable</kbd>.

# Pasos para establecer el canal de despedidas

## **Paso 1**: Establecer el canal de despedidas

Para establecer el canal de despedidas debes ejecutar el siguiente comando: <kbd>/farewells channel ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/farewells channel ``channel:#farewells``</kbd>.

# Pasos para establecer el mensaje de despedida

## **Paso 1**: Establecer el mensaje de despedida

Para establecer el canal de despedidas debes ejecutar el siguiente comando: <kbd>/farewells message</kbd>.

> Dispondrás de **1 minuto** para realizar esta acción.
{.is-warning}

**Ejemplo**: <kbd>/farewells message</kbd>.

> Puedes establecer variables en el mensaje de despedida. Puedes encontrar una lista de todas las variables haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/farewells/variables)**.
{.is-info}

> ```md
> Goodbye **{{user.tag}}**! 😧
> We look forward to your return in **{{server.name}}**. 👋
> ```
> **Código del mensaje**
>
> Goodbye **DiscordUser#0000**! 😧
> We look forward to your return in **Awesome Server**. 👋
>
> **Resultado del mensaje**

# Pasos para establecer el tipo de mensaje

## **Paso 1**: Establecer el tipo de mensaje

Para establecer el tipo de mensaje debes ejecutar el siguiente comando: <kbd>/farewells type ``type:<Normal/Embed>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/farewells type ``type:Embed``</kbd>.

> Si los usuarios han desactivado la visualización de embeds, no verán el mensaje de despedida.
{.is-danger}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/farewells reset</kbd>.

**Ejemplo**: <kbd>/farewells reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
