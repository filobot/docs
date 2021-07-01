---
title: Configurar un Rol
description:
published: true
date: Wed Jun 30 2021 12:22:56 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Jun 30 2021 12:22:56 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá configurar las propiedades y permisos de un rol en Filo.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/prefix)**.

# Pasos para configurar los permisos del rol

Configurar los permisos de un rol te permitirá flexibilizar los permisos que otorgas en el servidor a un rol determinado.

## Pasos para establecer el campo de bits de permisos para un rol

## **Paso 1**: Establecer el campo de bits de permisos para un rol

Para establecer el campo de bits de permisos para un rol debes ejecutar el siguiente comando: <kbd>f!config guild role custom \<@Rol/ID del Rol> permissions set \<Campo de bits></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver la calculadora de permisos de Filo haciendo **[clic aquí](https://filobot.xyz/calculator)**.
{.is-info}

**Ejemplo**: <kbd>f!config guild role custom @Moderators permissions set 147443</kbd>.

> Puedes consultar nuestros paquetes de permisos preestablecidos haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/guild/role/preset-packages)**.
{.is-info}

## Pasos para añadir un permiso a un rol

## **Paso 1**: Añadir un permiso a un rol

Para añadir un permiso a un rol debes ejecutar el siguiente comando: <kbd>f!config guild role custom \<@Rol/ID del Rol> permissions add \<Permiso></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver la calculadora de permisos de Filo haciendo **[clic aquí](https://filobot.xyz/calculator)**.
{.is-info}

**Ejemplo**: <kbd>f!config guild role custom @Moderators permissions add VIEW_CASES</kbd>.

> Puedes ver una lista completa de permisos ejecutando el siguiente comando: **f!config guild role custom \<@Rol/ID del Rol> permissions list**.
{.is-info}

## Pasos para eliminar un permiso a un rol

## **Paso 1**: Eliminar un permiso a un rol

Para eliminar un permiso a un rol debes ejecutar el siguiente comando: <kbd>f!config guild role custom \<@Rol/ID del Rol> permissions remove \<Permiso></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver la calculadora de permisos de Filo haciendo **[clic aquí](https://filobot.xyz/calculator)**.
{.is-info}

**Ejemplo**: <kbd>f!config guild role custom @Moderators permissions remove VIEW_CASES</kbd>.

> Puedes ver una lista completa de permisos ejecutando el siguiente comando: **f!config guild role custom \<@Rol/ID del Rol> permissions list**.
{.is-info}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config guild reset \<Roles></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config guild reset roles</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
