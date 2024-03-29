---
title: Deshabilitar Comandos
description:
published: true
date: Sun Oct 24 2021 11:54:26 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 11:54:26 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá desactivar los comandos de Filo para todos los miembros del servidor (incluido tú).

> The documentation for this module is out of date. See an updated version by **[clicking here](https://wiki-canary.filobot.xyz/modules/commands)**.
> {.is-warning}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso básico: ``VIEW_CHANNEL``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Pasos para deshabilitar un comando

## **Paso 1**: Deshabilitar un comando

Para deshabilitar un comando debes ejecutar el siguiente comando: <kbd>/commands disable ``target:Command`` ``value:<Comando>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/commands disable ``taarget:Command`` ``value:ping``</kbd>.

# Pasos para habilitar un comando

## **Paso 1**: Habilitar un comando

Para habilitar un comando debes ejecutar el siguiente comando: <kbd>/commands enable ``target:Command`` ``value:<Comando>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/commands enable ``target:Command`` ``value:ping``</kbd>.

# Pasos paraa deshabilitar una categoría de comandos

## **Paso 1**: Deshabilitar una categoría de comandos

Para deshabilitar una categoría de comandos debes ejecutar el siguiente comando: <kbd>/commands disable ``target:Category`` ``value:<Categoría>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/commands disable ``taarget:Category`` ``value:Core``</kbd>.

# Pasos paraa habilitar una categoría de comandos

## **Paso 1**: Habilitar una categoría de comandos

Para habilitar una categoría de comandos debes ejecutar el siguiente comando: <kbd>/commands enable ``target:Category`` ``value:<Categoría>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/commands enable ``target:Category`` ``value:Core``</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/commands reset</kbd>.

**Ejemplo**: <kbd>/commands reset</kbd>.
