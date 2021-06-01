---
title: Farewells
description:
published: 1
date: 2021-06-01T17:49:06.638Z
tags:
editor: markdown
---

# About the module

This module will allow you to send a farewell message to the old members of the server.

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

To enable the module you must execute the following command: <kbd>f!config farewells enable</kbd>.

**Example**: <kbd>f!config farewells enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config farewells disable</kbd>.

**Example**: <kbd>f!config farewells disable</kbd>.

# Steps to set the farewells channel

## **Step 1**: Set the farewells channel

To set the farewells channel you must execute the following command: <kbd>f!config farewells set channel \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config farewells set channel #farewells</kbd>.

# Steps to set the farewell message

## **Step 1**: Set the farewell message

To set the farewells channel you must execute the following command: <kbd>f!config farewells set message \<Message></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can set variables in the farewell message. You can find a list of all variables by **[clicking here](/es/modules/farewells/variables)**.
{.is-info}

**Example**: <kbd>f!config farewells set message Goodbye {user.tag}!</kbd>.

> ```md
> Goodbye **{user.tag}**! 😧
> We look forward to your return in **{server}**. 👋
> ```
> **Message code**
>
> Goodbye **DiscordUser#0000**! 😧
> We look forward to your return in **Awesome Server**. 👋
>
> **Result message**

# Steps to set the message type

## **Step 1**: Set the message type

To set the message type you must execute the following command: <kbd>f!config farewells set type \<Normal/Embed></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config farewells set type embed</kbd>.

> If users have disabled the display of embeds, they won't see the farewell message.
{.is-danger}

## **Step 12**: Set the embed color (optional)

Currently Filo doesn't have a command to set the embed color, however there is a way to change it. When Filo is going to send the farewell message through an embed, it obtains the information of the highest role assigned to it. If said role has a custom color, the color of the embed will be the same as said role.

> Check out this article from the Discord support center by **[clicking here](https://support.discord.com/hc/en-us/articles/214836687)**
{.is-info}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config farewells reset \<Channel/Message/Type> (optional)</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config farewells reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
