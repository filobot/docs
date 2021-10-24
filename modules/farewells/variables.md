---
title: Farewells Variables
description:
published: true
date: Sun Oct 24 2021 14:22:23 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:22:23 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

> These variables may not always send the expected information.
{.is-danger}

# User variables

> `{{@user}}`
> This variable will return the mention of the user in question.
> **Example**: @DiscordUser#0000

> `{{user.id}}`
> This variable will return the id of the user in question.
> **Example**: 123456789123456789

> `{{user.name}}`
> This variable will return the name of the user in question.
> **Example**: DiscordUser

> `{{user.discriminator}}`
> This variable will return the discriminator of the user in question.
> **Example**: #0000

> `{{user.tag}}`
> This variable will return the name and discriminator of the user in question.
> **Example**: DiscordUser#0000

> `{{user.avatar}}`
> This variable will return the avatar id of the user in question. (if applicable)
> **Example**: avatar_id

> `{{user.avatarURL}}`
> This variable will return the avatar url of the user in question. (if applicable)
> **Example**: https://cdn.discordapp.com/avatars/user_id/avatar_id.jpg

> `{{user.registrationDate}}`
> This variable will return the registration date of the user in question. (if applicable)
> **Example**: 13/05/2021 @ 00:00 (x years ago)

> `{{user.url}}`
> This variable will return the url of the user in question. (if applicable)
> **Example**: https://discord.com/users/user_id

# Server variables

> `{{server}}`
> This variable will return the name of the server in question.
> **Example**: Awesome server

> `{{server.name}}`
> This variable will return the name of the server in question.
> **Example**: Awesome server

> `{{server.id}}`
> This variable will return the id of the server in question.
> **Example**: 123456789123456789

> `{{server.icon}}`
> This variable will return the icon id of the server in question. (if applicable)
> **Example**: icon_id

> `{{server.iconURL}}`
> This variable will return the icon url of the server in question. (if applicable)
> **Example**: https://cdn.discordapp.com/icons/server_id/icon_id.png

> `{{@server.owner}}`
> This variable will return the mention of the owner of the server in question. (if applicable)
> **Example**: @DiscordUser#0000

> `{{server.ownerID}}`
> This variable will return the id of the owner of the server in question. (if applicable)
> **Example**: 123456789123456789

> `{{server.members}}`
> This variable will return the member count of the server in question.
> **Example**: 123,456

> `{{server.memberCount}}`
> This variable will return the member count of the server in question.
> **Example**: 123456

> `{{server.inviteSplash}}`
> This variable will return the invite splash id of the server in question. (if applicable)
> **Example**: splash_id

> `{{server.inviteSplashURL}}`
> This variable will return the invite splash url of the server in question. (if applicable)
> **Example**: https://cdn.discordapp.com/splashes/server_id/splash_id.png

> `{{server.banner}}`
> This variable will return the banner id of the server in question. (if applicable)
> **Example**: banner_id

> `{{server.bannerURL}}`
> This variable will return the banner url of the server in question. (if applicable)
> **Example**: https://cdn.discordapp.com/banners/server_id/banner_id.png

> `{{server.vanityURL}}`
> This variable will return the vanity url of the server in question. (if applicable)
> **Example**: https://discord.gg/vanity_code

> `{{server.vanityCode}}`
> This variable will return the vanity code of the server in question. (if applicable)
> **Example**: vanity_code

> `{{server.description}}`
> This variable will return the description of the server in question. (if applicable)
> **Example**: An awesome server to chat to!

> `{{server.discoverySplash}}`
> This variable will return the discovery splash id of the server in question. (if applicable)
> **Example**: splash_id

> `{{server.discoverySplashURL}}`
> This variable will return the discovery splash url of the server in question. (if applicable)
> **Example**: https://cdn.discordapp.com/discovery-splashes/server_id/splash_id.png

> `{{server.verificationLevel}}`
> This variable will return the verification level of the server in question. (if applicable)
> **Example**: None

> `{{server.nsfwLevel}}`
> This variable will return the nsfw level of the server in question. (if applicable)
> **Example**: None

> `{{server.afkTimeout}}`
> This variable will return the time to move a user to the afk channel. (if applicable)
> **Example**: 500 seconds

> `{{server.afkChannel}}`
> This variable will return the afk channel of the server in question. (if applicable)
> **Example**: <#1234756789123456789>

> `{{server.afkChannelID}}`
> This variable will return the afk channel id of the server in question. (if applicable)
> **Example**: 1234756789123456789

> `{{server.systemChannel}}`
> This variable will return the system channel of the server in question. (if applicable)
> **Example**: <#1234756789123456789>

> `{{server.systemChannelID}}`
> This variable will return the system channel id of the server in question. (if applicable)
> **Example**: 1234756789123456789

> `{{server.rulesChannel}}`
> This variable will return the rules channel of the server in question. (if applicable)
> **Example**: <#1234756789123456789>

> `{{server.rulesChannelID}}`
> This variable will return the rules channel id of the server in question. (if applicable)
> **Example**: 1234756789123456789

> `{{server.publicUpdatesChannel}}`
> This variable will return the public updates channel of the server in question. (if applicable)
> **Example**: <#1234756789123456789>

> `{{server.publicUpdatesChannelID}}`
> This variable will return the public updates channel id of the server in question. (if applicable)
> **Example**: 1234756789123456789

> `{{server.premiumTier}}`
> This variable will return the premium tier of the server in question. (if applicable)
> **Example**: Tier 1

> `{{server.premiumSubscriptions}}`
> This variable will return the premium subscriptions of the server in question. (if applicable)
> **Example**: 123,456

> `{{server.premiumSubscriptionCount}}`
> This variable will return the premium subscriptions of the server in question. (if applicable)
> **Example**: 123456

> `{{server.explicitContentFilter}}`
> This variable will return the explicit content filter for the server in question. (if applicable)
> **Example**: Disabled

> `{{server.mfaLevel}}`
> This variable will return the mfa level of the server in question. (if applicable)
> **Example**: Enabled

> `{{server.creationDate}}`
> This variable will return the creation date of the server in question. (if applicable)
> **Example**: 13/05/2021 @ 00:00 (x years ago)

> `{{server.language}}`
> This variable will return the language of the server in question. (if applicable)
> **Example**: en-US

> `{{server.features}}`
> This variable will return the features of the server in question. (if applicable)
> **Example**: Community, news, animated icon