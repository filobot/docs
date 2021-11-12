---
title: Reportes
description:
published: true
date: Sun Oct 24 2021 12:22:33 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:22:33 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo permitirá que los usuarios puedan informar del mal comportamiento de otros usuarios del servidor.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_WEBHOOKS``.

- Filo requiere el siguiente permiso básico: ``VIEW_CHANNEL``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si se ha eliminado el webhook. **^1^**

- Si el webhook comparte un canal con otro módulo de Filo (ej. registros). **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/reports enable</kbd>.

**Ejemplo**: <kbd>/reports enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/reports disable</kbd>.

**Ejemplo**: <kbd>/reports disable</kbd>.

# Pasos para establer el canal de reportes

## **Paso 1**: Establecer el canal de reportes

Para establecer el canal de reportes debes ejecutar el siguiente comando: <kbd>/reports channel ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/reports channel ``channel:#reports``</kbd>.

> Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_WEBHOOKS``.
{.is-danger}

> El canal que selecciones debe ser privado y accesible para los moderadores del servidor.
{.is-success}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/reports reset</kbd>.

**Ejemplo**: <kbd>/reports reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
