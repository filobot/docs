---
title: Anti Spam
description:
published: 1
date: 2021-06-01T17:52:53.358Z
tags:
editor: markdown
---

# About the module

This module will allow you to delete and warn a user who does spam.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permission: ``MANAGE_MESSAGES``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](es/modules/prefix)**.

# Module Exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS`` and ``MANAGE_MESSAGES`` permissions. **^1^**

- If the user has the ``ADMINISTRATOR`` permission. **^2^**

- If the user has the ``MANAGE_GUILD`` permission. **^2^**

- If the user has the ``MANAGE_MESSAGES`` permission. **^2^**

- If the user has the ``BAN_MEMBERS`` permission. **^2^**

- If the user has the ``KICK_MEMBERS`` permission. **^2^**

- If the position of the Filo's roles are lower than the user roles. **^2^**

- If the position of the Filo's roles are equal to the user roles. **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>f!config anti-spam enable</kbd>.

**Example**: <kbd>f!config anti-spam enable</kbd>.

> This module can be supplemented with the **[Auto Moderation](/es/modules/auto-moderation)** module.
{.is-success}

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config anti-spam disable</kbd>.

**Example**: <kbd>f!config anti-spam disable</kbd>.

# Steps to add a channel to the allowed list

## **Step 1**: Add a channel to the allowed list

To add a channel to the allowed list you must execute the following command: <kbd>f!config anti-spam allow channel add \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-spam allow channel add #spam-allowed</kbd>.

> If you add a channel to the allowed list, a warn won't be granted to those users who spam on those channels.
{.is-warning}

# Steps to remove a channel to the allowed list

## **Step 1**: Remove a channel to the allowed list

To remove a channel to the allowed list you must execute the following command: <kbd>f!config anti-spam allow channel remove \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-spam allow channel remove #general</kbd>.

> If you remove a channel to the allowed list, a warn will be granted to those users who spam on those channels.
{.is-warning}

# Steps to add a channel to the allowed list

## **Step 1**: Add a role to the allowed list

To add a role to the allowed list you must execute the following command: <kbd>f!config anti-spam allow role add \<@Role/Role ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-spam allow role add @Moderators</kbd>.

> If you add a role to the allowed list, users who have that role assigned won't be warned if they spam.
{.is-warning}

# Steps to remove a role to the allowed list

## **Step 1**: Remove a role to the allowed list

To remove a role to the allowed list you must execute the following command: <kbd>f!config anti-spam allow role remove \<@Role/Role ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-spam allow role remove @Moderators</kbd>.

> If you remove a role to the allowed list, users who have that role assigned will be warned if they spam.
{.is-warning}

# Steps to set the threshold and time for duplicate messages

## **Step 1**: Set the threshold for duplicate messages

To set the threshold for duplicate messages you must execute the following command: <kbd>f!config anti-spam set duplicates threshold \<Threshold></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-spam set duplicates threshold 4</kbd>

> The value must be greater than **2**.
{.is-warning}

## **Step 2**: Set the time for duplicate messages

To set the time for duplicate messages you must execute the following command: <kbd>f!config anti-spam set duplicates time \<Time></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-spam set duplicates time 5s</kbd>

> The duration of the action must be between **3 seconds** and **60 seconds**.
{.is-warning}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config anti-spam reset \<Duplicates/Roles/Channels></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-spam reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
