---
title: Disable commands
description:
published: true
date: Sun Oct 24 2021 11:54:26 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Oct 24 2021 11:54:26 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to disable the Filo commands that you don't want to be used on your server.

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following basic permission: ``VIEW_CHANNEL``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

# Steps to disable a command

## **Step 1**: Disable a command

To disable a command you must execute the following command: <kbd>/commands disable ``target:Command`` ``value:<Command>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/commands disable ``taarget:Command`` ``value:ping``</kbd>.

# Steps to enable a command

## **Step 1**: Enable a command

To enable a command you must execute the following command: <kbd>/commands enable ``target:Command`` ``value:<Command>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/commands enable ``target:Command`` ``value:ping``</kbd>.

# Steps to disable a category of commands

## **Step 1**: Disable a category of commands

To disable a category of commands you must execute the following command: <kbd>/commands disable ``target:Category`` ``value:<Category>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/commands disable ``taarget:Category`` ``value:Core``</kbd>.

# Steps to enable a category of commands

## **Step 1**: Enable a category of commands

To enable a category of commands you must execute the following command: <kbd>/commands enable ``target:Category`` ``value:<Category>``</kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>/commands enable ``target:Category`` ``value:Core``</kbd>.

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>/commands reset</kbd>.

**Example**: <kbd>/commands reset</kbd>.