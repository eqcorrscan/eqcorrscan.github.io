---
layout: page
title: Timeline
tagline: What next?
description: What next?
permalink: /timeline/
group: navigation
---
{% include JB/setup %}

EQcorrscan is a young project, and we have yet to integrate a great many things,
however this page serves to outline what we plan to integrate, with a rough
release timeline.  All of these dates are very rough and depend on how much
everyone contributes.  Any comments are welcome
on the issue [tracker](https://github.com/calum-chamberlain/EQcorrscan/issues/3).

## Release 0.1.3 - September-ish 2016
* Include subspace detection routine;
* Include pick-correction by cross-correlation routines;

## Release 0.2.0 - In the future
* Do not constrain matched-filter to day-long data;
  * Requires testing of stability of threshold levels with shorter data arrays;
* Include real-time ability using obspy's seedlink client;
* GUIs for template generation.

<!-- {% include JB/comments %} -->
