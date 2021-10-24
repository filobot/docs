---
title: Setup a Role
description:
published: true
date: Sun Oct 24 2021 12:17:54 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:17:54 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to configure the properties and permissions of a role in Filo.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following basic permission: ``VIEW_CHANNEL``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Steps to configure role permissions

Configuring the permissions of a role will allow you to make more flexible the permissions that you grant on the server to a specific role.

## Steps to set the permissions bitfield to a role

## **Step 1**: Set the permissions bitfield to a role

To set the permissions bitfield to a role you must execute the following command: <kbd>/core roles permissions ``role:<@Role/Role ID>`` ``permission:<Bitfield>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can view Filo's permissions calculator by **[clicking here](https://filobot.xyz/calculator)**.
{.is-info}

**Example**: <kbd>/core roles permissions ``role:@Moderators`` ``permission:147443``</kbd>.

> You can check our Preset Permission Packages by **[clicking here](https://wiki.filobot.xyz/en/modules/guild/role/preset-packages)**.
{.is-info}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/core roles reset</kbd>.

**Example**: <kbd>/core roles reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
