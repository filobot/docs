---
title: Welcomes
description:
published: true
date: Mon Jun 14 2021 13:19:25 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:19:25 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以為剛進入伺服器的人發佈一條訊息.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` 和 ``USE_EXTERNAL_EMOJIS``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR`` .

- 你需要取代 <kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請**[點擊這裡](zh-Tw/modules/prefix)**.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有以下權限： ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` 和 ``USE_EXTERNAL_EMOJIS``. **^1^**

**^1^** 如果要滿足此要求，模組設置將被重置.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>f!config welcomes enable</kbd>.

**範例**: <kbd>f!config welcomes enable</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>f!config welcomes disable</kbd>.

**範例**: <kbd>f!config welcomes disable</kbd>.

# 設定歡迎訊息發佈頻道的步驟

## **步驟 1**: 設定歡迎訊息發佈頻道

如果要 設定歡迎訊息發佈頻道 ，您必須執行以下指令：<kbd>f!config welcomes set channel \<#頻道/頻道 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config welcomes set channel #welcomes</kbd>.

# 設定歡迎訊息的步驟

## **步驟 1**: 設定歡迎訊息

如果要 設定歡迎訊息發佈頻道 ，您必須執行以下指令：<kbd>f!config welcomes set message \<訊息></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 你可以在歡迎訊息裡添加變數，點擊**[這個連結](https://wiki.filobot.xyz/zh-Tw/modules/welcomes/variables)**來查看 Filo 支援的變數.
{.is-info}

**範例**: <kbd>f!config welcomes set message Goodbye {user.tag}!</kbd>.

> ```md
> Welcome {user} to the server **{server}**! 😉
> Thanks to you we are **{server.members}** total members! 🎉
> ```
> **訊息程式碼**
>
> Welcome @DiscordUser to the server **Awesome Server**! 😉
> Thanks to you we are **123,456** total members! 🎉
>
> **訊息結果**

# 設定訊息類型的步驟

## **步驟 1**: 設定訊息類型

如果要 設定訊息類型 ，您必須執行以下指令：<kbd>f!config welcomes set type \<Normal/Embed></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config welcomes set type embed</kbd>.

> 如果使用者關閉嵌入內容，他將看不到訊息.
{.is-danger}

## **步驟 12**: 設定嵌入內容的顏色 (可填)

目前 Filo 並沒有一個改變顏色的指令，如果需要你可以改變 Filo 身分組的顏色，嵌入內容顏色將會隨著身分組顏色一起改動.

> 點**[這裡](https://support.discord.com/hc/en-us/articles/214836687)**來查看Discord官方的說明
{.is-info}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config welcomes reset \<Channel/Message/Type/Role> (可填)</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config welcomes reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
