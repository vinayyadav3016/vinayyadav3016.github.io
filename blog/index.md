---
layout: page
title: Blog
date: 2014-29-12
---
<ul>
    {% for post in site.posts %}
        {% if post.type == "blog" %}
            <li><span>{{ post.date | date_to_strin}}</span>
                <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>
