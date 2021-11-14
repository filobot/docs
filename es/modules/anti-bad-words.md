---
title: Anti Malas Palabras
description:
published: true
date: Sun Nov 14 2021 15:12:33 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Nov 14 2021 15:12:33 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo sancionará a aquellos usuarios que envíen mensajes con palabras malas.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``MANAGE_MESSAGES``.

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

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-bad-words enable</kbd>.

**Ejemplo**: <kbd>/anti-bad-words enable</kbd>.

> Este módulo se puede complementar con el módulo **[Auto Moderación](https://wiki.filobot.xyz/es/modules/auto-moderation)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-bad-words disable</kbd>.

**Ejemplo**: <kbd>/anti-bad-words disable</kbd>.

# Pasos para banear una mala palabra

## **Paso 1**: Banear una mala palabra

Para banear una mala palabra debes ejecutar el siguiente comando: <kbd>/anti-bad-words word ``action:Add`` ``word:<Mala palabra>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-bad-words word ``action:Add`` ``word:Kawaii``</kbd>.

# Pasos para desbanear una mala palabra

## **Paso 1**: Desbanear una mala palabra

Para desbanear una mala palabra debes ejecutar el siguiente comando: <kbd>/anti-bad-words word ``action:Remove`` ``word:<Mala palabra>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-bad-words word ``action:Remove`` ``word:Kawaii``</kbd>.

# Pasos para activar el filtro agresivo

## **Paso 1**:  Activar el filtro agresivo

Para activar el filtro agresivo debes ejecutar el siguiente comando: <kbd>/anti-bad-words aggresive-filter ``action:Enable``</kbd>.

**Ejemplo**: <kbd>/anti-bad-words aggresive-filter ``action:Enable``</kbd>.

> Activar el filtro agresivo puede ocasionar una mayor cantidad de falsos positivos.
{.is-warning}

# Pasos para desactivar el filtro agresivo

## **Paso 1**:  Desactivar el filtro agresivo

Para desactivar el filtro agresivo debes ejecutar el siguiente comando: <kbd>/anti-bad-words aggresive-filter ``action:Disable``</kbd>.

**Ejemplo**: <kbd>/anti-bad-words aggresive-filter ``action:Disable``</kbd>.

# Pasos para establecer una sanción

## **Paso 1**: Establecer una sanción

Para establecer una sanción debes ejecutar el siguiente comando: <kbd>/anti-bad-words action ``action:<Acción>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver una lista completa de las acciones que admite Filo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/actions-list)**.
{.is-info}

**Ejemplo**: <kbd>/anti-bad-words action ``action:Temporarily mute the user`` ``time:1h``</kbd>.

# Steps to add a channel to the allowed list

## **Paso 1**: Add a channel to the allowed list

Para add a channel to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-bad-words channel ``action:Add`` ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-bad-words channel ``action:Add`` ``channel:#spam-allowed``</kbd>.

> Si añades un canal a la lista de permitidos, este módulo no funcionará en dicho canal.
{.is-warning}

# Steps to remove a channel to the allowed list

## **Paso 1**: Remove a channel to the allowed list

Para remove a channel to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-bad-words channel ``action:Remove`` ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-bad-words channel ``action:Remove`` ``channel:#general``</kbd>.

> Si eliminas un canal de la lista de permitidos, este módulo funcionará en dicho canal.
{.is-warning}

# Steps to add a role to the allowed list

## **Paso 1**: Add a role to the allowed list

Para add a role to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-bad-words role ``action:Add`` ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-bad-words role ``action:Add`` ``role:@Moderators``</kbd>.

> Si añades un rol a la lista de permitidos, cualquier que tenga este rol estará exento del funcionamiento de este módulo.
{.is-warning}

# Steps to remove a role to the allowed list

## **Paso 1**: Remove a role to the allowed list

Para remove a role to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-bad-words role ``action:Remove`` ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-bad-words role ``action:Remove`` ``role:@Moderators``</kbd>.

> Si eliminas un rol de la lista de permitidos, cualquier que tenga este rol ya no estará exento del funcionamiento de este módulo.
{.is-warning}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/anti-bad-words reset</kbd>.

**Ejemplo**: <kbd>/anti-bad-words reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
