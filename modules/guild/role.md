---
title: Setup a Role
description:
published: true
date: Wed Jun 30 2021 12:22:56 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Jun 30 2021 12:22:56 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to configure the properties and permissions of a role in Filo.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](https://wiki.filobot.xyz/en/modules/prefix)**.

# Steps to configure role permissions

Configuring the permissions of a role will allow you to make more flexible the permissions that you grant on the server to a specific role.

## Steps to set the permissions bitfield to a role

## **Step 1**: Set the permissions bitfield to a role

To set the permissions bitfield to a role you must execute the following command: <kbd>f!config guild role custom \<@Role/Role ID> permissions set \<Bitfield></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can view Filo's permissions calculator by **[clicking here](https://filobot.xyz/calculator)**.
{.is-info}

**Example**: <kbd>f!config guild role custom @Moderators permissions set 147443</kbd>.

> You can check our Preset Permission Packages by **[clicking here](https://wiki.filobot.xyz/en/modules/guild/role/preset-packages)**.
{.is-info}

## Steps to add a permission to a role

## **Step 1**: Add a permission to a role

To add a permission to a role you must execute the following command: <kbd>f!config guild role custom \<@Role/Role ID> permissions add \<Permission></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can view Filo's permissions calculator by **[clicking here](https://filobot.xyz/calculator)**.
{.is-info}

**Example**: <kbd>f!config guild role custom @Moderators permissions add VIEW_CASES</kbd>.

> You can see a complete list of permissions by running the following command: **f!config guild role custom \<@Role/Role ID> permissions list**.
{.is-info}

## Steps to remove a permission to a role

## **Step 1**: Remove a permission to a role

To remove a permission to a role you must execute the following command: <kbd>f!config guild role custom \<@Role/Role ID> permissions remove \<Permission></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can view Filo's permissions calculator by **[clicking here](https://filobot.xyz/calculator)**.
{.is-info}

**Example**: <kbd>f!config guild role custom @Moderators permissions remove VIEW_CASES</kbd>.

> You can see a complete list of permissions by running the following command: **f!config guild role custom \<@Role/Role ID> permissions list**.
{.is-info}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config guild reset \<Roles></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config guild reset roles</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
