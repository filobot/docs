---
title: Member Counter Nickname
description:
published: true
date: Mon Jun 14 2021 13:22:55 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:22:55 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以把 Filo 的名稱更改為成員數量.

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項進階權限： ``CHANGE_NICKNAME``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

- 你需要取代<kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請 **[點擊這裡](https://wiki.filobot.xyz/zh-Tw/modules/prefix)**.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有此項權限： ``CHANGE_NICKNAME``. **^1^**

**^1^** 如果要滿足此要求，模組設置將被重置.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>f!config member-counter nickname enable</kbd>.

**範例**: <kbd>f!config member-counter nickname enable</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>f!config member-counter nickname disable</kbd>.

**範例**: <kbd>f!config member-counter nickname disable</kbd>.

# 設定暱稱的步驟

## **步驟 1**: 把 Filo 的名稱更改為成員數量

如果要 把 filo 的名稱更改為成員數量 ，您必須執行以下指令：<kbd>f!config member-counter nickname set \<名稱 {members}></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 頻道名稱必須小於 **28 個字**，而且需要包含 `{members}` 在您的新名稱內.
{.is-danger}

**範例**: <kbd>f!config member-counter nickname set 👥 Members: {members}</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config member-counter reset \<Nickname></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config member-counter reset nickname</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
