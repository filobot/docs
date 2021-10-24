---
title: Muted Role
description:
published: true
date: Sun Oct 24 2021 12:21:48 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 12:21:48 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to set the Muted role.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following basic permission: ``VIEW_CHANNEL``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Steps to create the muted role

## **Step 1**: Create the the muted role

To create the the muted role you must execute the following command: <kbd>/core roles muted</kbd>.

**Example**: <kbd>/core roles muted</kbd>.

> Filo requires the following advanced permissions: ``VIEW_CHANNEL``, ``MANAGE_CHANNELS`` and ``MANAGE_ROLES``.
{.is-danger}

# Steps to set a existing muted role

## **Step 1**: Set a existing muted role

To set a existing muted role you must execute the following command: <kbd>/core roles muted ``role:<@Role/Role ID>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/core roles muted ``role:@Muted``</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/core roles reset</kbd>.

**Example**: <kbd>/core roles reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
