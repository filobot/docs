---
title: Registros
description:
published: true
date: Mon Jun 07 2021 15:59:04 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 07 2021 15:59:04 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá enviar todos los registros del servidor a un canal específico.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_WEBHOOKS``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si se ha eliminado el webhook. **^1^**

- Si el webhook comparte un canal con otro módulo de Filo (ej. reportes). **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config logging enable</kbd>.

**Ejemplo**: <kbd>f!config logging enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config logging disable</kbd>.

**Ejemplo**: <kbd>f!config logging disable</kbd>.

# Pasos para establecer el canal de registros

## **Paso 1**: Establecer el canal de registros

Para establecer el canal de registros debes ejecutar el siguiente comando: <kbd>f!config logging set channel \<#Canal/ID del Canal></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config logging set channel #server-logs</kbd>.

> Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_WEBHOOKS``.
{.is-danger}

> El canal que selecciones debe ser privado y accesible para los moderadores del servidor.
{.is-success}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config logging reset \<Channel> (opcional)</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config logging reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
