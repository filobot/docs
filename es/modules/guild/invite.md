---
title: Invitación del Gremio
description:
published: true
date: Mon Jun 14 2021 13:23:06 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:23:06 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá establecer una invitación permanente del gremio.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``CREATE_INSTANT_INVITE``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/prefix)**.

# Pasos para crear la invitación en un canal

## **Paso 1**: Crear la invitación en un canal

Para crear la invitación en un canal debes ejecutar el siguiente comando: <kbd>f!config guild invite create \<#Canal/ID del Canal></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config guild invite create #general</kbd>.

> Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``CREATE_INSTANT_INVITE``.
{.is-danger}

# Pasos para configurar una invitación existente desde un canal

## **Paso 1**: Establecer una invitación existente de un canal

Para establecer una invitación existente de un canal debes ejecutar el siguiente comando: <kbd>f!config guild invite set \<URL de la Invitación/Código de la Invitación></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config guild invite set https://discord.gg/xHhBWhT</kbd>.

> La invitación que establezcas debe ser del mismo gremio.
{.is-danger}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config guild reset \<Invite></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config guild reset invite</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
