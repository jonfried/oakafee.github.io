---
layout: post
title: Urban Core
author: Jesse Fried
categories:
  - land-use
tags: urban-core
---

As I glance across the swirling Hudson brine at the steep banked edges of Hudson and Bergen counties, studded, like a crown, with brick high-rises and fringed along the water's edge with piers of cheap condos, I feel an inexpressible longing. Why not discard the empty mainstream life I have adoped, to wander through the city blocks, the suburban streets, the office parks, the grimy industrial zones of my state, seeking wisdom? Then, inevitably, I sigh and return to my voluntary exile in Corporate America. 

<div class="table-container">
  <table class="index">
    {% tablerow page in site.categories.urban-core cols:3 %}
      {% if page.url %}
          <a href="{{ page.url }}">{{ page.title }}</a>
      {% endif %}
    {% endtablerow %}
  </table>
</div>
