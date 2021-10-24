---
title: Rol Silenciado
description:
published: true
date: Sun Oct 24 2021 12:21:48 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:21:48 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo le permitirá configurar el rol Silenciado.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso básico: ``VIEW_CHANNEL``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Pasos para crear el rol Silenciado

## **Paso 1**: Crea el rol Silenciado

Para crea el rol silenciado debes ejecutar el siguiente comando: <kbd>/core roles muted</kbd>.

**Ejemplo**: <kbd>/core roles muted</kbd>.

> Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL``, ``MANAGE_CHANNELS`` y ``MANAGE_ROLES``.
{.is-danger}

# Pasos para establecer el rol Silenciado

## **Paso 1**: Establecer el rol Silenciado

Para establecer el rol silenciado debes ejecutar el siguiente comando: <kbd>/core roles muted ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/core roles muted ``role:@Muted``</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/core roles reset</kbd>.

**Ejemplo**: <kbd>/core roles reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
