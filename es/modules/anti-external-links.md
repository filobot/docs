---
title: Anti Enlaces Externos
description:
published: true
date: Fri Nov 12 2021 17:35:10 GMT+0000 (Coordinated Universal Time)
dateCreated: Fri Nov 12 2021 17:35:10 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo sancionará a aquellos usuarios que envíen en su mensaje algún tipo de enlace.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

> Todos los enlaces de Discord harán bypass a este módulo.
{.is-warning}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere los siguientes permisos avanzados: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``MANAGE_MESSAGES``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` y ``MANAGE_MESSAGES``. **^1^**

- Si el usuario tiene el permiso ``ADMINISTRATOR``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_GUILD``. **^2^**

- Si el usuario tiene el permiso ``EVADE_SANCTIONS``. **^2^**

- Si la posición de los roles de Filo es más baja que la de los roles del usuario. **^2^**

- Si la posición de los roles de Filo es igual que la de los roles del usuario. **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-external-links enable</kbd>.

**Ejemplo**: <kbd>/anti-external-links enable</kbd>.

> Este módulo se puede complementar con el módulo **[Auto Moderación](https://wiki.filobot.xyz/es/modules/auto-moderation)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>/anti-external-links disable</kbd>.

**Ejemplo**: <kbd>/anti-external-links disable</kbd>.

# Pasos para agregar una URL a la lista de permitidas

## Pasos para añadir un subdominio a la lista de permitidos

### **Paso 1**: Añadir un subdominio a la lista de permitidos

Para añadir un subdominio a la lista de permitidos debes ejecutar el siguiente comando: <kbd>/anti-external-links link ``action:Add`` ``link:<URL>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>/anti-external-links link ``action:Add`` ``link:https://wiki.filobot.xyz``</kbd>.

> Puedes permitir todos los subdominios de un dominio reemplazando el subdominio por un asterisco.
> **Ejemplo**: https://*.filobot.xyz.
{.is-info}

> Puedes permitir todos los enlaces de un dominio y sus subdominios sustituyendo el subdominio y el path por asterísco tal y como se describe en este artículo.
> **Ejemplo**: https://*.filobot.xyz/*.
{.is-success}

## Pasos para añadir un dominio a la lista de permitidos

### **Paso 1**: Añadir un dominio a la lista de permitidos

Para añadir un dominio a la lista de permitidos debes ejecutar el siguiente comando: <kbd>/anti-external-links link ``action:Add`` ``link:<URL>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>/anti-external-links link ``action:Add`` ``link:https://filobot.xyz``</kbd>.

> Puedes permitir todos los enlaces de un dominio y sus subdominios sustituyendo el subdominio y el path por asterísco tal y como se describe en este artículo.
> **Ejemplo**: https://*.filobot.xyz/*.
{.is-success}

## Pasos para añadir una ruta a la lista de permitidos

### **Paso 1**: Añadir una ruta a la lista de permitidos

Para añadir una ruta a la lista de permitidos debes ejecutar el siguiente comando: <kbd>/anti-external-links link ``action:Add`` ``link:<URL>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>/anti-external-links link ``action:Add`` ``link:https://wiki.filobot.xyz/en/home``</kbd>.

> Puedes permitir todas las rutas de un dominio reemplazando la ruta por un asterisco.
> **Ejemplo**: https://filobot.xyz/*.
{.is-info}

> Puedes permitir todos los enlaces de un dominio y sus subdominios sustituyendo el subdominio y el path por asterísco tal y como se describe en este artículo.
> **Ejemplo**: https://*.filobot.xyz/*.
{.is-success}

## Pasos para eliminar una URL de la lista de permitidas

### **Paso 1**: Eliminar una URL de la lista de permitidas

Para eliminar una url de la lista de permitidas debes ejecutar el siguiente comando: <kbd>/anti-external-links link ``action:Remove`` ``link:<URL>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>/anti-external-links link ``action:Remove`` ``link:https://filobot.xyz``</kbd>.

# Pasos para activar el ignorar los enlaces de Filo

## **Paso 1**: Activar el ignorar los enlaces de Filo

Para activar el ignorar los enlaces de filo debes ejecutar el siguiente comando: <kbd>/anti-external-links filo ``action:Enable``</kbd>.

**Ejemplo**: <kbd>/anti-external-links filo ``action:Enable``</kbd>.

# Pasos para desactivar el ignorar los enlaces de Filo

## **Paso 1**: Desactivar el ignorar los enlaces de Filo

Para desactivar el ignorar los enlaces de filo debes ejecutar el siguiente comando: <kbd>/anti-external-links filo ``action:Disable``</kbd>.

**Ejemplo**: <kbd>/anti-external-links filo ``action:Disable``</kbd>.

# Pasos para activar el ignorar los enlaces de Discord

## **Paso 1**: Pasos para activar el ignorar los enlaces de Discord

Para pasos para activar el ignorar los enlaces de discord debes ejecutar el siguiente comando: <kbd>/anti-external-links discord ``action:Enable``</kbd>.

**Ejemplo**: <kbd>/anti-external-links discord ``action:Enable``</kbd>.

# Pasos para desactivar el ignorar los enlaces de Discord

## **Paso 1**: Desactivar el ignorar los enlaces de Discord

Para desactivar el ignorar los enlaces de discord debes ejecutar el siguiente comando: <kbd>/anti-external-links discord ``action:Disable``</kbd>.

**Ejemplo**: <kbd>/anti-external-links discord ``action:Disable``</kbd>.

# Pasos para establecer una sanción

## **Paso 1**: Establecer una sanción

Para establecer una sanción debes ejecutar el siguiente comando: <kbd>/anti-external-links action ``action:<Acción>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Puede ver una lista completa de las acciones que admite Filo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/actions-list)**.
{.is-info}

**Ejemplo**: <kbd>/anti-external-links action ``action:Temporarily mute the user`` ``time:1h``</kbd>.

# Steps to add a channel to the allowed list

## **Paso 1**: Add a channel to the allowed list

Para add a channel to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-external-links channel ``action:Add`` ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-external-links channel ``action:Add`` ``channel:#spam-allowed``</kbd>.

> Si añades un canal a la lista de permitidos, este módulo no funcionará en dicho canal.
{.is-warning}

# Steps to remove a channel to the allowed list

## **Paso 1**: Remove a channel to the allowed list

Para remove a channel to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-external-links channel ``action:Remove`` ``channel:<#Canal/ID del Canal>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-external-links channel ``action:Remove`` ``channel:#general``</kbd>.

> Si eliminas un canal de la lista de permitidos, este módulo funcionará en dicho canal.
{.is-warning}

# Steps to add a role to the allowed list

## **Paso 1**: Add a role to the allowed list

Para add a role to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-external-links role ``action:Add`` ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-external-links role ``action:Add`` ``role:@Moderators``</kbd>.

> Si añades un rol a la lista de permitidos, cualquier que tenga este rol estará exento del funcionamiento de este módulo.
{.is-warning}

# Steps to remove a role to the allowed list

## **Paso 1**: Remove a role to the allowed list

Para remove a role to the allowed list debes ejecutar el siguiente comando: <kbd>/anti-external-links role ``action:Remove`` ``role:<@Rol/ID del Rol>``</kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>/anti-external-links role ``action:Remove`` ``role:@Moderators``</kbd>.

> Si eliminas un rol de la lista de permitidos, cualquier que tenga este rol ya no estará exento del funcionamiento de este módulo.
{.is-warning}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>/anti-external-links reset</kbd>.

**Ejemplo**: <kbd>/anti-external-links reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
