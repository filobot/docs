---
title: Anti External Links
description:
published: true
date: Fri Nov 12 2021 17:35:10 GMT+0000 (Coordinated Universal Time)
dateCreated: Fri Nov 12 2021 17:35:10 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

This module will sanction those users who send some type of link in their message.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

> 所有 Discord 的連結將會繞過這個模組.
{.is-warning}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` 和 ``MANAGE_MESSAGES``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有以下權限： ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` 和 ``MANAGE_MESSAGES``. **^1^**

- 如果使用者沒有這個權限： ``ADMINISTRATOR``. **^2^**

- 如果使用者沒有這個權限： ``MANAGE_GUILD``. **^2^**

- 如果使用者沒有這個權限： ``EVADE_SANCTIONS``. **^2^**

- 如果 Filo 的身分組位階低於這個使用者. **^2^**

- 如果 Filo 的身分組位階等於這個使用者. **^2^**

**^1^** 如果要滿足此要求，模組設置將被重置.

**^2^** 如果滿足此要求或以下要求，則該模組將無法工作.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>/anti-external-links enable</kbd>.

**範例**: <kbd>/anti-external-links enable</kbd>.

> 這個模組可以補充 **[Auto Moderation](https://wiki.filobot.xyz/zh-tw/modules/auto-moderation)**.
{.is-success}

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/anti-external-links disable</kbd>.

**範例**: <kbd>/anti-external-links disable</kbd>.

# 加入指定 URL 的步驟

## 將子網域添加到允許清單的步驟

### **步驟 1**: 添加子網域到允許清單

如果要 添加子網域到允許清單 ，您必須執行以下指令：<kbd>/anti-external-links link ``action:Add`` ``link:<URL>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>/anti-external-links link ``action:Add`` ``link:https://wiki.filobot.xyz``</kbd>.

> 您可以透過用星號替換子網域，來指定所有子網域.
> **範例**: https://*.filobot.xyz.
{.is-info}

> 如本文所述，您可以通過將子網域和路徑替換為星號使其子域的所有鏈接都有效.
> **範例**: https://*.filobot.xyz/*.
{.is-success}

## 將網域添加到允許清單的步驟

### **步驟 1**: 添加網域到允許清單

如果要 添加網域到允許清單 ，您必須執行以下指令：<kbd>/anti-external-links link ``action:Add`` ``link:<URL>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>/anti-external-links link ``action:Add`` ``link:https://filobot.xyz``</kbd>.

> 如本文所述，您可以通過將子網域和路徑替換為星號使其子域的所有鏈接都有效.
> **範例**: https://*.filobot.xyz/*.
{.is-success}

## 將路徑添加到允許清單的步驟

### **步驟 1**: 添加路徑到允許清單

如果要 添加路徑到允許清單 ，您必須執行以下指令：<kbd>/anti-external-links link ``action:Add`` ``link:<URL>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>/anti-external-links link ``action:Add`` ``link:https://wiki.filobot.xyz/en/home``</kbd>.

> 您可以透過用星號替換路徑，來指定所有的路徑.
> **範例**: https://filobot.xyz/*.
{.is-info}

> 如本文所述，您可以通過將子網域和路徑替換為星號使其子域的所有鏈接都有效.
> **範例**: https://*.filobot.xyz/*.
{.is-success}

## 從允許清單中移除 URL 的步驟

### **步驟 1**: 移除允許清單中的 URL

如果要 移除允許清單中的 url ，您必須執行以下指令：<kbd>/anti-external-links link ``action:Remove`` ``link:<URL>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>/anti-external-links link ``action:Remove`` ``link:https://filobot.xyz``</kbd>.

# Steps to enable bypassing of Filo links

## **步驟 1**: Enable bypassing of Filo links

如果要 enable bypassing of filo links ，您必須執行以下指令：<kbd>/anti-external-links filo ``action:Enable``</kbd>.

**範例**: <kbd>/anti-external-links filo ``action:Enable``</kbd>.

# Steps to disable bypassing of Filo links

## **步驟 1**: Disable bypassing of Filo links

如果要 disable bypassing of filo links ，您必須執行以下指令：<kbd>/anti-external-links filo ``action:Disable``</kbd>.

**範例**: <kbd>/anti-external-links filo ``action:Disable``</kbd>.

# Steps to enable bypassing of Discord links

## **步驟 1**: Enable bypassing of Discord links

如果要 enable bypassing of discord links ，您必須執行以下指令：<kbd>/anti-external-links discord ``action:Enable``</kbd>.

**範例**: <kbd>/anti-external-links discord ``action:Enable``</kbd>.

# Steps to disable bypassing of Discord links

## **步驟 1**: Disable bypassing of Discord links

如果要 disable bypassing of discord links ，您必須執行以下指令：<kbd>/anti-external-links discord ``action:Disable``</kbd>.

**範例**: <kbd>/anti-external-links discord ``action:Disable``</kbd>.

# Steps to set a sanction

## **步驟 1**: Set a sanction

如果要 set a sanction ，您必須執行以下指令：<kbd>/anti-external-links action ``action:<動作>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 你可以點擊 **[這個連結](https://wiki.filobot.xyz/zh-tw/modules/actions-list)** 來查看 Filo 支援的處罰.
{.is-info}

**範例**: <kbd>/anti-external-links action ``action:Temporarily mute the user`` ``time:1h``</kbd>.

# 新增例外頻道的步驟

## **步驟 1**: 新增一個例外的頻道

如果要 新增一個例外的頻道 ，您必須執行以下指令：<kbd>/anti-external-links channel ``action:Add`` ``channel:<#頻道/頻道 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-external-links channel ``action:Add`` ``channel:#spam-allowed``</kbd>.

> If you add a channel to the allow list, this module will not work on that channel.
{.is-warning}

# 移除例外頻道的步驟

## **步驟 1**: 移除例外頻道

如果要 移除例外頻道 ，您必須執行以下指令：<kbd>/anti-external-links channel ``action:Remove`` ``channel:<#頻道/頻道 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-external-links channel ``action:Remove`` ``channel:#general``</kbd>.

> If you remove a channel from the allowed list, this module will work on that channel.
{.is-warning}

# 新增例外身分組的步驟

## **步驟 1**: 新增例外身分組

如果要 新增例外身分組 ，您必須執行以下指令：<kbd>/anti-external-links role ``action:Add`` ``role:<@身分組/身分組 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-external-links role ``action:Add`` ``role:@Moderators``</kbd>.

> If you add a role to the allowed list, anyone who has this role will be exempt from the operation of this module.
{.is-warning}

# 移除例外身分組的步驟

## **步驟 1**: 移除例外身分組

如果要 移除例外身分組 ，您必須執行以下指令：<kbd>/anti-external-links role ``action:Remove`` ``role:<@身分組/身分組 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-external-links role ``action:Remove`` ``role:@Moderators``</kbd>.

> If you remove a role from the allowed list, anyone who has this role will no longer be exempt from the operation of this module.
{.is-warning}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/anti-external-links reset</kbd>.

**範例**: <kbd>/anti-external-links reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
