---
title: Contador de Miembros
description:
published: true
date: Mon Jun 07 2021 16:01:17 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 07 2021 16:01:17 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá mostrar el contador de miembros de tu gremio en un canal de voz.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_CHANNELS``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](es/modules/prefix)**.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config member-counter enable</kbd>.

**Ejemplo**: <kbd>f!config member-counter enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config member-counter disable</kbd>.

**Ejemplo**: <kbd>f!config member-counter disable</kbd>.

# Pasos para establecer el canal de contador de miembros

## **Paso 1**: Establecer el canal contador de miembros

Para establecer el canal contador de miembros debes ejecutar el siguiente comando: <kbd>f!config member-counter set channel \<ID del Canal></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config member-counter set channel 123456789123456789</kbd>.

> El canal que selecciones debe ser un **canal de voz**, de lo contrario, el módulo no funcionará.
{.is-warning}

> Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_CHANNELS``.
{.is-danger}

# Pasos para establecer el nombre del canal contador de miembros

## **Paso 1**: Establecer el nombre del canal contador de miembros

Para establecer el nombre del canal contador de miembros debes ejecutar el siguiente comando: <kbd>f!config member-counter set name \<Nombre {members}></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> El nombre del canal no puede exceder los **28 caracteres** de longitud y debe incluir la variable `{members}` en el contenido.
{.is-danger}

**Ejemplo**: <kbd>f!config member-counter set name 👥 Members: {members}</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config member-counter reset \<Channel/Name/Nickname> (opcional)</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config member-counter reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
