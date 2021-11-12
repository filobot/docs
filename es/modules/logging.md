---
title: Registros
description:
published: true
date: Wed Nov 10 2021 15:54:59 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:54:59 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá recibir los registros de auditoría a través de mensajes en un canal específico.

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

- Si el webhook comparte un canal con otro módulo de Filo (ej. reportes). **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/logging enable</kbd>.

**Ejemplo**: <kbd>/logging enable</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/logging disable</kbd>.

**Ejemplo**: <kbd>/logging disable</kbd>.

# Pasos para establecer el canal de registros

## **Paso 1**: Establecer el canal de registros

Para establecer el canal de registros debes ejecutar el siguiente comando: <kbd>/logging channel ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/logging channel ``channel:#server-logs``</kbd>.

> Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_WEBHOOKS``.
{.is-danger}

> El canal que selecciones debe ser privado y accesible para los moderadores del servidor.
{.is-success}

# Pasos para configurar los eventos del módulo

## Pasos para habilitar un evento

### **Paso 1**: Habilitar un evento

Para habilitar un evento debes ejecutar el siguiente comando: <kbd>/logging events ``action:Enable``</kbd>.

**Ejemplo**: <kbd>/logging events ``action:Enable``</kbd>.

## Pasos para deshabilitar un evento

### **Paso 1**: Deshabilitar un evento

Para deshabilitar un evento debes ejecutar el siguiente comando: <kbd>/logging events ``action:Disable``</kbd>.

**Ejemplo**: <kbd>/logging events ``action:Disable``</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/logging reset</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/logging reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
