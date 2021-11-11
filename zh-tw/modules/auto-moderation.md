---
title: Auto Moderation
description:
published: true
date: Thu Nov 11 2021 17:05:42 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Nov 11 2021 17:05:42 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以讓你把有前科的人抓出來，並訂製他們的處罰.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``MANAGE_MESSAGES``, ``MANAGE_ROLES``, ``KICK_MEMBERS`` 和``BAN_MEMBERS`` (如果適用).

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES`` 和 ``EMBED_LINKS``.

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

如果要 啟用模組 ，您必須執行以下指令：<kbd>/auto-moderation enable</kbd>.

**範例**: <kbd>/auto-moderation enable</kbd>.

> 這個模組可以補充 **[Anti Evasion](https://wiki.filobot.xyz/zh-tw/modules/anti-evasion)**.
{.is-success}

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/auto-moderation disable</kbd>.

**範例**: <kbd>/auto-moderation disable</kbd>.

# Steps to add a level

## **步驟 1**: Add a level

如果要 add a level ，您必須執行以下指令：<kbd>/auto-moderation add ``warnings:<Warnings>`` ``action:動作``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 你可以點擊 **[這個連結](https://wiki.filobot.xyz/zh-tw/modules/actions-list)** 來查看 Filo 支援的處罰.
{.is-info}

**範例**: <kbd>/auto-moderation add ``warnings:3`` ``action:Kick the user``</kbd>.

# Steps to remove a level

## **步驟 1**: Remove a level

如果要 remove a level ，您必須執行以下指令：<kbd>/auto-moderation remove ``level:<Level>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/auto-moderation remove ``level:1``</kbd>.

# Steps to set the information of a level

## **步驟 1**: Set the information of a level

如果要 set the information of a level ，您必須執行以下指令：<kbd>/auto-moderation set ``level:<Level>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/auto-moderation set ``level:1`` ``warnings: 3`` ``action:Kick the user``</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/auto-moderation reset</kbd>.

**範例**: <kbd>/auto-moderation reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
