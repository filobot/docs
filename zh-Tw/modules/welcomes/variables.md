---
title: Welcomes Variables
description:
published: true
date: Thu Jun 03 2021 14:36:04 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Jun 03 2021 14:36:04 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

> 這些變數可能不會總是發送出您預期的信息.
{.is-danger}

# 使用者 variables

> `{user}`
> 這個變數會傳回 相關使用者的提及.
> **範例**: @DiscordUser#0000

> `{user.id}`
> 這個變數會傳回 相關使用者的 id.
> **範例**: 123456789123456789

> `{user.name}`
> 這個變數會傳回 相關使用者的名稱.
> **範例**: DiscordUser

> `{user.discriminator}`
> 這個變數會傳回 相關使用者的編號.
> **範例**: #0000

> `{user.tag}`
> 這個變數會傳回 相關使用者的名稱和編號.
> **範例**: DiscordUser#0000

> `{user.avatar_url}`
> 這個變數會傳回 相關使用者的大頭貼 url. (如果適用)
> **範例**: https://cdn.discordapp.com/avatars/user_id/avatar_id.jpg

# 伺服器 variables

> `{server}`
> 這個變數會傳回 伺服器名稱.
> **範例**: Awesome server

> `{server.id}`
> 這個變數會傳回 伺服器 id.
> **範例**: 123456789123456789

> `{server.icon_url}`
> 這個變數會傳回 伺服器圖示url. (如果適用)
> **範例**: https://cdn.discordapp.com/icons/server_id/icon_id.png

> `{server.owner}`
> 這個變數會傳回 伺服器擁有者的提及. (如果適用)
> **範例**: @DiscordUser#0000

> `{server.ownerID}`
> 這個變數會傳回 伺服器擁有者的 id. (如果適用)
> **範例**: 123456789123456789

> `{server.members}`
> 這個變數會傳回 伺服器成員數量.
> **範例**: 123,456

> `{server.splash}`
> 這個變數會傳回 伺服器邀請頁面 url. (如果適用)
> **範例**: https://cdn.discordapp.com/splashes/server_id/splash_id.png

> `{server.banner}`
> 這個變數會傳回 伺服器橫幅 url. (如果適用)
> **範例**: https://cdn.discordapp.com/banners/server_id/banner_id.png
