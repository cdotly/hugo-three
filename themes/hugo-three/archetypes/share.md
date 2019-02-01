---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author: ""
slug: 
description: 
keywords: 
product: 
- share 
weight: 1
menu: 
  main:
  - identifier: about
    name: about hugo
    pre: <i class='fa fa-heart'></i>
    url: /about/
    weight: -110
  - name: getting started
    post: <span class='alert'>New!</span>
    pre: <i class='fa fa-road'></i>
    url: /getting-started/
    weight: -100
---