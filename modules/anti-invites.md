---
title: Anti Invites
description:
published: true
date: Wed Nov 10 2021 16:33:31 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 16:33:31 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to delete and warn users who send invites outside your server or the allowed servers.

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

- If the position of the Filo's roles are lower than the user roles. **^2^**

- If the position of the Filo's roles are equal to the user roles. **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/anti-invites enable</kbd>.

**Example**: <kbd>/anti-invites enable</kbd>.

> This module can be supplemented with the **[Auto Moderation](https://wiki.filobot.xyz/en/modules/auto-moderation)** module.
{.is-success}

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/anti-invites disable</kbd>.

**Example**: <kbd>/anti-invites disable</kbd>.

# Steps to enable Filo server bypass

## **Step 1**: Enable Filo server bypass

To enable filo server bypass you must execute the following command: <kbd>/anti-invites filo ``action:Enable``</kbd>.

**Example**: <kbd>/anti-invites filo ``action:Enable``</kbd>.

# Steps to disable Filo server bypass

## **Step 1**: Disable Filo server bypass

To disable filo server bypass you must execute the following command: <kbd>/anti-invites filo ``action:Disable``</kbd>.

**Example**: <kbd>/anti-invites filo ``action:Disable``</kbd>.

# Steps to enable Discord official servers bypass

## **Step 1**: Enable Discord official servers bypass

To enable discord official servers bypass you must execute the following command: <kbd>/anti-invites discord ``action:Enable``</kbd>.

**Example**: <kbd>/anti-invites discord ``action:Enable``</kbd>.

# Steps to disable Discord official servers bypass

## **Step 1**: Disable Discord official servers bypass

To disable discord official servers bypass you must execute the following command: <kbd>/anti-invites discord ``action:Disable``</kbd>.

**Example**: <kbd>/anti-invites discord ``action:Disable``</kbd>.

# Steps to add a server to the allowed list

## **Step 1**: Add a server to the allowed list

To add a server to the allowed list you must execute the following command: <kbd>/anti-invites guild ``action:Add`` ``guild:<Server ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-invites guild ``action:Add`` ``guild:123456789123456789``</kbd>.

> Check out this article from the Discord support center by **[clicking here](https://support.discord.com/hc/en-us/articles/206346498)**
{.is-info}

# Steps to remove a server to the allowed list

## **Step 1**: Remove a server to the allowed list

To remove a server to the allowed list you must execute the following command: <kbd>/anti-invites guild ``action:Remove`` ``guild:<Server ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-invites guild ``action:Remove`` ``guild:123456789123456789``</kbd>.

> Check out this article from the Discord support center by **[clicking here](https://support.discord.com/hc/en-us/articles/206346498)**
{.is-info}

# Steps to add a channel to the allowed list

## **Step 1**: Add a channel to the allowed list

To add a channel to the allowed list you must execute the following command: <kbd>/anti-invites channel ``action:Add`` ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-invites channel ``action:Add`` ``channel:#spam-allowed``</kbd>.

> If you add a channel to the allow list, this module will not work on that channel.
{.is-warning}

# Steps to remove a channel to the allowed list

## **Step 1**: Remove a channel to the allowed list

To remove a channel to the allowed list you must execute the following command: <kbd>/anti-invites channel ``action:Remove`` ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-invites channel ``action:Remove`` ``channel:#general``</kbd>.

> If you remove a channel from the allowed list, this module will work on that channel.
{.is-warning}

# Steps to add a channel to the allowed list

## **Step 1**: Add a role to the allowed list

To add a role to the allowed list you must execute the following command: <kbd>/anti-invites role ``action:Add`` ``role:<@Role/Role ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-invites role ``action:Add`` ``role:@Moderators``</kbd>.

> If you add a role to the allowed list, anyone who has this role will be exempt from the operation of this module.
{.is-warning}

# Steps to remove a role to the allowed list

## **Step 1**: Remove a role to the allowed list

To remove a role to the allowed list you must execute the following command: <kbd>/anti-invites role ``action:Remove`` ``role:<@Role/Role ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/anti-invites role ``action:Remove`` ``role:@Moderators``</kbd>.

> If you remove a role from the allowed list, anyone who has this role will no longer be exempt from the operation of this module.
{.is-warning}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/anti-invites reset</kbd>.

**Example**: <kbd>/anti-invites reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
