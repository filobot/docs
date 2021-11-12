---
title: Logging
description:
published: true
date: Wed Nov 10 2021 15:54:59 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:54:59 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to receive the audit records through messages on a specific channel.

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

- If the webhook shares a channel with another Filo's module (e.g. reports). **^2^**

**^1^** If this requirement is met, the module settings will be reset.

**^2^** If this or some of the requirements are met, the module won't work.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/logging enable</kbd>.

**Example**: <kbd>/logging enable</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/logging disable</kbd>.

**Example**: <kbd>/logging disable</kbd>.

# Steps to set the logging channel

## **Step 1**: Set the logging channel

To set the logging channel you must execute the following command: <kbd>/logging channel ``channel:<#Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/logging channel ``channel:#server-logs``</kbd>.

> Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_WEBHOOKS``.
{.is-danger}

> The channel you select should be private and accessible to server moderators.
{.is-success}

# Steps to configure module events

## Steps to enable an event

### **Step 1**: Enable an event

To enable an event you must execute the following command: <kbd>/logging events ``action:Enable``</kbd>.

**Example**: <kbd>/logging events ``action:Enable``</kbd>.

## Steps to disable an event

### **Step 1**: Disable an event

To disable an event you must execute the following command: <kbd>/logging events ``action:Disable``</kbd>.

**Example**: <kbd>/logging events ``action:Disable``</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/logging reset</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/logging reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
