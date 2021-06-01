---
title: Member Counter Nickname
description:
published: 1
date: 2021-06-01T17:49:06.739Z
tags:
editor: markdown
---

# About the module

This module will allow you to set a member counter on Filo's nickname.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permission: ``CHANGE_NICKNAME``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](en/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``CHANGE_NICKNAME`` permission. **^1^**

**^1^** If this requirement is met, the module settings will be reset.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>f!config member-counter nickname enable</kbd>.

**Example**: <kbd>f!config member-counter nickname enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config member-counter nickname disable</kbd>.

**Example**: <kbd>f!config member-counter nickname disable</kbd>.

# Steps to set the nickname

## **Step 1**: Set the nickname

To set the nickname you must execute the following command: <kbd>f!config member-counter nickname set \<Name {members}></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> The nickname can't exceed **28 characters** in length and must include the variable `{members}` in the content.
{.is-danger}

**Example**: <kbd>f!config member-counter nickname set 👥 Members: {members}</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config member-counter reset \<Nickname></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config member-counter reset nickname</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
