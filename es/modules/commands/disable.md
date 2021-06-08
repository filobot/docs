---
title: Deshabilitar Comandos
description:
published: true
date: Thu Jun 03 2021 14:35:24 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Jun 03 2021 14:35:24 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo le permitirá deshabilitar los comandos de Filo que no desea que se usen en su servidor.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``USE_EXTERNAL_EMOJIS``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, y ``USE_EXTERNAL_EMOJIS``. **^1^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

# Pasos para deshabilitar un comando

## **Paso 1**: Deshabilitar un comando

Para deshabilitar un comando debes ejecutar el siguiente comando: <kbd>f!config commands disable \<Comando></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config commands disable ping</kbd>.

# Pasos para habilitar un comando

## **Paso 1**: Habilitar un comando

Para habilitar un comando debes ejecutar el siguiente comando: <kbd>f!config commands enable \<Comando></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config commands enable ping</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config commands reset \<Disabled></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config commands reset disabled</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
