---
title: 語言
description:
published: true
date: Mon Jun 14 2021 13:21:19 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:21:19 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組允許您更改或重置 Filo 的語言。注意！這將影響所有的指令、模組和系統.

# 入門

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR`` .

- 你需要取代 <kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請**[點擊這裡](https://wiki.filobot.xyz/zh-Tw/modules/prefix)**.

# 設定語言的步驟

## **步驟 1**: 設定語言

如果要 設定語言 ，您必須執行以下指令：<kbd>f!config language set \<語言名稱></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config language set english</kbd>.

> 點擊**[這個連結](https://wiki.filobot.xyz/zh-Tw/modules/language/list)**來查看 Filo 所支援的語言.
{.is-info}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config language reset</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config language reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
