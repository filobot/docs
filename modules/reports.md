---
title: Reports
description:
published: true
date: Sun Oct 24 2021 12:22:33 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:22:33 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow users to report the bad behavior of other users of the server.

> We recommend using this module if you manage a community.
{.is-success}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_WEBHOOKS``.

- Filo requires the following basic permission: ``VIEW_CHANNEL``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Module exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If the webhook has been removed. **^1^**

- If the webhook shares a channel with another Filo's module (e.g. logging). **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/reports enable</kbd>.

**Example**: <kbd>/reports enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/reports disable</kbd>.

**Example**: <kbd>/reports disable</kbd>.

# Steps to set the reports channel

## **Step 1**: Set the reports channel

To set the reports channel you must execute the following command: <kbd>/reports channel ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/reports channel ``channel:#reports``</kbd>.

> Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_WEBHOOKS``.
{.is-danger}

> The channel you select should be private and accessible to server moderators.
{.is-success}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/reports reset</kbd>.

**Example**: <kbd>/reports reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
