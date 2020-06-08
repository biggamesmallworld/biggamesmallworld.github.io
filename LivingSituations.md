---
layout: page
permalink: /categories/Intros
title: Living Situations
---

{% for post in site.categories.Living Situations %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}