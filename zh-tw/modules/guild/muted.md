---
title: Muted Role
description:
published: true
date: Sun Oct 24 2021 12:00:53 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:00:53 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以將成員禁言 (需先設定禁言身分組).

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項進階權限： ``VIEW_CHANNEL`` 和 ``MANAGE_ROLES``.

- Filo 需要要此項基礎權限: ``VIEW_CHANNEL``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 禁言身分組的步驟

## **步驟 1**: 建立禁言身分組

如果要 建立禁言身分組 ，您必須執行以下指令：<kbd>/core roles muted</kbd>.

**範例**: <kbd>/core roles muted</kbd>.

# 綁定已經存在的身分組的步驟

## **步驟 1**: 綁定禁言身分組

如果要 綁定禁言身分組 ，您必須執行以下指令：<kbd>/core roles muted ``role:<@身分組/身分組 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/core roles muted ``role:@Muted``</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/core roles reset</kbd>.

**範例**: <kbd>/core roles reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
