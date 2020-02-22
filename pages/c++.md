---
layout: page
title : C++
permalink: /categories/c++
---
<div id="archives">
    {% for post in site.categories.['C++'] %}
        {% if post.type == "tutorial" %}
            <article class="archive-item">
                <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
            </article>
        {% endif %}
    {% endfor %}
    {% for post in site.categories.['C++'] %}
        {% if post.type == "blog" %}
            <article class="archive-item">
                <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
            </article>
        {% endif %}
    {% endfor %}
</div>
