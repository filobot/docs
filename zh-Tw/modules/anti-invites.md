---
title: Anti Invites
description:
published: true
date: Mon Jun 14 2021 13:22:25 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:22:25 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以自動刪除其他伺服器的邀請和警告連結發送者.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項進階權限： ``MANAGE_MESSAGES``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR`` .

- 你需要取代 <kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請**[點擊這裡](https://wiki.filobot.xyz/zh-Tw/modules/prefix)**.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有以下權限： ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS`` 和 ``MANAGE_MESSAGES``. **^1^**

- 如果使用者沒有這個權限： ``ADMINISTRATOR``. **^2^**

- 如果使用者沒有這個權限： ``MANAGE_GUILD``. **^2^**

- 如果使用者沒有這個權限： ``MANAGE_MESSAGES``. **^2^**

- 如果使用者沒有這個權限： ``BAN_MEMBERS``. **^2^**

- 如果使用者沒有這個權限： ``KICK_MEMBERS``. **^2^**

- 如果 Filo 的身分組位階低於這個使用者. **^2^**

- 如果 Filo 的身分組位階等於這個使用者. **^2^**

**^1^** 如果要滿足此要求，模組設置將被重置.

**^2^** 如果滿足此要求或以下要求，則該模組將無法工作.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>f!config anti-invites enable</kbd>.

**範例**: <kbd>f!config anti-invites enable</kbd>.

> 這個模組可以補充 **[Auto Moderation](https://wiki.filobot.xyz/zh-Tw/modules/auto-moderation)**.
{.is-success}

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>f!config anti-invites disable</kbd>.

**範例**: <kbd>f!config anti-invites disable</kbd>.

# 新增例外伺服器名單的步驟

## **步驟 1**: 新增例外伺服器至名單中

如果要 新增例外伺服器至名單中 ，您必須執行以下指令：<kbd>f!config anti-invites allow add \<伺服器 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-invites allow add 123456789123456789</kbd>.

> 點**[這裡](https://support.discord.com/hc/en-us/articles/206346498)**來查看Discord官方的說明
{.is-info}

# 從名單移除例外伺服器的步驟

## **步驟 1**: 移除例外伺服器

如果要 移除例外伺服器 ，您必須執行以下指令：<kbd>f!config anti-invites allow remove \<伺服器 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-invites allow remove 123456789123456789</kbd>.

> 點**[這裡](https://support.discord.com/hc/en-us/articles/206346498)**來查看Discord官方的說明
{.is-info}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config anti-invites reset \<Allow> (可填)</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-invites reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
