---
title: {{ replace .Name "-" " " | title  }} 
slug: {{ .Name | urlize }}
kind: post
type: releases
layout: single

date: {{ dateFormat "Mon, 02 Jan 2006 15:04:05 MST" .Date }}
publishDate: {{ dateFormat "Mon, 02 Jan 2006 15:04:05 MST" .Date }}
lastmod: {{ dateFormat "Mon, 02 Jan 2006 15:04:05 MST" .Date }}
draft: true
author: 
# adamt
# diegom 
# katt

releases: backup
products:  
# One
# Groups
# One & Groups
version: 
description: 
keywords: 
# meta keywords for SEO 
---



<!-- link -->
{{< link
    href="" >}}
    Link Text
{{< /link >}}

<br> 

<!-- link target-blank -->
{{< target-blank
    href="" >}}
    Link Text
{{< /target-blank >}}


<!-- img/figure -->
{{< img 
    src="" 
    type="" 
    alt="" 
    caption="" >}} 

<br>

<!-- hash table -->
{{< table 
    version=""

    platform-1="" 
    hash-1="" 
    
    platform-2="" 
    hash-2=""  

    platform-3="" 
    hash-3=""  

    platform-4="" 
    hash-4="" 

    platform-5="" 
    hash-5=""  

    platform-6="" 
    hash-6=""  

    platform-7="" 
    hash-7=""  

    platform-8="" 
    hash-8=""  

    platform-9="" 
    hash-9=""  

    platform-10="" 
    hash-10=""  
    >}} 