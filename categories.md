---
layout: page
permalink: /categories/
title: Categories
---


<div id="archives row">
{% for category in site.categories %}
    <a href="{{ site.baseurl }}/{{category_name}}">
        <div class="archive-group col-md-4">
            {% capture category_name %}{{ category | first }}{% endcapture %}
            <div id="#{{ category_name | slugize }}"></div>
            <h3 class="category-head">{{ category_name }}</h3>
            <a name="{{ category_name | slugize }}"></a>
        </div>
    </a>
{% endfor %}
</div>