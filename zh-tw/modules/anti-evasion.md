---
title: Anti Evasion
description:
published: true
date: Fri Nov 12 2021 15:43:29 GMT+0000 (Coordinated Universal Time)
dateCreated: Fri Nov 12 2021 15:43:29 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組會把想要繞過處罰機制的人抓出來，並恢復他們的處罰.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項進階權限： ``BAN_MEMBERS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有此項權限： ``BAN_MEMBERS``. **^1^**

**^1^** 如果要滿足此要求，模組設置將被重置.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>/anti-evasion enable</kbd>.

**範例**: <kbd>/anti-evasion enable</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/anti-evasion disable</kbd>.

**範例**: <kbd>/anti-evasion disable</kbd>.

# 設定要處理的原則的步驟

## **步驟 1**: 設定原則

如果要 設定原則 ，您必須執行以下指令：<kbd>/anti-evasion action ``action:<動作>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 你可以點擊 **[這個連結](https://wiki.filobot.xyz/zh-tw/modules/actions-list)** 來查看 Filo 支援的處罰.
{.is-info}

**範例**: <kbd>/anti-evasion action ``action:Temporarily ban the user`` ``time:7d``</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/anti-evasion reset</kbd>.

**範例**: <kbd>/anti-evasion reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
