---
layout: default
title: Codex
---

<ul>
{% assign codex_pages = site.pages | where: "type", "codex" | sort: "title" %}
{% for page in codex_pages %}
  {% if page.title %}
    <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
