---
title: Member Counter Nickname
description:
published: true
date: Wed Nov 10 2021 15:40:22 GMT+0000 (Coordinated Universal Time)
dateCreated: Wed Nov 10 2021 15:40:22 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to set a member counter on Filo's nickname.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permission: ``CHANGE_NICKNAME``.

- Filo requires the following basic permission: ``VIEW_CHANNEL``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Module exceptions

This module has exceptions, which means that it won't work if some of the requirements mentioned below are met:

- If Filo doesn't have ``CHANGE_NICKNAME`` permission. **^1^**

**^1^** If this requirement is met, the module settings will be reset.

# Steps to enable the module

## **Step 1**: Enable the module

To enable the module you must execute the following command: <kbd>/member-counter enable ``module:Member counter nickname``</kbd>.

**Example**: <kbd>/member-counter enable ``module:Member counter nickname``</kbd>.

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>/member-counter disable ``module:Member counter nickname``</kbd>.

**Example**: <kbd>/member-counter disable ``module:Member counter nickname``</kbd>.

# Steps to set the nickname

## **Step 1**: Set the nickname

To set the nickname you must execute the following command: <kbd>/member-counter nickname ``nickname:<Name {{members}}>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> The nickname can't exceed **32 characters** in length and must include the variable `{members}` in the content.
{.is-danger}

**Example**: <kbd>/member-counter nickname ``nickname:👥 Members: {{members}}``</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/member-counter reset</kbd>.

**Example**: <kbd>/member-counter reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
