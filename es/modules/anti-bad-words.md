---
title: Anti Malas Palabras
description:
published: true
date: Mon Jun 14 2021 13:18:44 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:18:44 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá eliminar y advertir a los usuarios que envían malas palabras.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso avanzado: ``MANAGE_MESSAGES``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](es/modules/prefix)**.

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

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-bad-words enable</kbd>.

**Ejemplo**: <kbd>f!config anti-bad-words enable</kbd>.

> Este módulo se puede complementar con el módulo **[Auto Moderación](https://wiki.filobot.xyz/es/modules/auto-moderation)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-bad-words disable</kbd>.

**Ejemplo**: <kbd>f!config anti-bad-words disable</kbd>.

# Pasos para banear una mala palabra

## **Paso 1**: Banear una mala palabra

Para banear una mala palabra debes ejecutar el siguiente comando: <kbd>f!config anti-bad-words ban \<Mala palabra></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-bad-words ban Kawaii</kbd>.

# Pasos para desbanear una mala palabra

## **Paso 1**: Desbanear una mala palabra

Para desbanear una mala palabra debes ejecutar el siguiente comando: <kbd>f!config anti-bad-words unban \<Mala palabra></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-bad-words unban Kawaii</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config anti-bad-words reset \<List> (opcional)</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-bad-words reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
