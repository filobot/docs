---
title: Anti Evasion
description:
published: 1
date: 2021-06-01T17:54:07.763Z
tags:
editor: markdown
---

# About the module

This module allows you to automatically ban those users who were sanctioned in your server and tried to evade the sanction.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permission: ``BAN_MEMBERS``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS`` and ``BAN_MEMBERS`` permissions. **^1^**

**^1^** If this requirement is met, the module settings will be reset.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>f!config anti-evasion enable</kbd>.

**Example**: <kbd>f!config anti-evasion enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config anti-evasion disable</kbd>.

**Example**: <kbd>f!config anti-evasion disable</kbd>.

# Steps to set a action

## **Step 1**: Set a action

To set a action you must execute the following command: <kbd>f!config anti-evasion set action \<Action></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-evasion set action tempban</kbd>.

> You can see a full list of actions that Filo supports by **[clicking here](/es/modules/anti-evasion/actions)**.
{.is-info}

# Steps to set the time of a action

## **Step 1**: Set the time of a action

To set the time of a action you must execute the following command: <kbd>f!config anti-evasion set time \<Time></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-evasion set action 1d</kbd>.

> The duration of the action must be between **1 minutes** and **24 days**.
{.is-warning}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config anti-evasion reset \<Allow> (optional)</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-evasion reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
