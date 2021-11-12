---
title: Anti Invites
description:
published: true
date: Fri Nov 12 2021 17:33:41 GMT+0000 (Coordinated Universal Time)
dateCreated: Fri Nov 12 2021 17:33:41 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

This module will sanction users who spam invitations from servers other than yours.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

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

如果要 啟用模組 ，您必須執行以下指令：<kbd>/anti-invites enable</kbd>.

**範例**: <kbd>/anti-invites enable</kbd>.

> 這個模組可以補充 **[Auto Moderation](https://wiki.filobot.xyz/zh-tw/modules/auto-moderation)**.
{.is-success}

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/anti-invites disable</kbd>.

**範例**: <kbd>/anti-invites disable</kbd>.

# Steps to enable Filo server bypass

## **步驟 1**: Enable Filo server bypass

如果要 enable filo server bypass ，您必須執行以下指令：<kbd>/anti-invites filo ``action:Enable``</kbd>.

**範例**: <kbd>/anti-invites filo ``action:Enable``</kbd>.

# Steps to disable Filo server bypass

## **步驟 1**: Disable Filo server bypass

如果要 disable filo server bypass ，您必須執行以下指令：<kbd>/anti-invites filo ``action:Disable``</kbd>.

**範例**: <kbd>/anti-invites filo ``action:Disable``</kbd>.

# Steps to enable Discord official servers bypass

## **步驟 1**: Enable Discord official servers bypass

如果要 enable discord official servers bypass ，您必須執行以下指令：<kbd>/anti-invites discord ``action:Enable``</kbd>.

**範例**: <kbd>/anti-invites discord ``action:Enable``</kbd>.

# Steps to disable Discord official servers bypass

## **步驟 1**: Disable Discord official servers bypass

如果要 disable discord official servers bypass ，您必須執行以下指令：<kbd>/anti-invites discord ``action:Disable``</kbd>.

**範例**: <kbd>/anti-invites discord ``action:Disable``</kbd>.

# Steps to set a sanction

## **步驟 1**: Set a sanction

如果要 set a sanction ，您必須執行以下指令：<kbd>/anti-invites action ``action:<動作>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 你可以點擊 **[這個連結](https://wiki.filobot.xyz/zh-tw/modules/actions-list)** 來查看 Filo 支援的處罰.
{.is-info}

**範例**: <kbd>/anti-invites action ``action:Temporarily mute the user`` ``time:1h``</kbd>.

# 新增例外伺服器名單的步驟

## **步驟 1**: 新增例外伺服器至名單中

如果要 新增例外伺服器至名單中 ，您必須執行以下指令：<kbd>/anti-invites guild ``action:Add`` ``guild:<伺服器 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-invites guild ``action:Add`` ``guild:123456789123456789``</kbd>.

> 點**[這裡](https://support.discord.com/hc/en-us/articles/206346498)**來查看Discord官方的說明
{.is-info}

# 從名單移除例外伺服器的步驟

## **步驟 1**: 移除例外伺服器

如果要 移除例外伺服器 ，您必須執行以下指令：<kbd>/anti-invites guild ``action:Remove`` ``guild:<伺服器 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-invites guild ``action:Remove`` ``guild:123456789123456789``</kbd>.

> 點**[這裡](https://support.discord.com/hc/en-us/articles/206346498)**來查看Discord官方的說明
{.is-info}

# 新增例外頻道的步驟

## **步驟 1**: 新增一個例外的頻道

如果要 新增一個例外的頻道 ，您必須執行以下指令：<kbd>/anti-invites channel ``action:Add`` ``channel:<#頻道/頻道 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-invites channel ``action:Add`` ``channel:#spam-allowed``</kbd>.

> If you add a channel to the allow list, this module will not work on that channel.
{.is-warning}

# 移除例外頻道的步驟

## **步驟 1**: 移除例外頻道

如果要 移除例外頻道 ，您必須執行以下指令：<kbd>/anti-invites channel ``action:Remove`` ``channel:<#頻道/頻道 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-invites channel ``action:Remove`` ``channel:#general``</kbd>.

> If you remove a channel from the allowed list, this module will work on that channel.
{.is-warning}

# 新增例外身分組的步驟

## **步驟 1**: 新增例外身分組

如果要 新增例外身分組 ，您必須執行以下指令：<kbd>/anti-invites role ``action:Add`` ``role:<@身分組/身分組 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-invites role ``action:Add`` ``role:@Moderators``</kbd>.

> If you add a role to the allowed list, anyone who has this role will be exempt from the operation of this module.
{.is-warning}

# 移除例外身分組的步驟

## **步驟 1**: 移除例外身分組

如果要 移除例外身分組 ，您必須執行以下指令：<kbd>/anti-invites role ``action:Remove`` ``role:<@身分組/身分組 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/anti-invites role ``action:Remove`` ``role:@Moderators``</kbd>.

> If you remove a role from the allowed list, anyone who has this role will no longer be exempt from the operation of this module.
{.is-warning}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/anti-invites reset</kbd>.

**範例**: <kbd>/anti-invites reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
