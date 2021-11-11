---
title: Anti External Links
description:
published: true
date: Thu Nov 11 2021 16:19:09 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Nov 11 2021 16:19:09 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組將可以刪除指定的外部鏈接消息並警告發送者.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

> 所有 Discord 的連結將會繞過這個模組.
{.is-warning}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項進階權限： ``MANAGE_MESSAGES``.

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

- 你需要取代<kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請 **[點擊這裡](https://wiki.filobot.xyz/zh-tw/modules/prefix)**.

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

如果要 啟用模組 ，您必須執行以下指令：<kbd>f!config anti-external-links enable</kbd>.

**範例**: <kbd>f!config anti-external-links enable</kbd>.

> 這個模組可以補充 **[Auto Moderation](https://wiki.filobot.xyz/zh-tw/modules/auto-moderation)**.
{.is-success}

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>f!config anti-external-links disable</kbd>.

**範例**: <kbd>f!config anti-external-links disable</kbd>.

# 加入指定 URL 的步驟

## 將子網域添加到允許清單的步驟

### **步驟 1**: 添加子網域到允許清單

如果要 添加子網域到允許清單 ，您必須執行以下指令：<kbd>f!config anti-external-links allow url add \<URL></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>f!config anti-external-links allow url add https://wiki.filobot.xyz</kbd>.

> 您可以透過用星號替換子網域，來指定所有子網域.
> **範例**: https://*.filobot.xyz.
{.is-info}

> 如本文所述，您可以通過將子網域和路徑替換為星號使其子域的所有鏈接都有效.
> **範例**: https://*.filobot.xyz/*.
{.is-success}

## 將網域添加到允許清單的步驟

### **步驟 1**: 添加網域到允許清單

如果要 添加網域到允許清單 ，您必須執行以下指令：<kbd>f!config anti-external-links allow url add \<URL></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>f!config anti-external-links allow url add https://filobot.xyz</kbd>.

> 如本文所述，您可以通過將子網域和路徑替換為星號使其子域的所有鏈接都有效.
> **範例**: https://*.filobot.xyz/*.
{.is-success}

## 將路徑添加到允許清單的步驟

### **步驟 1**: 添加路徑到允許清單

如果要 添加路徑到允許清單 ，您必須執行以下指令：<kbd>f!config anti-external-links allow url add \<URL></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>f!config anti-external-links allow url add https://wiki.filobot.xyz/en/home</kbd>.

> 您可以透過用星號替換路徑，來指定所有的路徑.
> **範例**: https://filobot.xyz/*.
{.is-info}

> 如本文所述，您可以通過將子網域和路徑替換為星號使其子域的所有鏈接都有效.
> **範例**: https://*.filobot.xyz/*.
{.is-success}

## 從允許清單中移除 URL 的步驟

### **步驟 1**: 移除允許清單中的 URL

如果要 移除允許清單中的 url ，您必須執行以下指令：<kbd>f!config anti-external-links allow url remove \<URL></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> URL 必須啟用 **HTTPS** 協議，否則 URL 將無法添加至允許列表.
{.is-danger}

**範例**: <kbd>f!config anti-external-links allow url remove https://filobot.xyz</kbd>.

# 新增例外頻道的步驟

## **步驟 1**: 新增一個例外的頻道

如果要 新增一個例外的頻道 ，您必須執行以下指令：<kbd>f!config anti-external-links allow channel add \<#頻道/頻道 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-external-links allow channel add #spam-allowed</kbd>.

> 如題所說，那些在本頻道洗版的人不會受到任何處罰.
{.is-warning}

# 移除例外頻道的步驟

## **步驟 1**: 移除例外頻道

如果要 移除例外頻道 ，您必須執行以下指令：<kbd>f!config anti-external-links allow channel remove \<#頻道/頻道 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-external-links allow channel remove #general</kbd>.

> 如題所說，那些在本頻道洗版的人將會重新受到處罰.
{.is-warning}

# 新增例外頻道的步驟

## **步驟 1**: 新增例外身分組

如果要 新增例外身分組 ，您必須執行以下指令：<kbd>f!config anti-external-links allow role add \<@身分組/身分組 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-external-links allow role add @Moderators</kbd>.

> 如題所說，那些擁有此身分組的人將不會受到洗版處罰.
{.is-warning}

# 移除例外身分組的步驟

## **步驟 1**: 移除例外身分組

如果要 移除例外身分組 ，您必須執行以下指令：<kbd>f!config anti-external-links allow role remove \<@身分組/身分組 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-external-links allow role remove @Moderators</kbd>.

> 如題所說，那些擁有此身分組的人將會重新受到洗版處罰.
{.is-warning}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config anti-external-links reset \<Allow/Action></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-external-links reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
