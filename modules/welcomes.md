---
title: Welcomes
description:
published: true
date: Sun Oct 24 2021 13:38:06 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 13:38:06 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to send a welcome message to the new members of the server.

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

To enable the module you must execute the following command: <kbd>/welcomes enable ``module:Welcome message``</kbd>.

**Example**: <kbd>/welcomes enable ``module:Welcome message``</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/welcomes disable ``module:Welcome message``</kbd>.

**Example**: <kbd>/welcomes disable ``module:Welcome message``</kbd>.

# Steps to set the welcomes channel

## **Step 1**: Set the welcomes channel

To set the welcomes channel you must execute the following command: <kbd>/welcomes channel ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/welcomes channel ``channel:#welcomes``</kbd>.

# Steps to set the welcome message

## **Step 1**: Set the welcome message

To set the welcomes channel you must execute the following command: <kbd>/welcomes message</kbd>.

> You'll have **1 minute** to perform this action.
{.is-warning}

**Example**: <kbd>/welcomes message</kbd>.

> You can set variables in the welcome message. You can find a list of all variables by **[clicking here](https://wiki.filobot.xyz/en/modules/welcomes/variables)**.
{.is-info}

> ```md
> Welcome {{@user}} to the server **{{server.name}}**! 😉
> Thanks to you we are **{{server.members}}** total members! 🎉
> ```
> **Message code**
>
> Welcome @DiscordUser to the server **Awesome Server**! 😉
> Thanks to you we are **123,456** total members! 🎉
>
> **Result message**

# Steps to set the message type

## **Step 1**: Set the message type

To set the message type you must execute the following command: <kbd>/welcomes type ``type:<Normal/Embed>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/welcomes type ``type:Embed``</kbd>.

> If users have disabled the display of embeds, they won't see the welcome message.
{.is-danger}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/welcomes reset</kbd>.

**Example**: <kbd>/welcomes reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
