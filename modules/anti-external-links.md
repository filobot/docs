---
title: Anti External Links
description:
published: true
date: Sun Jun 20 2021 08:52:33 GMT+0000 (Coordinated Universal Time)
dateCreated: Sun Jun 20 2021 08:52:33 GMT+0000 (Coordinated Universal Time)
tags:
editor: markdown
---

# About the module

This module will allow you to delete the message and warn members to send external links.

> We recommend using this module if you manage a community.
{.is-success}

> All Discord links will bypass this module.
{.is-warning}

# Getting Started

Before proceeding with this article, you must take into account a series of elements that can influence when you are going to carry out any action described on this page:

- Filo requires the following advanced permission: ``MANAGE_MESSAGES``.

- Filo requires the following basic permissions: ``VIEW_CHANNEL``, ``SEND_MESSAGES``, ``EMBED_LINKS``, ``USE_EXTERNAL_EMOJIS``, ``READ_MESSAGE_HISTORY`` and ``ADD_REACTIONS``.

- You need ``ADMINISTRATOR`` permission to perform most of the actions in this article.

- You should replace <kbd>f!</kbd> with the current prefix you have set. More information on how to change the prefix by **[clicking here](https://wiki.filobot.xyz/en/modules/prefix)**.

# Module exceptions

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

To enable the module you must execute the following command: <kbd>f!config anti-external-links enable</kbd>.

**Example**: <kbd>f!config anti-external-links enable</kbd>.

> This module can be supplemented with the **[Auto Moderation](https://wiki.filobot.xyz/en/modules/auto-moderation)** module.
{.is-success}

# Steps to disable the module

## **Step 1**: Disable the module

To disable the module you must execute the following command: <kbd>f!config anti-external-links disable</kbd>.

**Example**: <kbd>f!config anti-external-links disable</kbd>.

# Steps to add a URL to the allowed list

## Steps to add a subdomain to the allowed list

### **Step 1**: Add a subdomain to the allowed list

To add a subdomain to the allowed list you must execute the following command: <kbd>f!config anti-external-links allow url add \<URL></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> It is mandatory that the URL has the **HTTPS** protocol enabled, otherwise it cannot be added to the allowed list.
{.is-danger}

**Example**: <kbd>f!config anti-external-links allow url add https://wiki.filobot.xyz</kbd>.

> You can allow all subdomains of a domain by replacing the subdomain with an asterisk.
> **Example**: https://*.filobot.xyz.
{.is-info}

> You can allow all links from a domain and its subdomains by replacing the subdomain and the path with an asterisk as described in this article.
> **Example**: https://*.filobot.xyz/*.
{.is-success}

## Steps to add a domain to the allowed list

### **Step 1**: Add a domain to the allowed list

To add a domain to the allowed list you must execute the following command: <kbd>f!config anti-external-links allow url add \<URL></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> It is mandatory that the URL has the **HTTPS** protocol enabled, otherwise it cannot be added to the allowed list.
{.is-danger}

**Example**: <kbd>f!config anti-external-links allow url add https://filobot.xyz</kbd>.

> You can allow all links from a domain and its subdomains by replacing the subdomain and the path with an asterisk as described in this article.
> **Example**: https://*.filobot.xyz/*.
{.is-success}

## Steps to add a path to the allowed list

### **Step 1**: Add a path to the allowed list

To add a path to the allowed list you must execute the following command: <kbd>f!config anti-external-links allow url add \<URL></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> It is mandatory that the URL has the **HTTPS** protocol enabled, otherwise it cannot be added to the allowed list.
{.is-danger}

**Example**: <kbd>f!config anti-external-links allow url add https://wiki.filobot.xyz/en/home</kbd>.

> You can allow all paths of a domain by replacing the path with an asterisk.
> **Example**: https://filobot.xyz/*.
{.is-info}

> You can allow all links from a domain and its subdomains by replacing the subdomain and the path with an asterisk as described in this article.
> **Example**: https://*.filobot.xyz/*.
{.is-success}

## Steps to remove a URL from the allowed list

### **Step 1**: Remove a URL from the allowed list

To remove a url from the allowed list you must execute the following command: <kbd>f!config anti-external-links allow url remove \<URL></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

> It is mandatory that the URL has the **HTTPS** protocol enabled, otherwise it cannot be added to the allowed list.
{.is-danger}

**Example**: <kbd>f!config anti-external-links allow url remove https://filobot.xyz</kbd>.

# Steps to add a channel to the allowed list

## **Step 1**: Add a channel to the allowed list

To add a channel to the allowed list you must execute the following command: <kbd>f!config anti-external-links allow channel add \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-external-links allow channel add #spam-allowed</kbd>.

> If you add a channel to the allowed list, a warn won't be granted to those users who spam on those channels.
{.is-warning}

# Steps to remove a channel to the allowed list

## **Step 1**: Remove a channel to the allowed list

To remove a channel to the allowed list you must execute the following command: <kbd>f!config anti-external-links allow channel remove \<#Channel/Channel ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-external-links allow channel remove #general</kbd>.

> If you remove a channel to the allowed list, a warn will be granted to those users who spam on those channels.
{.is-warning}

# Steps to add a channel to the allowed list

## **Step 1**: Add a role to the allowed list

To add a role to the allowed list you must execute the following command: <kbd>f!config anti-external-links allow role add \<@Role/Role ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-external-links allow role add @Moderators</kbd>.

> If you add a role to the allowed list, users who have that role assigned won't be warned if they spam.
{.is-warning}

# Steps to remove a role to the allowed list

## **Step 1**: Remove a role to the allowed list

To remove a role to the allowed list you must execute the following command: <kbd>f!config anti-external-links allow role remove \<@Role/Role ID></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-external-links allow role remove @Moderators</kbd>.

> If you remove a role to the allowed list, users who have that role assigned will be warned if they spam.
{.is-warning}

# Steps to reset module settings

## **Step 1**: Reset the module settings

To reset the module settings you must execute the following command: <kbd>f!config anti-external-links reset \<Allow/Action></kbd>.

> Don't include ``<>`` when you're running the command.
{.is-warning}

**Example**: <kbd>f!config anti-external-links reset</kbd>.

> You'll be forced to confirm the action you are about to take. Once you have confirmed the action, you won't be able to recover the previous data.
{.is-danger}
