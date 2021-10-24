---
title: Rol de Bienvenida
description:
published: true
date: Sun Oct 24 2021 14:30:22 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:30:22 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá otorgar un rol de bienvenida a los nuevos miembros.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso avanzado: ``MANAGE_ROLES``.

- Filo requiere el siguiente permiso básico: ``VIEW_CHANNEL``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.
- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene el permiso ``MANAGE_ROLES``. **^1^**

- Si la posición de los roles de Filo es más baja que la de los roles del usuario. **^2^**

- Si la posición de los roles de Filo es igual que la de los roles del usuario. **^2^**

- Si la posición de los roles de Filo es más baja que la del rol de bienvenida. **^2^**

- Si la posición de los roles de Filo es igual que la del rol de bienvenida. **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/welcomes enable ``module:Welcome role``</kbd>.

**Ejemplo**: <kbd>/welcomes enable ``module:Welcome role``</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>welcomes disable ``module:Welcome role``</kbd>.

**Ejemplo**: <kbd>/welcomes disable ``module:Welcome role``</kbd>.

# Pasos para establecer el rol de bienvenida

## **Paso 1**: Establecer el rol de bienvenida

Para establecer el rol de bienvenida debes ejecutar el siguiente comando: <kbd>/welcomes role ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/welcomes role ``role:@Newbies``</kbd>.

> Los roles de Filo deben ser más altos que el rol seleccionado, además, el rol seleccionado no puede ser administrado por una integración.
{.is-danger}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/welcomes reset</kbd>.

**Ejemplo**: <kbd>/welcomes reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
