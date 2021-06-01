---
title: Disable commands
description:
published: 1
date: 2021-06-01T17:56:38.247Z
tags:
editor: markdown
---

# About the module

This module will allow you to disable the Filo commands that you don't want to be used on your guild.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` and ``USE_EXTERNAL_EMOJIS``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, and ``USE_EXTERNAL_EMOJIS`` permissions. **^1^**

**^1^** If this requirement is met, the module settings will be reset.

# Steps to disable a command

## **Step 1**: Disable a command

To disable a command you must execute the following command: <kbd>f!config commands disable \<Command></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config commands disable ping</kbd>.

# Steps to enable a command

## **Step 1**: Enable a command

To enable a command you must execute the following command: <kbd>f!config commands enable \<Command></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config commands enable ping</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config commands reset \<Disabled></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config commands reset disabled</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
