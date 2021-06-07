---
title: Auto Moderation
description:
published: true
date: Mon Jun 07 2021 15:58:13 GMT+0000 (Coordinated Universal Time)
dateCreated: Mon Jun 07 2021 15:58:13 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to automatically sanction those users who repeatedly have incorrect behavior.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: {{permissions}} (if applicable).

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``MANAGE_MESSAGES``, ``MANAGE_ROLES``, ``KICK_MEMBERS`` and ``BAN_MEMBERS`` permissions. **^1^**

- If the user has the ``ADMINISTRATOR`` permission. **^2^**

- If the user has the ``MANAGE_GUILD`` permission. **^2^**

- If the user has the ``MANAGE_ROLES`` permission. **^2^**

- If the user has the ``MANAGE_MESSAGES`` permission. **^2^**

- If the user has the ``BAN_MEMBERS`` permission. **^2^**

- If the user has the ``KICK_MEMBERS`` permission. **^2^**

- If the user has the ``MUTE_MEMBERS`` permission. **^2^**

- If the position of the Filo's roles are lower than the user roles. **^2^**

- If the position of the Filo's roles are equal to the user roles. **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>f!config auto-moderation enable</kbd>.

**Example**: <kbd>f!config auto-moderation enable</kbd>.

> This module can be supplemented with the **[Anti Evasion](/es/modules/anti-evasion)** module.
{.is-success}

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config auto-moderation disable</kbd>.

**Example**: <kbd>f!config auto-moderation disable</kbd>.

# Steps to set maximum warnings per level

## **Step 1**: Set maximum warnings per level

To set maximum warnings per level you must execute the following command: <kbd>f!config auto-moderation set level \<Level> \<Number></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config auto-moderation set level 1 3</kbd>.

# Steps to set a action per level

## **Step 1**: Set a action per level

To set a action per level you must execute the following command: <kbd>f!config auto-moderation set action \<Level> \<Action></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can see a full list of actions that Filo supports by **[clicking here](/es/modules/auto-moderation/actions)**
{.is-info}

**Example**: <kbd>f!config auto-moderation set action 1 kick</kbd>.

# Steps to set the time of a action per level

## **Step 1**: Set the time of a action per level

To set the time of a action per level you must execute the following command: <kbd>f!config auto-moderation set time \<Level> \<Time></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config auto-moderation set time 1 1h</kbd>.

> The duration of the action must be between **1 minutes** and **24 days**.
{.is-warning}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config auto-moderation reset \<Levels></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config auto-moderation reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
