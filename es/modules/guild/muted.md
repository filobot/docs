---
title: Rol Silenciado
description:
published: true
date: Thu Jun 03 2021 14:35:41 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Jun 03 2021 14:35:41 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo le permitirá configurar el rol Silenciado.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_ROLES``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](es/modules/prefix)**.

# Pasos para crear el rol Silenciado

## **Paso 1**: Crea el rol Silenciado

Para crea el rol silenciado debes ejecutar el siguiente comando: <kbd>f!config guild role muted create</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config guild role muted create</kbd>.

# Pasos para establecer el rol Silenciado

## **Paso 1**: Establecer el rol Silenciado

Para establecer el rol silenciado debes ejecutar el siguiente comando: <kbd>f!config guild role muted set \<@Rol/ID del Rol></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config guild role muted set @Muted</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config guild reset \<Muted></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config guild reset muted</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
