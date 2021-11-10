---
title: Apodo Contador de Miembros
description:
published: true
date: Wed Nov 10 2021 15:40:22 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:40:22 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá establecer un contador de miembros en el apodo de Filo.

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso avanzado: ``CHANGE_NICKNAME``.

- Filo requiere el siguiente permiso básico: ``VIEW_CHANNEL``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene el permiso ``CHANGE_NICKNAME``. **^1^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/member-counter enable ``module:Member counter nickname``</kbd>.

**Ejemplo**: <kbd>/member-counter enable ``module:Member counter nickname``</kbd>.

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/member-counter disable ``module:Member counter nickname``</kbd>.

**Ejemplo**: <kbd>/member-counter disable ``module:Member counter nickname``</kbd>.

# Pasos para establecer el apodo

## **Paso 1**: Establecer el apodo

Para establecer el apodo debes ejecutar el siguiente comando: <kbd>/member-counter nickname ``nickname:<Nombre {{members}}>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> El apodo no puede exceder los **32 caracteres** de longitud y debe incluir la variable `{members}` en el contenido.
{.is-danger}

**Ejemplo**: <kbd>/member-counter nickname ``nickname:👥 Members: {{members}}``</kbd>.

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/member-counter reset</kbd>.

**Ejemplo**: <kbd>/member-counter reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
