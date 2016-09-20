---
layout: post
title: Highlands
categories: land
tags: highlands
---

Rocks and sprawl. 

Little lush mountain streams in steep valleys of sugar maples. Open grassy oak forests higher up. Lots of exposed bedrock, with red cedar trees.


<ul>
  {% for post in site.categories.highlands %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
