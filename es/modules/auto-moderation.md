---
title: Auto Moderación
description:
published: true
date: Sun Jun 27 2021 10:53:29 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Jun 27 2021 10:53:29 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá sancionar automáticamente a aquellos usuarios que tengan repetidamente un comportamiento incorrecto.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``MANAGE_MESSAGES``, ``MANAGE_ROLES``, ``KICK_MEMBERS`` y``BAN_MEMBERS`` (si aplica).

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``MANAGE_MESSAGES``, ``MANAGE_ROLES``, ``KICK_MEMBERS`` y ``BAN_MEMBERS``. **^1^**

- Si el usuario tiene el permiso ``ADMINISTRATOR``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_GUILD``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_ROLES``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_MESSAGES``. **^2^**

- Si el usuario tiene el permiso ``BAN_MEMBERS``. **^2^**

- Si el usuario tiene el permiso ``KICK_MEMBERS``. **^2^**

- Si el usuario tiene el permiso ``MUTE_MEMBERS``. **^2^**

- Si la posición de los roles de Filo es más baja que la de los roles del usuario. **^2^**

- Si la posición de los roles de Filo es igual que la de los roles del usuario. **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config auto-moderation enable</kbd>.

**Ejemplo**: <kbd>f!config auto-moderation enable</kbd>.

> Este módulo se puede complementar con el módulo **[Anti Evasión](https://wiki.filobot.xyz/es/modules/anti-evasion)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config auto-moderation disable</kbd>.

**Ejemplo**: <kbd>f!config auto-moderation disable</kbd>.

# Pasos para establecer las advertencias máximas por nivel

## **Paso 1**: Establecer las advertencias máximas por nivel

Para establecer las advertencias máximas por nivel debes ejecutar el siguiente comando: <kbd>f!config auto-moderation set level \<Nivel> \<Número></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config auto-moderation set level 1 3</kbd>.

# Pasos para establecer la acción por nivel

## **Paso 1**: Establecer la acción por nivel

Para establecer la acción por nivel debes ejecutar el siguiente comando: <kbd>f!config auto-moderation set action \<Nivel> \<Acción></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puedes ver una lista completa de las acciones que admite Filo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/auto-moderation/actions)**
{.is-info}

**Ejemplo**: <kbd>f!config auto-moderation set action 1 kick</kbd>.

# Pasos para establecer el tiempo de la acción por nivel

## **Paso 1**: Establecer el tiempo de la acción por nivel

Para establecer el tiempo de la acción por nivel debes ejecutar el siguiente comando: <kbd>f!config auto-moderation set time \<Nivel> \<Tiempo></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config auto-moderation set time 1 1h</kbd>.

> La duración de la acción debe estar entre **1 minutos** y **24 dias**.
{.is-warning}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config auto-moderation reset \<Levels></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config auto-moderation reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
