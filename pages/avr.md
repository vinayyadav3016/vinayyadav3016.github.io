---
layout: page
title : AVR
permalink: /avr
---
<div id="archives">
    {% for post in site.categories.Avr %}
        <article class="archive-item">
            <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
        </article>
    {% endfor %}
</div>
