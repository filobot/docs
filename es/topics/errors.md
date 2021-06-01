---
title: Common Errors
description:
published: 1
date: 2021-06-01T18:01:16.435Z
tags:
editor: markdown
---

Here you'll find documented all Filo errors along with their possible solutions.

# Something went wrong when trying to execute that action

## Without Tracking ID

This is an error that will be granted whenever something fails on your part, for example, the lack of permissions from Filo can cause this error to be sent.

**Solution**: Check that the Filo permissions are correctly placed and that the role hierarchy is appropriate for each situation.

## With Tracking ID

This error occurs when something isn't working on our side or the Discord API doesn't return satisfactory responses.

**Solution**: Inform the Filo Development Team and wait for a solution to the problem.

> It's possible that there's no definitive solution, depending on the causes of the error.
{.is-warning}

# The ``EXAMPLE`` module is disabled

This is an error that's sent when you try to use a command or functionality that's only available if you have the necessary module enabled.

**Solution**: Enable the necessary module that's specified in the error message.

# The ``EXAMPLE`` module doesn't work even though it's enabled

This error is given when something in the module configuration does not work as it should; The causes could be: lack of necessary permissions, problems in the role hierarchy, the necessary channel ceased to exist, malformation of the information sent by the module, the webhook ceased to exist, etc.

**Solution**: Check that the configuration is correct, the permissions are correct and if the hierarchy is correct.

> If you can't determine the problem why the module doesn't work, **[contact us](https://filobot.xyz/discord)**.
{.is-warning}

# You don't have permissions to run the ``EXAMPLE`` command

This error is given when you try to execute a command that you shouldn't have access to, for example, a moderation command without being a server moderator.

**Solution**: Ask a superior of your server to establish the necessary permissions for the execution of the command in question.

> If you can't determine which permission is necessary, **[contact us](https://filobot.xyz/discord)**.
{.is-warning}

# You don't have permissions to run the command ``EXAMPLE`` to ``DiscordUser#0000``

This error is given when you try to execute a command with a user who has a higher role hierarchy than yours.

**Solution**: Ask a superior to review your role hierarchy and that of the user with whom you want to run the command.

# An error occurred while trying to contact the API

This error is given when the command or module depends on a third-party API and it doesn't return a successful response.

**Solution**: Try to try the action taken later, if it continues the same, **[contact us](https://filobot.xyz/discord)**.

# Filo doesn't respond to any command

This error occurs when the Discord API doesn't send the necessary information about the permissions of Filo in the command execution channel.

**Solution**: Please try again later and if the problem persists, **[contact us](https://filobot.xyz/discord)**.

> There's currently no definitive solution to this error.
{.is-danger}
