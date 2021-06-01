---
title: Muted Role
description:
published: 1
date: 2021-06-01T18:01:16.449Z
tags:
editor: markdown
---

# About the module

This module will allow you to set the Muted role.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_ROLES``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Steps to create the muted role

## **Step 1**: Create the the muted role

To create the the muted role you must execute the following command: <kbd>f!config guild role muted create</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config guild role muted create</kbd>.

# Steps to set a existing muted role

## **Step 1**: Set a existing muted role

To set a existing muted role you must execute the following command: <kbd>f!config guild role muted set \<@Role/Role ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config guild role muted set @Muted</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config guild reset \<Muted></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config guild reset muted</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
