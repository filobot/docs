---
title: Welcome Role
description:
published: true
date: Sun Oct 24 2021 14:42:56 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:42:56 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以為剛進入伺服器的人設定一個身分組.

> 我們強烈建議你使用本模組來管理社群.
{.is-success}

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項進階權限： ``MANAGE_ROLES``.

- Filo 需要要此項基礎權限: ``VIEW_CHANNEL``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 常見錯誤

如果在使用本模組時，如果你沒有開啟下列敘述，你將會得到錯誤:

- 如果 Filo 沒有此項權限： ``MANAGE_ROLES``. **^1^**

- 如果 Filo 的身分組位階低於這個使用者. **^2^**

- 如果 Filo 的身分組位階等於這個使用者. **^2^**

- 如果 Filo 的身分組位階低於這個使用者. **^2^**

- 如果 Filo 的身分組位階等於這個使用者. **^2^**

**^1^** 如果要滿足此要求，模組設置將被重置.

**^2^** 如果滿足此要求或以下要求，則該模組將無法工作.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>/welcomes enable ``module:Welcome role``</kbd>.

**範例**: <kbd>/welcomes enable ``module:Welcome role``</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/welcomes disable ``module:Welcome role``</kbd>.

**範例**: <kbd>/welcomes disable ``module:Welcome role``</kbd>.

# 設定預設身分組的步驟

## **步驟 1**: 設定預設身分組

如果要 設定預設身分組 ，您必須執行以下指令：<kbd>/welcomes role ``role:<@身分組/身分組 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/welcomes role ``role:@Newbies``</kbd>.

> Filo 的身分組位階必須高於所選身分組，並且所選身分組不能是管理層級.
{.is-danger}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/welcomes reset</kbd>.

**範例**: <kbd>/welcomes reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
