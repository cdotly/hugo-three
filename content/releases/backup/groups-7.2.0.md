---
title: Groups 7.2.0
subtitle: subtitle of post 4
date: 2018-06-11
draft: true
author: katt
kind: post
type: releases
layout: single
slug: groups-7-2-0
description: 
keywords: 
categories: groups
products: groups
weight: 
---

_Update: As of today, June 15, 2018, the issue with checksums for Linux installers has been resolved. This was not a security problem, rather an issue with how our release widget pushed RC versions to staging. This has now been resolved and will ensure future releases are better automated and streamlined. Kudos to Diego for resolving this! [Our download page](https://spideroakwp.wpengine.com/one/download/) is serving version 7.2.0 for all platforms now and checksums are provided below._

_Note: Today (June 13, 2018) we discovered an error in the way our Linux builds of SpiderOak One were released. This is in the process of being fixed but in the meantime we will be serving v. 7.1.0. Once the issue is resolved we will add new checksums to this page. SpiderOak Groups installers are unaffected._

This release of SpiderOak One and Groups Backup is a testament to the value of teamwork! While we don’t normally share “feel good” stories in the software development world, this one is too good not to share.

A few helpful SpiderOak One users contacted us with information about a fringe bug involving unicode and syncing data across operating systems. We were able to quickly confirm that the bug existed, but recreating was very hard. Roger from our dev team made an experimental build that fixed the issue for some users, but not all. We were temporarily stuck; without a way to recreate the issue any fix we released wouldn’t necessarily work for all users.

Enter Beth from our QA team. She spent some time working with our team of support rockstars and our users, then came up with a series of tests that successfully recreated the bug. With this information Roger was able to fine tune the fix, and today we’re releasing it to all SpiderOak One and SpiderOak Groups users.

This kind of collaboration between users, support, devs, and QA is a perfect illustration of what makes the SpiderOak community great! Your feedback plays a huge role in helping us make SpiderOak One, SpiderOak Groups, and all of our other products the best they can be. Please don’t ever hesitate to reach out to us through support.spideroak.com, @SpiderOak on Twitter or on Facebook at facebook.com/SpiderOak.

## Changes

- Add notice for data storage
- Normalize naming conventions
- Calculate space usage in a more efficient way

## Bug Fixes

- Fix sync bug where the client reports that it can’t find a journal
- (Groups only) Fix icons in dashboard for policy enforcement

## Installer Hashes (SHA256):

| PLATFORM                    | VERSION | HASH                                                             |
|-----------------------------|---------|------------------------------------------------------------------|
| Windows MSI installer (x64) | 7.2.0   | 472a6ff1e9b1caf4687ef3ce62aaabab99d5b118714995a975ac84b564164d6a |
| Windows MSI installer (x86) | 7.2.0   | 3b818001ffb5e4f26ea890e0102418b9f32abedb9f2dc40fff01dce0dd3ad668 |
| Mac OS X High Sierra        | 7.2.0   | 15bb4a83e53aded9367eeea177d5d2da10e85871f3e83d9b99d8d6f56070f73b |
| OS X installer              | 7.2.0   | a3ba0788fa7d69e7738e18f0c5351a831e0a2672dc2591db8e67455d94469373 |
| Slackware Tarball (x64)     | 7.2.0   | 10ac669eb7caa51f6768f83f8ab8e777025c79fcaf9a97c428e3e91ad5a9c611 |
| Slackware Tarball (x86)     | 7.2.0   | b0cd96de3bd30aaa016037643296d32244c01efbdd63ccc67b8c40bda31f7bab |
| DEB Linux (x86)             | 7.2.0   | 8f7c10ea12c36ba0218456f98702aaff8bb7a4fc817a72e9836622a7690bd34c |
| DEB Linux (x64)             | 7.2.0   | 9c93f4a2ea4d2c0ca38af4ae61bea56bd7e21ebd235b47fcea5704646cb21e80 |
| RPM Linux (x64)             | 7.2.0   | ab5f43f298da3424129c714d4df16b4ee7e55bd855879bce3da2965e1fdcd7f0 |
| RPM Linux (x86)             | 7.2.0   | 23dadf97dd41f9ed095d9845a7aed49bd78ec7e493ec04a002f56fa1c43118cf |