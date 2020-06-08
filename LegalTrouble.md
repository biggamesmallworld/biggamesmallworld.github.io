---
layout: page
permalink: /categories/Intros
title: Legal Trouble
---

{% for post in site.categories.Legal Trouble %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}