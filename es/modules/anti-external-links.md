---
title: Anti Enlaces Externos
description:
published: true
date: Thu Nov 11 2021 16:19:09 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Nov 11 2021 16:19:09 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# Acerca del módulo

Este módulo te permitirá eliminar los mensajes y advertir a los miembros que envíen enlaces externos.

> Recomendamos usar este módulo si administras una comunidad.
{.is-success}

> Todos los enlaces de Discord harán bypass a este módulo.
{.is-warning}

# Empezando

Antes de continuar con este artículo, debes tener en cuenta una serie de elementos que pueden influir cuando vayas a realizar alguna acción descrita en esta página:

- Filo requiere el siguiente permiso avanzado: ``MANAGE_MESSAGES``.

- Filo requiere los siguientes permisos básicos: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` y ``ADD_REACTIONS``.

- Necesitas el permiso ``ADMINISTRATOR`` para realizar la mayoría de las acciones de este artículo.

- Debes reemplazar <kbd>f!</kbd> con el prefijo actual que hayas establecido. Más información sobre cómo cambiar el prefijo haciendo **[clic aquí](https://wiki.filobot.xyz/es/modules/prefix)**.

# Excepciones del módulo

Este módulo tiene excepciones, lo que significa que no funcionará si se cumplen algunos de los requisitos que se mencionan a continuación:

- Si Filo no tiene los permisos ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS`` y ``MANAGE_MESSAGES``. **^1^**

- Si el usuario tiene el permiso ``ADMINISTRATOR``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_GUILD``. **^2^**

- Si el usuario tiene el permiso ``MANAGE_MESSAGES``. **^2^**

- Si el usuario tiene el permiso ``BAN_MEMBERS``. **^2^**

- Si el usuario tiene el permiso ``KICK_MEMBERS``. **^2^**

- Si la posición de los roles de Filo es más baja que la de los roles del usuario. **^2^**

- Si la posición de los roles de Filo es igual que la de los roles del usuario. **^2^**

**^1^** Si se cumple este requisito, la configuración del módulo se restablecerá.

**^2^** Si se cumplen estos o algunos de los requisitos, el módulo no funcionará.

# Pasos para habilitar el módulo

## **Paso 1**: Habilitar el módulo

Para habilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-external-links enable</kbd>.

**Ejemplo**: <kbd>f!config anti-external-links enable</kbd>.

> Este módulo se puede complementar con el módulo **[Auto Moderación](https://wiki.filobot.xyz/es/modules/auto-moderation)**.
{.is-success}

# Pasos para deshabilitar el módulo

## **Paso 1**: Deshabilitar el módulo

Para deshabilitar el módulo debes ejecutar el siguiente comando: <kbd>f!config anti-external-links disable</kbd>.

**Ejemplo**: <kbd>f!config anti-external-links disable</kbd>.

# Pasos para agregar una URL a la lista de permitidas

## Pasos para añadir un subdominio a la lista de permitidos

### **Paso 1**: Añadir un subdominio a la lista de permitidos

Para añadir un subdominio a la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow url add \<URL></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>f!config anti-external-links allow url add https://wiki.filobot.xyz</kbd>.

> Puedes permitir todos los subdominios de un dominio reemplazando el subdominio por un asterisco.
> **Ejemplo**: https://*.filobot.xyz.
{.is-info}

> Puedes permitir todos los enlaces de un dominio y sus subdominios sustituyendo el subdominio y el path por asterísco tal y como se describe en este artículo.
> **Ejemplo**: https://*.filobot.xyz/*.
{.is-success}

## Pasos para añadir un dominio a la lista de permitidos

### **Paso 1**: Añadir un dominio a la lista de permitidos

Para añadir un dominio a la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow url add \<URL></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>f!config anti-external-links allow url add https://filobot.xyz</kbd>.

> Puedes permitir todos los enlaces de un dominio y sus subdominios sustituyendo el subdominio y el path por asterísco tal y como se describe en este artículo.
> **Ejemplo**: https://*.filobot.xyz/*.
{.is-success}

## Pasos para añadir una ruta a la lista de permitidos

### **Paso 1**: Añadir una ruta a la lista de permitidos

Para añadir una ruta a la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow url add \<URL></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>f!config anti-external-links allow url add https://wiki.filobot.xyz/en/home</kbd>.

> Puedes permitir todas las rutas de un dominio reemplazando la ruta por un asterisco.
> **Ejemplo**: https://filobot.xyz/*.
{.is-info}

> Puedes permitir todos los enlaces de un dominio y sus subdominios sustituyendo el subdominio y el path por asterísco tal y como se describe en este artículo.
> **Ejemplo**: https://*.filobot.xyz/*.
{.is-success}

## Pasos para eliminar una URL de la lista de permitidas

### **Paso 1**: Eliminar una URL de la lista de permitidas

Para eliminar una url de la lista de permitidas debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow url remove \<URL></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

> Es obligatorio que la URL tenga el protocolo **HTTPS** habilitado, de lo contrario no podrá ser añadida a la lista de permitidas.
{.is-danger}

**Ejemplo**: <kbd>f!config anti-external-links allow url remove https://filobot.xyz</kbd>.

# Pasos para añadir un canal a la lista de permtiidos

## **Paso 1**: Añadir un canal a la lista de permitidos

Para añadir un canal a la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow channel add \<#Canal/ID del Canal></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-external-links allow channel add #spam-allowed</kbd>.

> Si agregas un canal a la lista de permitidos, no se otorgará una advertencia a los usuarios que envíen spam en esos canales.
{.is-warning}

# Pasos para eliminar un canal de la lista de permitidos

## **Paso 1**: Eliminar un canal de la lista de permitidos

Para eliminar un canal de la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow channel remove \<#Canal/ID del Canal></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-external-links allow channel remove #general</kbd>.

> Si eliminas un canal de la lista de permitidos, se otorgará una advertencia a los usuarios que envíen spam en esos canales.
{.is-warning}

# Pasos para añadir un canal a la lista de permtiidos

## **Paso 1**: Añadir un rol a la lista de permitidos

Para añadir un rol a la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow role add \<@Rol/ID del Rol></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-external-links allow role add @Moderators</kbd>.

> Si agregas un rol a la lista de permitidos, los usuarios que tengan ese rol asignado no recibirán una advertencia si envían spam.
{.is-warning}

# Pasos para eliminar un rol de la lista de permitidos

## **Paso 1**: Eliminar un rol de la lista de permitidos

Para eliminar un rol de la lista de permitidos debes ejecutar el siguiente comando: <kbd>f!config anti-external-links allow role remove \<@Rol/ID del Rol></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-external-links allow role remove @Moderators</kbd>.

> Si eliminas un rol de la lista de permitidos, los usuarios que tengan ese rol asignado recibirán una advertencia si envían spam.
{.is-warning}

# Pasos para restablecer las configuraciones del módulo

## **Paso 1**: Restablecer las configuraciones del módulo

Para restablecer las configuraciones del módulo debes ejecutar el siguiente comando: <kbd>f!config anti-external-links reset \<Allow/Action></kbd>.

> No incluyas ``<>`` cuando estés ejecutando el comando.
{.is-warning}

**Ejemplo**: <kbd>f!config anti-external-links reset</kbd>.

> Te verás obligado a confirmar la acción que estas a punto de realizar. Una vez la hayas confirmado, no podrás recuperar los datos anteriores.
{.is-danger}
