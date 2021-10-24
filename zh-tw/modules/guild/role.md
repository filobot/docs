---
title: Setup a Role
description:
published: true
date: Sun Oct 24 2021 12:17:54 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:17:54 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

該模組將允許您在 Filo 中配置身分組的屬性和權限.

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項基礎權限: ``VIEW_CHANNEL``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 配置身分組權限的步驟

配置身分組的權限將可以使您更靈活地在您的伺服器上授予特定身分組權限.

## 設定數字位域權限的步驟

## **步驟 1**: 為身分組設定特定的權限

如果要 為身分組設定特定的權限 ，您必須執行以下指令：<kbd>/core roles permissions ``role:<@身分組/身分組 ID>`` ``permission:<數字位域>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> **[點擊這裡](https://filobot.xyz/calculator)**以查看 Filo 的權限計算機.
{.is-info}

**範例**: <kbd>/core roles permissions ``role:@Moderators`` ``permission:147443``</kbd>.

> **[點擊這裡](https://wiki.filobot.xyz/zh-tw/modules/guild/role/preset-packages)**以查看預設的權限.
{.is-info}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/core roles reset</kbd>.

**範例**: <kbd>/core roles reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
