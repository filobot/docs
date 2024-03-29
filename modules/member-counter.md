---
title: Member Counter
description:
published: true
date: Wed Nov 10 2021 15:48:08 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:48:08 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to display the member count of your guild in a voice channel.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_CHANNELS``.

- Filo requires the following basic permission: ``VIEW_CHANNEL``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/member-counter enable ``module:Member counter channel``</kbd>.

**Example**: <kbd>/member-counter enable ``module:Member counter channel``</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/member-counter disable ``module:Member counter channel``</kbd>.

**Example**: <kbd>/member-counter disable ``module:Member counter channel``</kbd>.

# Steps to set the member-counter channel

## **Step 1**: Set the member-counter channel

To set the member-counter channel you must execute the following command: <kbd>/member-counter channel ``channel:<Channel/Channel ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/member-counter channel ``channel:123456789123456789``</kbd>.

> The channel you select must be **voice channel**, otherwise the module won't work.
{.is-warning}

> Filo requires the following advanced permissions: ``VIEW_CHANNEL`` and ``MANAGE_CHANNELS``.
{.is-danger}

# Steps to set the member-counter channel name

## **Step 1**: Set the member-counter channel name

To set the member-counter channel name you must execute the following command: <kbd>/member-counter name ``name:<Name {{members}}>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> The channel name can't exceed **100 characters** in length and must include the variable `{{members}}` in the content.
{.is-danger}

**Example**: <kbd>/member-counter name ``name:👥 Members: {{members}}``</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/member-counter reset</kbd>.

**Example**: <kbd>/member-counter reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
