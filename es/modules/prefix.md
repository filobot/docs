---
title: Prefix
description:
published: 1
date: 2021-06-01T17:54:07.854Z
tags:
editor: markdown
---

# About the module

This module will allow you to set or reset the Filo's prefix.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Steps to set a new prefix

## **Step 1**: Set a new prefix

To set a new prefix you must execute the following command: <kbd>f!config prefix set \<Prefix></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config prefix set f!</kbd>.

> Slash prefixes aren't supported by Filo.
{.is-danger}

> You can't set a prefix that is longer than **2** characters.
{.is-warning}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config prefix reset</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config prefix reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
