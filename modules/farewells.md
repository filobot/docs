---
title: Farewells
description:
published: true
date: Sun Oct 24 2021 14:37:45 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 14:37:45 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to send a farewell message to the old members of the server.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES`` and ``EMBED_LINKS``.

- Filo requires the following basic permission: ``VIEW_CHANNEL``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Module exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``VIEW_CHANNEL``, ``SEND_MESSAGES`` and ``EMBED_LINKS`` permissions. **^1^**

**^1^** If this requirement is met, the module settings will be reset.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/farewells enable</kbd>.

**Example**: <kbd>/farewells enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/farewells disable</kbd>.

**Example**: <kbd>/farewells disable</kbd>.

# Steps to set the farewells channel

## **Step 1**: Set the farewells channel

To set the farewells channel you must execute the following command: <kbd>/farewells channel ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/farewells channel ``channel:#farewells``</kbd>.

# Steps to set the farewell message

## **Step 1**: Set the farewell message

To set the farewells channel you must execute the following command: <kbd>/farewells message</kbd>.

> You'll have **1 minute** to perform this action.
{.is-warning}

**Example**: <kbd>/farewells message</kbd>.

> You can set variables in the farewell message. You can find a list of all variables by **[clicking here](https://wiki.filobot.xyz/en/modules/farewells/variables)**.
{.is-info}

> ```md
> Goodbye **{{user.tag}}**! 😧
> We look forward to your return in **{{server.name}}**. 👋
> ```
> **Message code**
>
> Goodbye **DiscordUser#0000**! 😧
> We look forward to your return in **Awesome Server**. 👋
>
> **Result message**

# Steps to set the message type

## **Step 1**: Set the message type

To set the message type you must execute the following command: <kbd>/farewells type ``type:<Normal/Embed>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/farewells type ``type:Embed``</kbd>.

> If users have disabled the display of embeds, they won't see the farewell message.
{.is-danger}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/farewells reset</kbd>.

**Example**: <kbd>/farewells reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
