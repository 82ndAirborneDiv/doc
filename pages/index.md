---
layout: page
title: Docsy Jekyll Theme
permalink: /
---

# Welcome to Docsy Jekyll

This is a starter template for a docsy jekyll theme.

![assets/img/docsy-jekyll.png](assets/img/docsy-jekyll.png)

## Purpose

GitHub pages uses Jekyll natively, so when I make documentation, I typically
look for Jekyll templates. Why? Using Jekyll means that I can use markdown,
and allow for users to easily contribute, and build automatically just by
way of pushing to a master branch (or general GitHub pages).
I found Docsy, a beautiful Hugo template, but it requires hugo with GoLang
which doesn't render natively on GitHub pages. For this reason, I've spent
some time creating a custom Jekyll template that is (almost) as beautiful,
and includes all the features that I might want.

Welcome to the {{ site.title }} Documentation pages! Here you can quickly jump to a 
particular page.

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
