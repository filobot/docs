---
title: Auto Moderation
description:
published: true
date: Thu Nov 11 2021 17:05:42 GMT+0000 (Coordinated Universal Time)
dateCreated: Thu Nov 11 2021 17:05:42 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to automatically sanction those users who repeatedly have incorrect behavior.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``MANAGE_MESSAGES``, ``MANAGE_ROLES``, ``KICK_MEMBERS`` and``BAN_MEMBERS`` (if applicable).

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES`` and ``EMBED_LINKS``.

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

To enable the module you must execute the following command: <kbd>/auto-moderation enable</kbd>.

**Example**: <kbd>/auto-moderation enable</kbd>.

> This module can be supplemented with the **[Anti Evasion](https://wiki.filobot.xyz/en/modules/anti-evasion)** module.
{.is-success}

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/auto-moderation disable</kbd>.

**Example**: <kbd>/auto-moderation disable</kbd>.

# Steps to add a level

## **Step 1**: Add a level

To add a level you must execute the following command: <kbd>/auto-moderation add ``warnings:<Warnings>`` ``action:Action``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> You can see a full list of actions that Filo supports by **[clicking here](https://wiki.filobot.xyz/en/modules/actions-list)**.
{.is-info}

**Example**: <kbd>/auto-moderation add ``warnings:3`` ``action:Kick the user``</kbd>.

# Steps to remove a level

## **Step 1**: Remove a level

To remove a level you must execute the following command: <kbd>/auto-moderation remove ``level:<Level>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/auto-moderation remove ``level:1``</kbd>.

# Steps to set the information of a level

## **Step 1**: Set the information of a level

To set the information of a level you must execute the following command: <kbd>/auto-moderation set ``level:<Level>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/auto-moderation set ``level:1`` ``warnings: 3`` ``action:Kick the user``</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/auto-moderation reset</kbd>.

**Example**: <kbd>/auto-moderation reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
