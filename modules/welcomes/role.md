---
title: Welcome Role
description:
published: true
date: Thu Jun 03 2021 14:35:59 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Jun 03 2021 14:35:59 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to grant a welcome role to new members.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permission: ``MANAGE_ROLES``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](en/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``MANAGE_ROLES`` permission. **^1^**

- If the position of the Filo's roles are lower than the user roles. **^2^**

- If the position of the Filo's roles are equal to the user roles. **^2^**

- If the position of the Filo's roles are lower than the welcome role. **^2^**

- If the position of the Filo's roles is equal to the welcome role. **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>f!config welcomes role enable</kbd>.

**Example**: <kbd>f!config welcomes role enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config welcomes role disable</kbd>.

**Example**: <kbd>f!config welcomes role disable</kbd>.

# Steps to set the welcome role

## **Step 1**: Set the welcome role

To set the welcome role you must execute the following command: <kbd>f!config welcomes role set \<@Role/Role ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config welcomes role set @Newbies</kbd>.

> The Filo's roles must be higher than the selected role, also the selected role can't be managed by an integration.
{.is-danger}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config welcomes role reset \<Role></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config welcomes role reset role</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
