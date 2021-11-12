---
title: Disable commands
description:
published: true
date: Sun Oct 24 2021 11:54:26 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 11:54:26 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# 關於本模組

This module will allow you to disable Filo commands for all members of the server (including you).

# Getting Started

在繼續之前，您必須考慮一系列可能影響您執行的任何操作因素:

- Filo 需要要此項基礎權限: ``VIEW_CHANNEL``.

- 在執行本主題的指令前，你需要此項權限： ``ADMINISTRATOR``.

# 停用指令的步驟

## **步驟 1**: 停用指令

如果要 停用指令 ，您必須執行以下指令：<kbd>/commands disable ``target:Command`` ``value:<指令>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/commands disable ``taarget:Command`` ``value:ping``</kbd>.

# 啟用指令的步驟

## **步驟 1**: 啟用指令

如果要 啟用指令 ，您必須執行以下指令：<kbd>/commands enable ``target:Command`` ``value:<指令>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/commands enable ``target:Command`` ``value:ping``</kbd>.

# Steps to disable a category of commands

## **步驟 1**: Disable a category of commands

如果要 disable a category of commands ，您必須執行以下指令：<kbd>/commands disable ``target:Category`` ``value:<Category>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/commands disable ``taarget:Category`` ``value:Core``</kbd>.

# Steps to enable a category of commands

## **步驟 1**: Enable a category of commands

如果要 enable a category of commands ，您必須執行以下指令：<kbd>/commands enable ``target:Category`` ``value:<Category>``</kbd>.

> 當您在打指令時，請勿包含 ``<>``.
{.is-warning}

**範例**: <kbd>/commands enable ``target:Category`` ``value:Core``</kbd>.

# 重置模組的步驟

## **步驟 1**: 重置模組

如果要 重置模組 ，您必須執行以下指令：<kbd>/commands reset</kbd>.

**範例**: <kbd>/commands reset</kbd>.