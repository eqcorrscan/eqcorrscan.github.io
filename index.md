---
layout: page
title: Welcome to EQcorrscan
tagline: Matched-filter earthquake detection in Python
---
{% include JB/setup %}

[![Here is supposed to be the EQcorrscan logo]({{ site.production_url }}/assets/EQcorrscan_logo.png)](http://eqcorrscan.readthedocs.org/en/latest)


[![Join the chat at https://gitter.im/calum-chamberlain/EQcorrscan](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/calum-chamberlain/EQcorrscan?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![TravisCIStatus](https://travis-ci.org/calum-chamberlain/EQcorrscan.svg?branch=master)](https://travis-ci.org/calum-chamberlain/EQcorrscan)
[![Build status](https://ci.appveyor.com/api/projects/status/69bpa53loaq473w7?svg=true)](https://ci.appveyor.com/project/calum-chamberlain/eqcorrscan)
[![Coverage Status](https://coveralls.io/repos/github/calum-chamberlain/EQcorrscan/badge.svg?branch=develop)](https://coveralls.io/github/calum-chamberlain/EQcorrscan?branch=develop)
[![DOI](https://zenodo.org/badge/18852/calum-chamberlain/EQcorrscan.svg)](https://zenodo.org/badge/latestdoi/18852/calum-chamberlain/EQcorrscan)
[![DocumentationStatus](http://readthedocs.org/projects/eqcorrscan/badge/?version=latest)](http://eqcorrscan.readthedocs.org/en/latest/?badge=latest)


These pages make up the general documentation of the EQcorrscan project,
the full API can be found
[here](http://eqcorrscan.readthedocs.org/en/latest/?badge=latest).

This project is an open source, Python project for the detection and analysis
of repeating and near-repeating earthquakes.  To do this it requires either
data from a single, or a network of, seimographs.

The codes are hosted on [github](https://github.com/calum-chamberlain/EQcorrscan), with the
latest release also available on
[pypi](https://pypi.python.org/pypi/EQcorrscan).

This project is under development, although the core routines are
relatively stable.

You can find more details about the project on the [About](about) page,
and details on how to install and update on the
[Installation](installation) page.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
