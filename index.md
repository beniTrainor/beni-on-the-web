---
layout: default
title: Beni On The Web
---

Welcome! 👋🏻 This site contains information about me, **Beni Trainor**, in the form of pages and lists. You can read more about me or this site in separate pages.

- [About me]()
- [About this site]()




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



## Comments, suggestions and corrections

Want to comment, suggest or correct something? You can do so by sending an email or opening a pull request.
