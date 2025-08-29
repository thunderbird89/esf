---
layout: default
title: Stories
---
<ul>
{% assign story_pages = site.pages | where: "type", "story" | sort: "timeline" %}
{% for p in story_pages %}
  {% if p.timeline and p.title %}
    <li>{{ p.timeline }}: <a href="{{ p.url | relative_url }}">{{ p.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
