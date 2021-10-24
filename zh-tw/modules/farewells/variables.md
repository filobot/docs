---
title: Farewells Variables
description:
published: true
date: Sun Oct 24 2021 14:22:23 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:22:23 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

> 這些變數可能不會總是發送出您預期的信息.
{.is-danger}

# 使用者 的變數們

> `{{@user}}`
> 這個變數會傳回 mention of the user in question.
> **範例**: @DiscordUser#0000

> `{{user.id}}`
> 這個變數會傳回 id of the user in question.
> **範例**: 123456789123456789

> `{{user.name}}`
> 這個變數會傳回 name of the user in question.
> **範例**: DiscordUser

> `{{user.discriminator}}`
> 這個變數會傳回 discriminator of the user in question.
> **範例**: #0000

> `{{user.tag}}`
> 這個變數會傳回 name and discriminator of the user in question.
> **範例**: DiscordUser#0000

> `{{user.avatar}}`
> 這個變數會傳回 avatar id of the user in question. (如果適用)
> **範例**: avatar_id

> `{{user.avatarURL}}`
> 這個變數會傳回 avatar url of the user in question. (如果適用)
> **範例**: https://cdn.discordapp.com/avatars/user_id/avatar_id.jpg

> `{{user.registrationDate}}`
> 這個變數會傳回 registration date of the user in question. (如果適用)
> **範例**: 13/05/2021 @ 00:00 (x years ago)

> `{{user.url}}`
> 這個變數會傳回 url of the user in question. (如果適用)
> **範例**: https://discord.com/users/user_id

# 伺服器 variables

> `{{server}}`
> 這個變數會傳回 name of the server in question.
> **範例**: Awesome server

> `{{server.name}}`
> 這個變數會傳回 name of the server in question.
> **範例**: Awesome server

> `{{server.id}}`
> 這個變數會傳回 id of the server in question.
> **範例**: 123456789123456789

> `{{server.icon}}`
> 這個變數會傳回 icon id of the server in question. (如果適用)
> **範例**: icon_id

> `{{server.iconURL}}`
> 這個變數會傳回 icon url of the server in question. (如果適用)
> **範例**: https://cdn.discordapp.com/icons/server_id/icon_id.png

> `{{@server.owner}}`
> 這個變數會傳回 mention of the owner of the server in question. (如果適用)
> **範例**: @DiscordUser#0000

> `{{server.ownerID}}`
> 這個變數會傳回 id of the owner of the server in question. (如果適用)
> **範例**: 123456789123456789

> `{{server.members}}`
> 這個變數會傳回 member count of the server in question.
> **範例**: 123,456

> `{{server.memberCount}}`
> 這個變數會傳回 member count of the server in question.
> **範例**: 123456

> `{{server.inviteSplash}}`
> 這個變數會傳回 invite splash id of the server in question. (如果適用)
> **範例**: splash_id

> `{{server.inviteSplashURL}}`
> 這個變數會傳回 invite splash url of the server in question. (如果適用)
> **範例**: https://cdn.discordapp.com/splashes/server_id/splash_id.png

> `{{server.banner}}`
> 這個變數會傳回 banner id of the server in question. (如果適用)
> **範例**: banner_id

> `{{server.bannerURL}}`
> 這個變數會傳回 banner url of the server in question. (如果適用)
> **範例**: https://cdn.discordapp.com/banners/server_id/banner_id.png

> `{{server.vanityURL}}`
> 這個變數會傳回 vanity url of the server in question. (如果適用)
> **範例**: https://discord.gg/vanity_code

> `{{server.vanityCode}}`
> 這個變數會傳回 vanity code of the server in question. (如果適用)
> **範例**: vanity_code

> `{{server.description}}`
> 這個變數會傳回 description of the server in question. (如果適用)
> **範例**: An awesome server to chat to!

> `{{server.discoverySplash}}`
> 這個變數會傳回 discovery splash id of the server in question. (如果適用)
> **範例**: splash_id

> `{{server.discoverySplashURL}}`
> 這個變數會傳回 discovery splash url of the server in question. (如果適用)
> **範例**: https://cdn.discordapp.com/discovery-splashes/server_id/splash_id.png

> `{{server.verificationLevel}}`
> 這個變數會傳回 verification level of the server in question. (如果適用)
> **範例**: None

> `{{server.nsfwLevel}}`
> 這個變數會傳回 nsfw level of the server in question. (如果適用)
> **範例**: None

> `{{server.afkTimeout}}`
> 這個變數會傳回 time to move a user to the afk channel. (如果適用)
> **範例**: 500 秒

> `{{server.afkChannel}}`
> 這個變數會傳回 afk channel of the server in question. (如果適用)
> **範例**: <#1234756789123456789>

> `{{server.afkChannelID}}`
> 這個變數會傳回 afk channel id of the server in question. (如果適用)
> **範例**: 1234756789123456789

> `{{server.systemChannel}}`
> 這個變數會傳回 system channel of the server in question. (如果適用)
> **範例**: <#1234756789123456789>

> `{{server.systemChannelID}}`
> 這個變數會傳回 system channel id of the server in question. (如果適用)
> **範例**: 1234756789123456789

> `{{server.rulesChannel}}`
> 這個變數會傳回 rules channel of the server in question. (如果適用)
> **範例**: <#1234756789123456789>

> `{{server.rulesChannelID}}`
> 這個變數會傳回 rules channel id of the server in question. (如果適用)
> **範例**: 1234756789123456789

> `{{server.publicUpdatesChannel}}`
> 這個變數會傳回 public updates channel of the server in question. (如果適用)
> **範例**: <#1234756789123456789>

> `{{server.publicUpdatesChannelID}}`
> 這個變數會傳回 public updates channel id of the server in question. (如果適用)
> **範例**: 1234756789123456789

> `{{server.premiumTier}}`
> 這個變數會傳回 premium tier of the server in question. (如果適用)
> **範例**: Tier 1

> `{{server.premiumSubscriptions}}`
> 這個變數會傳回 premium subscriptions of the server in question. (如果適用)
> **範例**: 123,456

> `{{server.premiumSubscriptionCount}}`
> 這個變數會傳回 premium subscriptions of the server in question. (如果適用)
> **範例**: 123456

> `{{server.explicitContentFilter}}`
> 這個變數會傳回 explicit content filter for the server in question. (如果適用)
> **範例**: Disabled

> `{{server.mfaLevel}}`
> 這個變數會傳回 mfa level of the server in question. (如果適用)
> **範例**: Enabled

> `{{server.creationDate}}`
> 這個變數會傳回 creation date of the server in question. (如果適用)
> **範例**: 13/05/2021 @ 00:00 (x years ago)

> `{{server.language}}`
> 這個變數會傳回 language of the server in question. (如果適用)
> **範例**: en-US

> `{{server.features}}`
> 這個變數會傳回 features of the server in question. (如果適用)
> **範例**: Community, news, animated icon