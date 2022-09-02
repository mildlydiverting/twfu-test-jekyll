---
title: Blog
permalink: "/blog/"
layout: page
header: Blog
description: Updates about digital sustainability, product management and running
  ethical digital projects in third sector.
---

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  🗓 {{ post.date | date_to_string }}</p>
{% endfor %}