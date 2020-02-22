---
layout: page
title : Linux
permalink: /categories/linux
---
<div id="archives">
    {% for post in site.categories.Linux %}
        {% if post.type == "tutorial" %}
            <article class="archive-item">
                <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
            </article>
        {% endif %}
    {% endfor %}
    {% for post in site.categories.Linux %}
        {% if post.type == "blog" %}
            <article class="archive-item">
                <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
            </article>
        {% endif %}
    {% endfor %}
</div>
