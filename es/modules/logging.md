---
title: Logging
description:
published: 1
date: 2021-06-01T18:01:16.354Z
tags:
editor: markdown
---

# About the module

This module will allow you to send all the server logs to a specific channel.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_WEBHOOKS``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If the webhook has been removed. **^1^**

- If the webhook shares a channel with another Filo's module (e.g. reports). **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>f!config logging enable</kbd>.

**Example**: <kbd>f!config logging enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config logging disable</kbd>.

**Example**: <kbd>f!config logging disable</kbd>.

# Steps to set the logging channel

## **Step 1**: Set the logging channel

To set the logging channel you must execute the following command: <kbd>f!config logging set channel \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config logging set channel #server-logs</kbd>.

> Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_WEBHOOKS``.
{.is-danger}

> The channel you select should be private and accessible to server moderators.
{.is-success}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config logging reset \<Channel> (optional)</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config logging reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
