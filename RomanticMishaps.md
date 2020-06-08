---
layout: page
permalink: /categories/Romantic-Mishaps
title: Romantic Mishaps
---

{% for post in site.categories.Romantic Mishaps %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}