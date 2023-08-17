---
layout: page
title: Misc
permalink: /misc/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: date_format }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
