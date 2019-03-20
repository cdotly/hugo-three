---
title: Groups 7.2.1
date: 2019-02-05T16:30:08-08:00
draft: true
author: adamt
kind: post
type: releases
layout: single
slug: groups-7.2.1
description: 
keywords: 
products: groups
---

This release is only for the Linux .rpm and Mac versions of SpiderOak One and SpiderOak Groups. 7.2.0 RPMs were missing their GPG signature due to a change in our build tools. This release fixes the signing error. The Mac versions had an incorrectCFBundleShortVersionString value which this version corrects. We want to thank all of the users who alerted us to these issues and helped us with troubleshooting.

All other platforms, including Windows and non-RPM based Linux distros, should continue to use version 7.2.0 as the current version.

## Bug Fixes

- Resolved GPG signing issue on RPM
- Fixed wrong CFBundleShortVersionString value on macOS

## Installer Hashes (SHA256):

| PLATFORM             | VERSION | HASH                                                             |
|----------------------|---------|------------------------------------------------------------------|
| Mac OS X High Sierra | 7.2.1   | 63338def886c7274ec3f11417a20837b2d3e719386d95d0ea68587b75aff6245 |
| OS X installer       | 7.2.1   | 1d14e40871bfdcf8fbea77afec06cceac49aceb773dd8749e00ef5710eeedaf8 |
| RPM Linux (x64)      | 7.2.1   | 4d5fac5bbb77e80374adda48f9c1a998e37a76b91a06d2c83bd60d8b36d7da37 |
| RPM Linux (x86)      | 7.2.1   | 72a8a6e658c5957e11802f9fd187c462851a3c3361778893e6edc2f7e48c2fc5 |