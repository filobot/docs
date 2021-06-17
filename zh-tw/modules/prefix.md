---
title: Prefix
description:
published: true
date: Mon Jun 14 2021 13:20:58 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:20:58 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組允許您更改或重置 Filo 的 Prefix.

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR`` .

- 你需要取代 <kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請**[點擊這裡](https://wiki.filobot.xyz/zh-Tw/modules/prefix)**.

# 設定新 Prefix的步驟

## **步驟 1**: 設定新的 Prefix

如果要 設定新的 prefix ，您必須執行以下指令：<kbd>f!config prefix set \<Prefix></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config prefix set f!</kbd>.

> Filo 不支援更改斜線字首 .
{.is-danger}

> Prefix 必須小於 **2** 個字 .
{.is-warning}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config prefix reset</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config prefix reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
