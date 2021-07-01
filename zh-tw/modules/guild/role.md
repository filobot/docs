---
title: Setup a Role
description:
published: true
date: Wed Jun 30 2021 12:22:56 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Jun 30 2021 12:22:56 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

該模組將允許您在 Filo 中配置身分組的屬性和權限.

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要以下基礎權限: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` 和 ``ADD_REACTIONS``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

- 你需要取代<kbd>f!</kbd> 成你設定的 prefix 。如果你需要更換它的教學，請 **[點擊這裡](https://wiki.filobot.xyz/zh-tw/modules/prefix)**.

# 配置身分組權限的步驟

配置身分組的權限將可以使您更靈活地在您的伺服器上授予特定身分組權限.

## 設定數字位域權限的步驟

## **步驟 1**: 為身分組設定特定的權限

如果要 為身分組設定特定的權限 ，您必須執行以下指令：<kbd>f!config guild role custom \<@身分組/身分組 ID> permissions set \<數字位域></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> **[點擊這裡](https://filobot.xyz/calculator)**以查看 Filo 的權限計算機.
{.is-info}

**範例**: <kbd>f!config guild role custom @Moderators permissions set 147443</kbd>.

> **[點擊這裡](https://wiki.filobot.xyz/zh-tw/modules/guild/role/preset-packages)**以查看預設的權限.
{.is-info}

## 新增權限到身分組的步驟

## **步驟 1**: 新增權限到身分組

如果要 新增權限到身分組 ，您必須執行以下指令：<kbd>f!config guild role custom \<@身分組/身分組 ID> permissions add \<權限></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> **[點擊這裡](https://filobot.xyz/calculator)**以查看 Filo 的權限計算機.
{.is-info}

**範例**: <kbd>f!config guild role custom @Moderators permissions add VIEW_CASES</kbd>.

> 您也可以通過運行以下指令查看完整的權限列表: **f!config guild role custom \<@身分組/身分組 ID> permissions list**.
{.is-info}

## 移除身分組權限的步驟

## **步驟 1**: 移除身分組權限

如果要 移除身分組權限 ，您必須執行以下指令：<kbd>f!config guild role custom \<@身分組/身分組 ID> permissions remove \<權限></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

> **[點擊這裡](https://filobot.xyz/calculator)**以查看 Filo 的權限計算機.
{.is-info}

**範例**: <kbd>f!config guild role custom @Moderators permissions remove VIEW_CASES</kbd>.

> 您也可以通過運行以下指令查看完整的權限列表: **f!config guild role custom \<@身分組/身分組 ID> permissions list**.
{.is-info}

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>f!config guild reset \<Roles></kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>f!config guild reset roles</kbd>.

> 你必須謹慎考慮此操作。如果重置，您將無法恢復之前的設定.
{.is-danger}
