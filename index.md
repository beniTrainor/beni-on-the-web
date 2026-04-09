---
layout: default
title: Beni On The Web
---

Welcome to this site! Have a look around.

I've written pages and lists of things that I find personally relevant.

## All pages

<ul>
{% for page in site.pages %}
<li>
  <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
</li>
{% endfor %}
</ul>

## All lists

<ul>
{% for page in site.lists %}
<li>
  <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
</li>
{% endfor %}
</ul>
