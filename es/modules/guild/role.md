---
title: Configurar un Rol
description:
published: true
date: Sun Oct 24 2021 12:15:49 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:15:49 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá configurar las propiedades y permisos de un rol en Filo.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso básico: {{permission}}.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Pasos para configurar los permisos del rol

Configurar los permisos de un rol te permitirá flexibilizar los permisos que otorgas en el servidor a un rol determinado.

## Pasos para establecer el campo de bits de permisos para un rol

## **Paso 1**: Establecer el campo de bits de permisos para un rol

Para establecer el campo de bits de permisos para un rol debes ejecutar el siguiente comando: <kbd>/core roles permissions ``role:<@Rol/ID del Rol>`` ``permission:<Campo de bits>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver la calculadora de permisos de Filo haciendo **[clic aquí](https://filobot.xyz/calculator)**.
{.is-info}

**Ejemplo**: <kbd>/core roles permissions ``role:@Moderators`` ``permission:147443``</kbd>.

> Puedes consultar nuestros paquetes de permisos preestablecidos haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/guild/role/preset-packages)**.
{.is-info}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/core roles reset</kbd>.

**Ejemplo**: <kbd>/core roles reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
