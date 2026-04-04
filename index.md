---
layout: default
title: Beni On The Web
---

Welcome to *Beni On The Web*! This is a place where I, Beni, want to publish writings on various topics of personal relevance.

## All pages

<ul>
{% for page in site.pages %}
<li>
  <a href="{{ page.url }}">{{ page.title }}</a>
</li>
{% endfor %}
</ul>

## All lists

<ul>
{% for page in site.lists %}
<li>
  <a href="{{ page.url }}">{{ page.title }}</a>
</li>
{% endfor %}
</ul>
