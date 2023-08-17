---
layout: page
title: Archive
permalink: /archive.html
---

Hier een lijstje met alle artikelen.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%-d %B %Y" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
