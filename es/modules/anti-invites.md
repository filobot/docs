---
title: Anti Invitaciones
description:
published: true
date: Thu Nov 11 2021 16:31:15 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Nov 11 2021 16:31:15 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá eliminar y advertir a los usuarios que envían invitaciones ajenas a su servidor o de los servidores permitidos.

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

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-invites enable</kbd>.

**Ejemplo**: <kbd>/anti-invites enable</kbd>.

> Este módulo se puede complementar con el módulo **[Auto Moderación](https://wiki.filobot.xyz/es/modules/auto-moderation)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-invites disable</kbd>.

**Ejemplo**: <kbd>/anti-invites disable</kbd>.

# Pasos para establecer una sanción

## **Paso 1**: Establecer una sanción

Para establecer una sanción debes ejecutar el siguiente comando: <kbd>/anti-invites action ``action:<Acción>``</kbd>.

**Ejemplo**: <kbd>/anti-invites action ``action:Delete the message``</kbd>.

# Pasos para habilitar el ignorar el servidor de Filo

## **Paso 1**: Ignorar el servidor de Filo

Para ignorar el servidor de filo debes ejecutar el siguiente comando: <kbd>/anti-invites filo ``action:Enable``</kbd>.

**Ejemplo**: <kbd>/anti-invites filo ``action:Enable``</kbd>.

# Pasos para no ignorar el servidor de Filo

## **Paso 1**: No ignorar el servidor de Filo

Para no ignorar el servidor de filo debes ejecutar el siguiente comando: <kbd>/anti-invites filo ``action:Disable``</kbd>.

**Ejemplo**: <kbd>/anti-invites filo ``action:Disable``</kbd>.

# Pasos para ignorar los servidores oficiales de Discord

## **Paso 1**: Ignorar los servidores oficiales de Discord

Para ignorar los servidores oficiales de discord debes ejecutar el siguiente comando: <kbd>/anti-invites discord ``action:Enable``</kbd>.

**Ejemplo**: <kbd>/anti-invites discord ``action:Enable``</kbd>.

# Pasos para no ignorar los servidores oficiales de Discord

## **Paso 1**: No ignorar los servidores oficiales de Discord

Para no ignorar los servidores oficiales de discord debes ejecutar el siguiente comando: <kbd>/anti-invites discord ``action:Disable``</kbd>.

**Ejemplo**: <kbd>/anti-invites discord ``action:Disable``</kbd>.

# Pasos para añadir un servidor a la lista de permitidos

## **Paso 1**: Añadir un servidor a la lista de permitidos

Para añadir un servidor a la lista de permitidos debes ejecutar el siguiente comando: <kbd>/anti-invites guild ``action:Add`` ``guild:<ID del servidor>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-invites guild ``action:Add`` ``guild:123456789123456789``</kbd>.

> Consulta este artículo del centro de soporte de Discord haciendo **[clic aquí](https://support.discord.com/hc/en-us/articles/206346498)**
{.is-info}

# Pasos para eliminar un servidor de la lista de permitidos

## **Paso 1**: Eliminar un servidor de la lista de permitidos

Para eliminar un servidor de la lista de permitidos debes ejecutar el siguiente comando: <kbd>/anti-invites guild ``action:Remove`` ``guild:<ID del servidor>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-invites guild ``action:Remove`` ``guild:123456789123456789``</kbd>.

> Consulta este artículo del centro de soporte de Discord haciendo **[clic aquí](https://support.discord.com/hc/en-us/articles/206346498)**
{.is-info}

# Steps to add a channel to the allowed list

## **Paso 1**: Add a channel to the allowed list

Para add a channel to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-invites channel ``action:Add`` ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-invites channel ``action:Add`` ``channel:#spam-allowed``</kbd>.

> Si añades un canal a la lista de permitidos, este módulo no funcionará en dicho canal.
{.is-warning}

# Steps to remove a channel to the allowed list

## **Paso 1**: Remove a channel to the allowed list

Para remove a channel to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-invites channel ``action:Remove`` ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-invites channel ``action:Remove`` ``channel:#general``</kbd>.

> Si eliminas un canal de la lista de permitidos, este módulo funcionará en dicho canal.
{.is-warning}

# Steps to add a channel to the allowed list

## **Paso 1**: Add a role to the allowed list

Para add a role to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-invites role ``action:Add`` ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-invites role ``action:Add`` ``role:@Moderators``</kbd>.

> Si añades un rol a la lista de permitidos, cualquier que tenga este rol estará exento del funcionamiento de este módulo.
{.is-warning}

# Steps to remove a role to the allowed list

## **Paso 1**: Remove a role to the allowed list

Para remove a role to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-invites role ``action:Remove`` ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-invites role ``action:Remove`` ``role:@Moderators``</kbd>.

> Si eliminas un rol de la lista de permitidos, cualquier que tenga este rol ya no estará exento del funcionamiento de este módulo.
{.is-warning}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/anti-invites reset</kbd>.

**Ejemplo**: <kbd>/anti-invites reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
