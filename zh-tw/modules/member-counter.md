---
title: Member Counter
description:
published: true
date: Mon Jun 14 2021 13:21:05 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:21:05 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以讓您創建一個以成員數量命名的語音頻道.

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``MANAGE_CHANNELS``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

- 你需要取代<kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請 **[點擊這裡](https://wiki.filobot.xyz/zh-tw/modules/prefix)**.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>f!config member-counter enable</kbd>.

**範例**: <kbd>f!config member-counter enable</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>f!config member-counter disable</kbd>.

**範例**: <kbd>f!config member-counter disable</kbd>.

# 創建一個以成員數量命名的語音頻道的步驟

## **步驟 1**: 創建成員數頻道

如果要 創建成員數頻道 ，您必須執行以下指令：<kbd>f!config member-counter set channel \<頻道 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config member-counter set channel 123456789123456789</kbd>.

> 您選擇的頻道必須是 **語音頻道**，否則這個模組將不會正常運作.
{.is-warning}

> Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``MANAGE_CHANNELS``.
{.is-danger}

# 設定成員數頻道的名字的步驟

## **步驟 1**: 設定成員數頻道的名字

如果要 設定成員數頻道的名字 ，您必須執行以下指令：<kbd>f!config member-counter set name \<名稱 {members}></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 頻道名稱必須小於 **28 個字**，而且需要包含 `{members}` 在您的新名稱內.
{.is-danger}

**範例**: <kbd>f!config member-counter set name 👥 Members: {members}</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config member-counter reset \<Channel/Name/Nickname> (可填)</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config member-counter reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
