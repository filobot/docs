---
title: Welcome Role
description:
published: true
date: Mon Jun 14 2021 13:22:45 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:22:45 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以為剛進入伺服器的人設定一個身分組.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項進階權限： ``MANAGE_ROLES``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

- 你需要取代<kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請 **[點擊這裡](https://wiki.filobot.xyz/zh-Tw/modules/prefix)**.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有此項權限： ``MANAGE_ROLES``. **^1^**

- 如果 Filo 的身分組位階低於這個使用者. **^2^**

- 如果 Filo 的身分組位階等於這個使用者. **^2^**

- 如果 Filo 的身分組位階低於這個使用者. **^2^**

- 如果 Filo 的身分組位階等於這個使用者. **^2^**

**^1^** 如果要滿足此要求，模組設置將被重置.

**^2^** 如果滿足此要求或以下要求，則該模組將無法工作.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>f!config welcomes role enable</kbd>.

**範例**: <kbd>f!config welcomes role enable</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>f!config welcomes role disable</kbd>.

**範例**: <kbd>f!config welcomes role disable</kbd>.

# 設定預設身分組的步驟

## **步驟 1**: 設定預設身分組

如果要 設定預設身分組 ，您必須執行以下指令：<kbd>f!config welcomes role set \<@身分組/身分組 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config welcomes role set @Newbies</kbd>.

> Filo 的身分組位階必須高於所選身分組，並且所選身分組不能是管理層級.
{.is-danger}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config welcomes role reset \<Role></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config welcomes role reset role</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
