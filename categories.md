---
layout: page
permalink: /categories/
title: Categories
---

<div class="container">
    <!--Row with three equal columns-->
    <div class="row">
        {% for category in site.categories %}
        <a class="col-lg-4">
            <div class="archive-group">
                {% capture category_name %}{{ category | first }}{% endcapture %}
                <div id="#{{ category_name | slugize }}"></div>
                <h3 class="category-head">{{ category_name }}</h3>
                <a name="{{ category_name | slugize }}"></a>
            </div>
        </a>
        {% endfor %}
    </div>
</div>
</div>