---
title: Anti Evasion
description:
published: true
date: Fri Nov 12 2021 15:43:29 GMT+0000 (Coordinated Universal Time)
dateCreated: Fri Nov 12 2021 15:43:29 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will sanction those users who have an active sanction (mute) and have left the server.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permission: ``BAN_MEMBERS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Module exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``BAN_MEMBERS`` permission. **^1^**

**^1^** If this requirement is met, the module settings will be reset.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/anti-evasion enable</kbd>.

**Example**: <kbd>/anti-evasion enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/anti-evasion disable</kbd>.

**Example**: <kbd>/anti-evasion disable</kbd>.

# Steps to set a action

## **Step 1**: Set a action

To set a action you must execute the following command: <kbd>/anti-evasion action ``action:<Action>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can see a full list of actions that Filo supports by **[clicking here](https://wiki.filobot.xyz/en/modules/actions-list)**.
{.is-info}

**Example**: <kbd>/anti-evasion action ``action:Temporarily ban the user`` ``time:7d``</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/anti-evasion reset</kbd>.

**Example**: <kbd>/anti-evasion reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
