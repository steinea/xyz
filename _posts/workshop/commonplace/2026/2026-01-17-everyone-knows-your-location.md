---
layout: entry
category: commonplace
author: Tim Sh
title: Everyone Knows Your Location
publication: tim.sh
link: https://timsh.org/tracking-myself-down-through-in-app-ads/
date: 2026-01-17
---

"Recently I read about a [massive geolocation data leak from Gravy Analytics](https://www.404media.co/hackers-claim-massive-breach-of-location-data-giant-threaten-to-leak-data/?ref=timsh.org), which exposed more than 2000 apps, both in AppStore and Google Play, that secretly collect geolocation data without user consent."

"I looked into the list ([link here](https://docs.google.com/spreadsheets/d/1Ukgd0gIWd9gpV6bOx2pcSHsVO6yIUqbjnlM4ewjO6Cs/edit?gid=1257088277&ref=timsh.org#gid=1257088277)) and found at least 3 apps I have installed on my iPhone. Take a look for yourself!"

"this is **not** communicated correctly to the end users, you and me, in any adequate way, shape or form: the free apps you install and use **collect your precise location** with timestamp and send it to some 3rd-party companies.

The only thing that stops anyone with access to bid data (yet another ad buying agent, or ad exchange, or a dataset bought or rented from data broker, as you'll see later) from tracking you down with all trips you make daily is this `IDFA` that is not shared when you disallow apps to "track you across apps" to "enhance and personalise your ads experience"."

"How to track yourself down?

Easy! Just follow this simple step-by-step guide:

1.  Use some free apps for a bit.  
    Move around and commute - this makes the geo data more valuable.
2.  "Allow" or "ask not to track" - a combo of IP + location + User-agent + geolocation will still be leaked to hundreds of "3rd parties" regardless of your choice.
3.  Wait for a few seconds until fake DSPs and data brokers receive your data.
4.  Exchange your full name or phone number for an IDFA (if present), IP address and user-agent through the `MAID <> PII` data purchased somewhere.
5.  Now, access the "Mobility data" consisting of geolocation history, and filter it using the values from the previous step."
