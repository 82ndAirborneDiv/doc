---
layout: page
title: Docsy Jekylll Theme
permalink: /doc/
---

## Table of Contents





Welcome to the {{ site.title }} site! 

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
