---
title: Logging
description:
published: true
date: Wed Nov 10 2021 15:54:59 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:54:59 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

This module will allow you to receive the audit records through messages on a specific channel.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``MANAGE_WEBHOOKS``.

- Filo 需要要此項基礎權限: ``VIEW_CHANNEL``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Webhook 被刪除. **^1^**

- 如果 Webhook 已經跟其它模組共用 (e.g. reports). **^2^**

**^1^** 如果要滿足此要求，模組設置將被重置.

**^2^** 如果滿足此要求或以下要求，則該模組將無法工作.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>/logging enable</kbd>.

**範例**: <kbd>/logging enable</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/logging disable</kbd>.

**範例**: <kbd>/logging disable</kbd>.

# 設定日誌頻道的步驟

## **步驟 1**: 設定日誌頻道

如果要 設定日誌頻道 ，您必須執行以下指令：<kbd>/logging channel ``channel:<#頻道/頻道 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/logging channel ``channel:#server-logs``</kbd>.

> Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``MANAGE_WEBHOOKS``.
{.is-danger}

> 您設定的頻道需要是不公開且伺服器管理員可以看到的.
{.is-success}

# 配置模組事件的步驟

## 啟用事件的步驟

### **步驟 1**: 啟用事件

如果要 啟用事件 ，您必須執行以下指令：<kbd>/logging events ``action:Enable``</kbd>.

**範例**: <kbd>/logging events ``action:Enable``</kbd>.

## 停用事件的步驟

### **步驟 1**: 停用事件

如果要 停用事件 ，您必須執行以下指令：<kbd>/logging events ``action:Disable``</kbd>.

**範例**: <kbd>/logging events ``action:Disable``</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/logging reset</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/logging reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
