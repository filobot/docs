---
title: Guild Invite
description:
published: 1
date: 2021-06-01T17:54:07.932Z
tags:
editor: markdown
---

# About the module

This module will allow you to set a permanent invite from the guild.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``CREATE_INSTANT_INVITE``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](en/modules/prefix)**.

# Steps to create the invite on a channel

## **Step 1**: Create the invite on a channel

To create the invite on a channel you must execute the following command: <kbd>f!config guild invite create \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config guild invite create #general</kbd>.

> Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``CREATE_INSTANT_INVITE``.
{.is-danger}

# Steps to set a existing invite from a channel

## **Step 1**: Set a existing invite from a channel

To set a existing invite from a channel you must execute the following command: <kbd>f!config guild invite set \<Invite URL/Invite Code></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config guild invite set https://discord.gg/xHhBWhT</kbd>.

> The invite you set must be from the same guild.
{.is-danger}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config guild reset \<Invite></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config guild reset invite</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
