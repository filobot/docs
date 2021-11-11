---
title: Auto Moderación
description:
published: true
date: Thu Nov 11 2021 17:05:42 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Nov 11 2021 17:05:42 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá sancionar automáticamente a aquellos usuarios que tengan repetidamente un comportamiento incorrecto.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``MANAGE_MESSAGES``, ``MANAGE_ROLES``, ``KICK_MEMBERS`` y``BAN_MEMBERS`` (si aplica).

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES`` y ``EMBED_LINKS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``MANAGE_MESSAGES``. **^1^**

- Si el usuario tiene el permiso ``ADMINISTRATOR``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_GUILD``. **^2^**

- Si el usuario tiene el permiso ``EVADE_SANCTIONS``. **^2^**

- Si la posición de los roles de Filo es más baja que la de los roles del usuario. **^2^**

- Si la posición de los roles de Filo es igual que la de los roles del usuario. **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/auto-moderation enable</kbd>.

**Ejemplo**: <kbd>/auto-moderation enable</kbd>.

> Este módulo se puede complementar con el módulo **[Anti Evasión](https://wiki.filobot.xyz/es/modules/anti-evasion)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/auto-moderation disable</kbd>.

**Ejemplo**: <kbd>/auto-moderation disable</kbd>.

# Pasos para añadir un nivel

## **Paso 1**: Añadir un nivel

Para añadir un nivel debes ejecutar el siguiente comando: <kbd>/auto-moderation add ``warnings:<Advertencias>`` ``action:Acción``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver una lista completa de las acciones que admite Filo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/actions-list)**.
{.is-info}

**Ejemplo**: <kbd>/auto-moderation add ``warnings:3`` ``action:Kick the user``</kbd>.

# Pasos para eliminar un nivel

## **Paso 1**: Eliminar un nivel

Para eliminar un nivel debes ejecutar el siguiente comando: <kbd>/auto-moderation remove ``level:<Nivel>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/auto-moderation remove ``level:1``</kbd>.

# Pasos para establecer la información de un nivel

## **Paso 1**: Establecer la información de un nivel

Para establecer la información de un nivel debes ejecutar el siguiente comando: <kbd>/auto-moderation set ``level:<Nivel>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/auto-moderation set ``level:1`` ``warnings: 3`` ``action:Kick the user``</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/auto-moderation reset</kbd>.

**Ejemplo**: <kbd>/auto-moderation reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
