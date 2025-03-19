---
layout: default
title: Directory Listing
---

<h1>Files</h1>
<ul>
  {% for file in site.static_files %}
    {% unless site.exclude_files contains file.name %}
      <li><a href="{{ file.path }}">{{ file.name }}</a></li>
    {% endunless %}
  {% endfor %}
</ul>
