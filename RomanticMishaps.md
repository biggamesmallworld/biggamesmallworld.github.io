---
layout: page
permalink: /categories/Romantic
title: Romantic Mishaps
---

{% for post in site.categories.Romantic %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}