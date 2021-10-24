---
title: Farewells
description:
published: true
date: Sun Oct 24 2021 14:37:45 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:37:45 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以為離開伺服器的人發佈一條訊息.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES`` 和 ``EMBED_LINKS``.

- Filo 需要要此項基礎權限: ``VIEW_CHANNEL``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有以下權限： ``VIEW_CHANNEL``, ``SEND_MESSAGES`` 和 ``EMBED_LINKS``. **^1^**

**^1^** 如果要滿足此要求，模組設置將被重置.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>/farewells enable</kbd>.

**範例**: <kbd>/farewells enable</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/farewells disable</kbd>.

**範例**: <kbd>/farewells disable</kbd>.

# 設定離別訊息發佈頻道的步驟

## **步驟 1**: 設定離別訊息發佈頻道

如果要 設定離別訊息發佈頻道 ，您必須執行以下指令：<kbd>/farewells channel ``channel:<#頻道/頻道 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/farewells channel ``channel:#farewells``</kbd>.

# 設定離別訊息的步驟

## **步驟 1**: 設定離別訊息

如果要 設定離別訊息發佈頻道 ，您必須執行以下指令：<kbd>/farewells message</kbd>.

> You'll have **1 分** to perform this action.
{.is-warning}

**範例**: <kbd>/farewells message</kbd>.

> 你可以在離別訊息裡添加變數，點擊 **[這個連結](https://wiki.filobot.xyz/zh-tw/modules/farewells/variables)** 來查看 Filo 支援的變數.
{.is-info}

> ```md
> Goodbye **{{user.tag}}**! 😧
> We look forward to your return in **{{server.name}}**. 👋
> ```
> **訊息程式碼**
>
> Goodbye **DiscordUser#0000**! 😧
> We look forward to your return in **Awesome Server**. 👋
>
> **訊息結果**

# 設定訊息類型的步驟

## **步驟 1**: 設定訊息類型

如果要 設定訊息類型 ，您必須執行以下指令：<kbd>/farewells type ``type:<Normal/Embed>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/farewells type ``type:Embed``</kbd>.

> 如果使用者關閉嵌入內容，他將看不到訊息.
{.is-danger}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/farewells reset</kbd>.

**範例**: <kbd>/farewells reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
