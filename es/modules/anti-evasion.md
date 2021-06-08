---
title: Anti Evasión
description:
published: true
date: Mon Jun 07 2021 16:00:29 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 07 2021 16:00:29 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá banear automáticamente a aquellos usuarios que fueron sancionados en tu servidor e intentaron evadir la sanción.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso avanzado: ``BAN_MEMBERS``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS`` y ``BAN_MEMBERS``. **^1^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-evasion enable</kbd>.

**Ejemplo**: <kbd>f!config anti-evasion enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-evasion disable</kbd>.

**Ejemplo**: <kbd>f!config anti-evasion disable</kbd>.

# Pasos para establecer la acción

## **Paso 1**: Establecer la acción

Para establecer la acción debes ejecutar el siguiente comando: <kbd>f!config anti-evasion set action \<Acción></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-evasion set action tempban</kbd>.

> Puede ver una lista completa de las acciones que admite Filo haciendo **[clic aquí](/es/modules/anti-evasion/actions)**.
{.is-info}

# Pasos para establecer el tiempo de la acción

## **Paso 1**: Establecer el tiempo de la acción

Para establecer el tiempo de la acción debes ejecutar el siguiente comando: <kbd>f!config anti-evasion set time \<Tiempo></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-evasion set action 1d</kbd>.

> La duración de la acción debe estar entre **1 minutos** y **24 dias**.
{.is-warning}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config anti-evasion reset \<Allow> (opcional)</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-evasion reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
