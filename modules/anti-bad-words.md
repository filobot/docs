---
title: Anti Bad Words
description:
published: true
date: Sun Nov 14 2021 15:13:05 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Nov 14 2021 15:13:05 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will sanction those users who send messages with bad words.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` and ``MANAGE_MESSAGES``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Module exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS`` and ``MANAGE_MESSAGES`` permissions. **^1^**

- If the user has the ``ADMINISTRATOR`` permission. **^2^**

- If the user has the ``MANAGE_GUILD`` permission. **^2^**

- If the user has the ``EVADE_SANCTIONS`` permission. **^2^**

- If the position of the Filo's roles are lower than the user roles. **^2^**

- If the position of the Filo's roles are equal to the user roles. **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/anti-bad-words enable</kbd>.

**Example**: <kbd>/anti-bad-words enable</kbd>.

> This module can be supplemented with the **[Auto Moderation](https://wiki.filobot.xyz/en/modules/auto-moderation)** module.
{.is-success}

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/anti-bad-words disable</kbd>.

**Example**: <kbd>/anti-bad-words disable</kbd>.

# Steps to ban a bad word

## **Step 1**: Ban a bad word

To ban a bad word you must execute the following command: <kbd>/anti-bad-words word ``action:Add`` ``word:<Bad word>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-bad-words word ``action:Add`` ``word:Kawaii``</kbd>.

# Steps to unban a bad word

## **Step 1**: Unban a bad word

To unban a bad word you must execute the following command: <kbd>/anti-bad-words word ``action:Remove`` ``word:<Bad word>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-bad-words word ``action:Remove`` ``word:Kawaii``</kbd>.

# Steps to enable the aggressive filter

## **Step 1**:  Enable the aggressive filter

To enable the aggressive filter you must execute the following command: <kbd>/anti-bad-words aggresive-filter ``action:Enable``</kbd>.

**Example**: <kbd>/anti-bad-words aggresive-filter ``action:Enable``</kbd>.

> Enabling the aggressive filter can cause a higher number of false positives.
{.is-danger}

# Steps to disable the aggressive filter

## **Step 1**:  Disable the aggressive filter

To disable the aggressive filter you must execute the following command: <kbd>/anti-bad-words aggresive-filter ``action:Disable``</kbd>.

**Example**: <kbd>/anti-bad-words aggresive-filter ``action:Disable``</kbd>.

# Steps to set a sanction

## **Step 1**: Set a sanction

To set a sanction you must execute the following command: <kbd>/anti-bad-words action ``action:<Action>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can see a full list of actions that Filo supports by **[clicking here](https://wiki.filobot.xyz/en/modules/actions-list)**.
{.is-info}

**Example**: <kbd>/anti-bad-words action ``action:Temporarily mute the user`` ``time:1h``</kbd>.

# Steps to add a channel to the allowed list

## **Step 1**: Add a channel to the allowed list

To add a channel to the allowed list you must execute the following command: <kbd>/anti-bad-words channel ``action:Add`` ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-bad-words channel ``action:Add`` ``channel:#spam-allowed``</kbd>.

> If you add a channel to the allow list, this module will not work on that channel.
{.is-warning}

# Steps to remove a channel to the allowed list

## **Step 1**: Remove a channel to the allowed list

To remove a channel to the allowed list you must execute the following command: <kbd>/anti-bad-words channel ``action:Remove`` ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-bad-words channel ``action:Remove`` ``channel:#general``</kbd>.

> If you remove a channel from the allowed list, this module will work on that channel.
{.is-warning}

# Steps to add a role to the allowed list

## **Step 1**: Add a role to the allowed list

To add a role to the allowed list you must execute the following command: <kbd>/anti-bad-words role ``action:Add`` ``role:<@Role/Role ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-bad-words role ``action:Add`` ``role:@Moderators``</kbd>.

> If you add a role to the allowed list, anyone who has this role will be exempt from the operation of this module.
{.is-warning}

# Steps to remove a role to the allowed list

## **Step 1**: Remove a role to the allowed list

To remove a role to the allowed list you must execute the following command: <kbd>/anti-bad-words role ``action:Remove`` ``role:<@Role/Role ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-bad-words role ``action:Remove`` ``role:@Moderators``</kbd>.

> If you remove a role from the allowed list, anyone who has this role will no longer be exempt from the operation of this module.
{.is-warning}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/anti-bad-words reset</kbd>.

**Example**: <kbd>/anti-bad-words reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
