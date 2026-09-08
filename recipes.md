---
layout: default
title: Recipes
---
<h1>All Recipes</h1>
<ul>
{% for recipe in site.recipes %}
  <li><a href="{{ recipe.url | relative_url }}">{{ recipe.title }}</a> — {{ recipe.category }}</li>
{% endfor %}
</ul>
