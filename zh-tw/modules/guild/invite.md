---
title: Guild Invite
description:
published: true
date: Mon Jun 14 2021 13:23:06 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:23:06 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以讓你設定一個永久的伺服器邀請.

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``CREATE_INSTANT_INVITE``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

- 你需要取代<kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請 **[點擊這裡](https://wiki.filobot.xyz/zh-Tw/modules/prefix)**.

# 如何在頻道裡建立永久的伺服器邀請

## **步驟 1**: 在頻道裡建立永久的邀請

如果要 在頻道裡建立永久的邀請 ，您必須執行以下指令：<kbd>f!config guild invite create \<#頻道/頻道 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config guild invite create #general</kbd>.

> Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``CREATE_INSTANT_INVITE``.
{.is-danger}

# 從頻道設定現有的邀請的步驟

## **步驟 1**: 從頻道設定現有的邀請

如果要 從頻道設定現有的邀請 ，您必須執行以下指令：<kbd>f!config guild invite set \<邀請連結/邀請代碼></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config guild invite set https://discord.gg/xHhBWhT</kbd>.

> 你設置的邀請必須來自同一個伺服器.
{.is-danger}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config guild reset \<Invite></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config guild reset invite</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
