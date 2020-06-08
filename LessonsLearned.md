---
layout: page
permalink: /categories/Lessons
title: Lessons Learned
---

{% for post in site.categories.Lessons Learned %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}