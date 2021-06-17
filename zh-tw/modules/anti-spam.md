---
title: Anti Spam
description:
published: true
date: Mon Jun 14 2021 13:21:56 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 14 2021 13:21:56 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以自動刪除洗版訊息和警告洗版發送者.

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

如果要 啟用模組 ，您必須執行以下指令：<kbd>f!config anti-spam enable</kbd>.

**範例**: <kbd>f!config anti-spam enable</kbd>.

> 這個模組可以補充 **[Auto Moderation](https://wiki.filobot.xyz/zh-Tw/modules/auto-moderation)**.
{.is-success}

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>f!config anti-spam disable</kbd>.

**範例**: <kbd>f!config anti-spam disable</kbd>.

# 新增例外頻道的步驟

## **步驟 1**: 新增一個例外的頻道

如果要 新增一個例外的頻道 ，您必須執行以下指令：<kbd>f!config anti-spam allow channel add \<#頻道/頻道 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-spam allow channel add #spam-allowed</kbd>.

> 如題所說，那些在本頻道洗版的人不會受到任何處罰.
{.is-warning}

# 移除例外頻道的步驟

## **步驟 1**: 移除例外頻道

如果要 移除例外頻道 ，您必須執行以下指令：<kbd>f!config anti-spam allow channel remove \<#頻道/頻道 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-spam allow channel remove #general</kbd>.

> 如題所說，那些在本頻道洗版的人將會重新受到處罰.
{.is-warning}

# 新增例外頻道的步驟

## **步驟 1**: 新增例外身分組

如果要 新增例外身分組 ，您必須執行以下指令：<kbd>f!config anti-spam allow role add \<@身分組/身分組 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-spam allow role add @Moderators</kbd>.

> 如題所說，那些擁有此身分組的人將不會受到洗版處罰.
{.is-warning}

# 移除例外身分組的步驟

## **步驟 1**: 移除例外身分組

如果要 移除例外身分組 ，您必須執行以下指令：<kbd>f!config anti-spam allow role remove \<@身分組/身分組 ID></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-spam allow role remove @Moderators</kbd>.

> 如題所說，那些擁有此身分組的人將會重新受到洗版處罰.
{.is-warning}

# 設定數量和時間的步驟

## **步驟 1**: 設定數量和時間

如果要 設定數量和時間 ，您必須執行以下指令：<kbd>f!config anti-spam set duplicates threshold \<進入點></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-spam set duplicates threshold 4</kbd>

> 數值必須大於 **2**.
{.is-warning}

## **步驟 2**: 為相同的訊息設定洗版最低時間

如果要 為相同的訊息設定洗版最低時間 ，您必須執行以下指令：<kbd>f!config anti-spam set duplicates time \<時間></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-spam set duplicates time 5s</kbd>

> 指令有效的持續時間必須在 **3 秒** 到 **60 秒** 之間 .
{.is-warning}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config anti-spam reset \<Duplicates/Roles/Channels></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config anti-spam reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
