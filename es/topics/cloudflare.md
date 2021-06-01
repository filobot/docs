---
title: Cloudflare
description:
published: 1
date: 2021-06-01T16:29:42.026Z
tags:
editor: markdown
---

Here you'll find useful documentation on how Cloudflare works on the Filo service.

# What's Cloudflare?

Cloudflare is one of the biggest networks operating on the Internet. People use Cloudflare services for the purposes of increasing the security and performance of their web sites and services.

# How does Cloudflare help Filo?

Cloudflare helps Filo by protecting its website and API from malicious people.

# Cloudflare bans

It's essential that we protect our website from people with malicious intent, for this we are using bans on Cloudflare. Below you'll find information about these bans and how they can affect you.

## What's a Cloudflare ban?

A Cloudflare ban is a temporary or permanent sanction that will deny you access to our website. The ban can be given by:.
- Your IP address.
- Your ISP (AKA: Internet Service Provider).
- Your IP address range.
- Your User-Agent.
- Your country.

## How can I identify a Cloudflare ban?

You'll be able to quickly identify a Cloudflare ban, because you'll receive a 403 error followed by an error page titled "Access Denied".

> <p align=center><img src="https://raw.githubusercontent.com/filobot/docs/main/resources/Cloudflare%20ban.png" alt="If the image doesn't load, please contact us." /><br>
> <i>Example of a page that shows that your IP address has been banned and you can't access its content.</i></p>
{.is-image}

# What actions are banned from Cloudflare?

Information on what actions can be banned from Cloudflare is specified below, however this document may not be 100% accurate for security reasons.

## Excess 429 errors in the API

429 errors tell browsers and applications making requests of any kind to our website that your rate limit is being exceeded.

The API has two types of rate limits:
- Individual or specific.
- Global or common.

The individual or specific rate limits are more restrictive, but, as a consequence, exceeding this limit won't result in a ban on Cloudflare (although it would be advisable not to exceed these limits). These limits are specific to each API endpoint.

Global or common rate limits are restrictive in the long term, that's, if you make a large number of requests per minute, you'll likely receive a global rate limit (you won't be allowed to access any other API endpoints during a rate limit).

If you exceed 5 times the warning for exceeding the global request quota in less than 1 hour, your IP address will be temporarily banned for 1 hour.

Please note that Cloudflare bans affect all domains related to Filo.

## Excess 429 errors in the rest of the service

429 errors tell browsers and applications making requests of any kind to our website that your rate limit is being exceeded

The rest of the Filo service has two types of rate limits:
- Global or common.

The individual or specific rate limits are more restrictive, but, as a consequence, exceeding this limit won't result in a ban on Cloudflare (although it would be advisable not to exceed these limits). These limits are specific to each API endpoint

Global or common rate limits are restrictive in the long term, that's, if you make a large number of requests per minute, you'll likely receive a global rate limit (you won't be allowed to access any other API endpoints during a rate limit).

If you exceed 5 times the warning for exceeding the global request quota in less than 1 hour, your IP address will be temporarily banned for 1 hour

Please note that Cloudflare bans affect all domains related to Filo

## Appeal a ban on Cloudflare

Below you'll find information on how to appeal a ban on Cloudflare.

## Appeal according to the duration of the ban

- Temporary: Not available.
- Permanent: You can appeal a permanent ban by **[clicking here](https://forms.gle/Pdig38H5gn6XfyW76)**.

## Appeal according to the type of ban

Below you'll find information on how to appeal the type of ban:

> Please note that some bans can't be appealed due to their nature.
{is-warning}

- **IP address**: IP address.
- **ISP (AKA: Internet Service Provider)**: ISP (AKA: Internet Service Provider).
- **IP address range**: IP address range.
- **User-Agent**: User-Agent.
- **Country**: .

# Repetitive sanctions

The automatic sanctions of our service are always temporary, however, if an IP address or ISP receives constant sanctions, our team can permanently ban the following parameters:
- **IP address**.
- **IP address range**.
- **ISP (AKA: Internet Service Provider)**.

# Permanent bans on Cloudflare

Permanent Cloudflare bans are granted as the last measure of protection for our service. While it's true that, in the event of an ISP ban, all of its clients are denied access to our website, it isn't entirely true.

## ISP ban

It isn't entirely true that to protect our website we ban an ISP, rather we force all clients of this ISP to perform a captcha. This validates requests and makes it possible to deny access to people with bad intentions.

## IP address range ban

Depending on the situation, if an IP address range has been permanently banned, on special occasions, it's possible that no type of captcha is performed to validate the requests. Likewise, the priority of our team is to reject requests with bad intentions as the main measure.

## User-Agent ban

Typically, those who modify the User-Agent of their browser or application to make requests to a website know what they are doing. Modification to an unknown User-Agent can be interpreted as a threat and receive a sanction from us.

Our recommendation is to leave the browser's default User-Agent or specify a known User-Agent.

## Country ban

It isn't entirely true that we ban countries that make malicious requests (at least not if we consider the number of malicious requests tolerable). As a priority, we'll request a captcha to all requests from those countries and all requests with bad intentions will be rejected, to ensure that our service is accessible to people with good intentions.

# hCaptcha

The captcha is managed by **[hCaptcha](https://www.hcaptcha.com)** and applies a **[Terms and Conditions](https://www.hcaptcha.com/terms)** and **[Privacy Policy](https://www.hcaptcha.com/privacy)**.

> <p align=center><img src="https://raw.githubusercontent.com/filobot/docs/main/resources/hCaptcha.png" alt="If the image doesn't load, please contact us." /><br>
> <i>Example of a page that shows an hCaptcha to be able to access its content.</i></p>
{.is-image}
