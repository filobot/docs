---
title: Contador de Miembros
description:
published: true
date: Wed Nov 10 2021 15:37:20 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:37:20 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá mostrar el contador de miembros de tu gremio en un canal de voz.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_CHANNELS``.

- Filo requiere el siguiente permiso básico: ``VIEW_CHANNEL``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/member-counter enable ``module:Member counter channel``</kbd>.

**Ejemplo**: <kbd>/member-counter enable ``module:Member counter channel``</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/member-counter disable ``module:Member counter channel``</kbd>.

**Ejemplo**: <kbd>/member-counter disable ``module:Member counter channel``</kbd>.

# Pasos para establecer el canal de contador de miembros

## **Paso 1**: Establecer el canal contador de miembros

Para establecer el canal contador de miembros debes ejecutar el siguiente comando: <kbd>/member-counter channel ``channel:<Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/member-counter channel ``channel:123456789123456789``</kbd>.

> El canal que selecciones debe ser un **canal de voz**, de lo contrario, el módulo no funcionará.
{.is-warning}

> Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL`` y ``MANAGE_CHANNELS``.
{.is-danger}

# Pasos para establecer el nombre del canal contador de miembros

## **Paso 1**: Establecer el nombre del canal contador de miembros

Para establecer el nombre del canal contador de miembros debes ejecutar el siguiente comando: <kbd>/member-counter name ``name:<Nombre {{members}}>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> El nombre del canal no puede exceder los **100 caracteres** de longitud y debe incluir la variable `{members}` en el contenido.
{.is-danger}

**Ejemplo**: <kbd>/member-counter name ``name:👥 Members: {{members}}``</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/member-counter reset</kbd>.

**Ejemplo**: <kbd>/member-counter reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
