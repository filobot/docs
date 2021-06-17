---
title: 停用指令
description:
published: true
date: Mon Jun 14 2021 13:23:21 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:23:21 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組將允許您停用您不會用到或不想使用的指令.

# 入門

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` 和 ``USE_EXTERNAL_EMOJIS``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR`` .

- 你需要取代 <kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請**[點擊這裡](https://wiki.filobot.xyz/zh-Tw/modules/prefix)**.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有以下權限： ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, 和 ``USE_EXTERNAL_EMOJIS``. **^1^**

**^1^** 如果要滿足此要求，模組設置將被重置.

# 停用指令的步驟

## **步驟 1**: 停用指令

如果要 停用指令 ，您必須執行以下指令：<kbd>f!config commands disable \<指令></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config commands disable ping</kbd>.

# 啟用指令的步驟

## **步驟 1**: 啟用指令

如果要 啟用指令 ，您必須執行以下指令：<kbd>f!config commands enable \<指令></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config commands enable ping</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config commands reset \<Disabled></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config commands reset disabled</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
