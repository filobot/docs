---
title: Member Counter
description:
published: true
date: Wed Nov 10 2021 15:37:20 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:37:20 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

本模組可以讓您創建一個以成員數量命名的語音頻道.

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``MANAGE_CHANNELS``.

- Filo 需要要此項基礎權限: ``VIEW_CHANNEL``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 啟用本模組的步驟

## **步驟 1**: 啟用模組

如果要 啟用模組 ，您必須執行以下指令：<kbd>/member-counter enable ``module:Member counter channel``</kbd>.

**範例**: <kbd>/member-counter enable ``module:Member counter channel``</kbd>.

# 停用本模組的步驟

## **步驟 1**: 停用模組

如果要 停用模組 ，您必須執行以下指令：<kbd>/member-counter disable ``module:Member counter channel``</kbd>.

**範例**: <kbd>/member-counter disable ``module:Member counter channel``</kbd>.

# 創建一個以成員數量命名的語音頻道的步驟

## **步驟 1**: 創建成員數頻道

如果要 創建成員數頻道 ，您必須執行以下指令：<kbd>/member-counter channel ``channel:<頻道/頻道 ID>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/member-counter channel ``channel:123456789123456789``</kbd>.

> 您選擇的頻道必須是 **語音頻道**，否則這個模組將不會正常運作.
{.is-warning}

> Filo 需要以下進階權限: ``VIEW_CHANNEL`` 和 ``MANAGE_CHANNELS``.
{.is-danger}

# 設定成員數頻道的名字的步驟

## **步驟 1**: 設定成員數頻道的名字

如果要 設定成員數頻道的名字 ，您必須執行以下指令：<kbd>/member-counter name ``name:<名稱 {{members}}>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> 頻道名稱必須小於 **100 個字**，而且需要包含 `{members}` 在您的新名稱內.
{.is-danger}

**範例**: <kbd>/member-counter name ``name:👥 Members: {{members}}``</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/member-counter reset</kbd>.

**範例**: <kbd>/member-counter reset</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
