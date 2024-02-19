---
title: Reference Guide for Adding Pages to this Website
author: Adam Dennett
date: '2023-08-22'
slug: []
categories:
  - Paper
tags: [Guide]
subtitle: 'This is hard'
excerpt: 'Just figuring out'
draft: yes
series: ~
layout: single
---

## Important Folders

As far as I can tell, there are some folders that are vital for the website to work and others that might be surplus. Vital ones include:

-   R

-   assets

-   content

-   data

-   layouts

-   resources

-   static

surplus ones *probably* include:

-   archetypes

-   public

-   themes

## Important files in the root

-   config.toml - this seems to control virtually everything (but it could be a .yaml)

-   netlify.toml - this is for deployment

-   gitignore - for all the usual reasons.

## Showing/Hiding Content in Folders

Thanks to Andy Mac for this little bit of golden knowledge - in order to show/hide content within any particular folder, add/remove an underscore in the index.md file. E.g. _index.md will not show the content of that file, where as index.md will. 
