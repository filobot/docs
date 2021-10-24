---
title: Variables de Despedida
description:
published: true
date: Sun Oct 24 2021 14:22:23 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:22:23 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

> Es posible que estas variables no siempre envíen la información esperada.
{.is-danger}

# Variables de Usuario

> `{{@user}}`
> Esta variable devolverá el mención del usuario en cuestión.
> **Ejemplo**: @DiscordUser#0000

> `{{user.id}}`
> Esta variable devolverá el id del usuario en cuestión.
> **Ejemplo**: 123456789123456789

> `{{user.name}}`
> Esta variable devolverá el nombre del usuario en cuestión.
> **Ejemplo**: DiscordUser

> `{{user.discriminator}}`
> Esta variable devolverá el discriminador del usuario en cuestión.
> **Ejemplo**: #0000

> `{{user.tag}}`
> Esta variable devolverá el nombre y discriminador del usuario en cuestión.
> **Ejemplo**: DiscordUser#0000

> `{{user.avatar}}`
> Esta variable devolverá el id del avatar del usuario en cuestión. (si aplica)
> **Ejemplo**: avatar_id

> `{{user.avatarURL}}`
> Esta variable devolverá el url del avatar del usuario en cuestión. (si aplica)
> **Ejemplo**: https://cdn.discordapp.com/avatars/user_id/avatar_id.jpg

> `{{user.registrationDate}}`
> Esta variable devolverá el fecha de registro del usuario en cuestión. (si aplica)
> **Ejemplo**: 13/05/2021 @ 00:00 (x years ago)

> `{{user.url}}`
> Esta variable devolverá el url del usuario en cuestión. (si aplica)
> **Ejemplo**: https://discord.com/users/user_id

# Variables de Servidor

> `{{server}}`
> Esta variable devolverá el nombre del servidor en cuestión.
> **Ejemplo**: Awesome server

> `{{server.name}}`
> Esta variable devolverá el nombre del servidor en cuestión.
> **Ejemplo**: Awesome server

> `{{server.id}}`
> Esta variable devolverá el id del servidor en cuestión.
> **Ejemplo**: 123456789123456789

> `{{server.icon}}`
> Esta variable devolverá el id del icono del servidor en cuestión. (si aplica)
> **Ejemplo**: icon_id

> `{{server.iconURL}}`
> Esta variable devolverá el url del icono del servidor en cuestión. (si aplica)
> **Ejemplo**: https://cdn.discordapp.com/icons/server_id/icon_id.png

> `{{@server.owner}}`
> Esta variable devolverá el mención del propietario del servidor en cuestión. (si aplica)
> **Ejemplo**: @DiscordUser#0000

> `{{server.ownerID}}`
> Esta variable devolverá el id del propietario del servidor en cuestión. (si aplica)
> **Ejemplo**: 123456789123456789

> `{{server.members}}`
> Esta variable devolverá el contador de miembros del servidor en cuestión.
> **Ejemplo**: 123,456

> `{{server.memberCount}}`
> Esta variable devolverá el contador de miembros del servidor en cuestión.
> **Ejemplo**: 123456

> `{{server.inviteSplash}}`
> Esta variable devolverá el id del fondo de invitación del servidor en cuestión. (si aplica)
> **Ejemplo**: splash_id

> `{{server.inviteSplashURL}}`
> Esta variable devolverá el url del fondo de invitación del servidor en cuestión. (si aplica)
> **Ejemplo**: https://cdn.discordapp.com/splashes/server_id/splash_id.png

> `{{server.banner}}`
> Esta variable devolverá el id del cartel del servidor en cuestión. (si aplica)
> **Ejemplo**: banner_id

> `{{server.bannerURL}}`
> Esta variable devolverá el url del cartel del servidor en cuestión. (si aplica)
> **Ejemplo**: https://cdn.discordapp.com/banners/server_id/banner_id.png

> `{{server.vanityURL}}`
> Esta variable devolverá el url de vanidad del servidor en cuestión. (si aplica)
> **Ejemplo**: https://discord.gg/vanity_code

