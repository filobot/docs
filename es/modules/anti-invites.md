---
title: Anti Invitaciones
description:
published: true
date: Mon Jun 14 2021 13:22:25 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:22:25 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá eliminar y advertir a los usuarios que envían invitaciones ajenas a su servidor o de los servidores permitidos.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso avanzado: ``MANAGE_MESSAGES``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS`` y ``MANAGE_MESSAGES``. **^1^**

- Si el usuario tiene el permiso ``ADMINISTRATOR``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_GUILD``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_MESSAGES``. **^2^**

- Si el usuario tiene el permiso ``BAN_MEMBERS``. **^2^**

- Si el usuario tiene el permiso ``KICK_MEMBERS``. **^2^**

- Si la posición de los roles de Filo es más baja que la de los roles del usuario. **^2^**

- Si la posición de los roles de Filo es igual que la de los roles del usuario. **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-invites enable</kbd>.

**Ejemplo**: <kbd>f!config anti-invites enable</kbd>.

> Este módulo se puede complementar con el módulo **[Auto Moderación](https://wiki.filobot.xyz/es/modules/auto-moderation)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-invites disable</kbd>.

**Ejemplo**: <kbd>f!config anti-invites disable</kbd>.

# Pasos para añadir un servidor a la lista de permitidos

## **Paso 1**: Añadir un servidor a la lista de permitidos

Para añadir un servidor a la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-invites allow add \<ID del servidor></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-invites allow add 123456789123456789</kbd>.

> Consulta este artículo del centro de soporte de Discord haciendo **[clic aquí](https://support.discord.com/hc/en-us/articles/206346498)**
{.is-info}

# Pasos para eliminar un servidor de la lista de permitidos

## **Paso 1**: Eliminar un servidor de la lista de permitidos

Para eliminar un servidor de la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-invites allow remove \<ID del servidor></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-invites allow remove 123456789123456789</kbd>.

> Consulta este artículo del centro de soporte de Discord haciendo **[clic aquí](https://support.discord.com/hc/en-us/articles/206346498)**
{.is-info}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config anti-invites reset \<Allow> (opcional)</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-invites reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
