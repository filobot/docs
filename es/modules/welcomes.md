---
title: Welcomes
description:
published: 1
date: 2021-06-01T17:52:53.453Z
tags:
editor: markdown
---

# About the module

This module will allow you to send a welcome message to the new members of the server.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` and ``USE_EXTERNAL_EMOJIS``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` and ``USE_EXTERNAL_EMOJIS`` permissions. **^1^**

**^1^** If this requirement is met, the module settings will be reset.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>f!config welcomes enable</kbd>.

**Example**: <kbd>f!config welcomes enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config welcomes disable</kbd>.

**Example**: <kbd>f!config welcomes disable</kbd>.

# Steps to set the welcomes channel

## **Step 1**: Set the welcomes channel

To set the welcomes channel you must execute the following command: <kbd>f!config welcomes set channel \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config welcomes set channel #welcomes</kbd>.

# Steps to set the welcome message

## **Step 1**: Set the welcome message

To set the welcomes channel you must execute the following command: <kbd>f!config welcomes set message \<Message></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can set variables in the welcome message. You can find a list of all variables by **[clicking here](/es/modules/welcomes/variables)**.
{.is-info}

**Example**: <kbd>f!config welcomes set message Goodbye {user.tag}!</kbd>.

> ```md
> Welcome {user} to the server **{server}**! 😉
> Thanks to you we are **{server.members}** total members! 🎉
> ```
> **Message code**
>
> Welcome @DiscordUser to the server **Awesome Server**! 😉
> Thanks to you we are **123,456** total members! 🎉
>
> **Result message**

# Steps to set the message type

## **Step 1**: Set the message type

To set the message type you must execute the following command: <kbd>f!config welcomes set type \<Normal/Embed></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config welcomes set type embed</kbd>.

> If users have disabled the display of embeds, they won't see the welcome message.
{.is-danger}

## **Step 12**: Set the embed color (optional)

Currently Filo doesn't have a command to set the embed color, however there is a way to change it. When Filo is going to send the welcome message through an embed, it obtains the information of the highest role assigned to it. If said role has a custom color, the color of the embed will be the same as said role.

> Check out this article from the Discord support center by **[clicking here](https://support.discord.com/hc/en-us/articles/214836687)**
{.is-info}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config welcomes reset \<Channel/Message/Type/Role> (optional)</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config welcomes reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