> `{{server.vanityCode}}`
> Esta variable devolverá el código de vanidad del servidor en cuestión. (si aplica)
> **Ejemplo**: vanity_code

> `{{server.description}}`
> Esta variable devolverá el descripción del servidor en cuestión. (si aplica)
> **Ejemplo**: An awesome server to chat to!

> `{{server.discoverySplash}}`
> Esta variable devolverá el id del fondo de descubrimiento del servidor en cuestión. (si aplica)
> **Ejemplo**: splash_id

> `{{server.discoverySplashURL}}`
> Esta variable devolverá el url del fondo de descubrimiento del servidor en cuestión. (si aplica)
> **Ejemplo**: https://cdn.discordapp.com/discovery-splashes/server_id/splash_id.png

> `{{server.verificationLevel}}`
> Esta variable devolverá el nivel de verificación del servidor en cuestión. (si aplica)
> **Ejemplo**: None

> `{{server.nsfwLevel}}`
> Esta variable devolverá el nivel nsfw del servidor en cuestión. (si aplica)
> **Ejemplo**: None

> `{{server.afkTimeout}}`
> Esta variable devolverá el tiempo para mover a un usuario al canal afk. (si aplica)
> **Ejemplo**: 500 segundos

> `{{server.afkChannel}}`
> Esta variable devolverá el canal afk del servidor en cuestión. (si aplica)
> **Ejemplo**: <#1234756789123456789>

> `{{server.afkChannelID}}`
> Esta variable devolverá el id del canal afk del servidor en cuestión. (si aplica)
> **Ejemplo**: 1234756789123456789

> `{{server.systemChannel}}`
> Esta variable devolverá el canal del sistema del servidor en cuestión. (si aplica)
> **Ejemplo**: <#1234756789123456789>

> `{{server.systemChannelID}}`
> Esta variable devolverá el id del canal del sistema del servidor en cuestión. (si aplica)
> **Ejemplo**: 1234756789123456789

> `{{server.rulesChannel}}`
> Esta variable devolverá el canal de reglas del servidor en cuestión. (si aplica)
> **Ejemplo**: <#1234756789123456789>

> `{{server.rulesChannelID}}`
> Esta variable devolverá el id del canal de reglas del servidor en cuestión. (si aplica)
> **Ejemplo**: 1234756789123456789

> `{{server.publicUpdatesChannel}}`
> Esta variable devolverá el canal de actualizaciones públicas del servidor en cuestión. (si aplica)
> **Ejemplo**: <#1234756789123456789>

> `{{server.publicUpdatesChannelID}}`
> Esta variable devolverá el id del canal de actualizaciones públicas del servidor en cuestión. (si aplica)
> **Ejemplo**: 1234756789123456789

> `{{server.premiumTier}}`
> Esta variable devolverá el nivel premium del servidor en cuestión. (si aplica)
> **Ejemplo**: Tier 1

> `{{server.premiumSubscriptions}}`
> Esta variable devolverá el suscripciones premium del servidor en cuestión. (si aplica)
> **Ejemplo**: 123,456

> `{{server.premiumSubscriptionCount}}`
> Esta variable devolverá el suscripciones premium del servidor en cuestión. (si aplica)
> **Ejemplo**: 123456

> `{{server.explicitContentFilter}}`
> Esta variable devolverá el filtro de contenido explícito del servidor en cuestión. (si aplica)
> **Ejemplo**: Disabled

> `{{server.mfaLevel}}`
> Esta variable devolverá el nivel mfa del servidor en cuestión. (si aplica)
> **Ejemplo**: Enabled

> `{{server.creationDate}}`
> Esta variable devolverá el fecha de creación del servidor en cuestión. (si aplica)
> **Ejemplo**: 13/05/2021 @ 00:00 (x years ago)

> `{{server.language}}`
> Esta variable devolverá el idioma del servidor en cuestión. (si aplica)
> **Ejemplo**: en-US

> `{{server.features}}`
> Esta variable devolverá el ventajas del servidor en cuestión. (si aplica)
> **Ejemplo**: Community, news, animated icon