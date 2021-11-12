---
title: Anti Evasión
description:
published: true
date: Fri Nov 12 2021 15:43:29 GMT+0000 (Coordinated Universal Time)
dateCreated: Fri Nov 12 2021 15:43:29 GMT+0000 (Coordinated Universal Time)
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

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene el permiso ``BAN_MEMBERS``. **^1^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-evasion enable</kbd>.

**Ejemplo**: <kbd>/anti-evasion enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-evasion disable</kbd>.

**Ejemplo**: <kbd>/anti-evasion disable</kbd>.

# Pasos para establecer la acción

## **Paso 1**: Establecer la acción

Para establecer la acción debes ejecutar el siguiente comando: <kbd>/anti-evasion action ``action:<Acción>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver una lista completa de las acciones que admite Filo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/actions-list)**.
{.is-info}

**Ejemplo**: <kbd>/anti-evasion action ``action:Temporarily ban the user`` ``time:7d``</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/anti-evasion reset</kbd>.

**Ejemplo**: <kbd>/anti-evasion reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
