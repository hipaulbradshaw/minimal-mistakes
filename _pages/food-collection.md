---
layout: collection
title: "Food"
collection: food
permalink: /food/
author_profile: false
entries_layout: grid
toc: true
---

# with iteration archive-single.html and entries_layout: grid

Sample document listing for the collection `_food`.

<h2>Food</h2>
{% for post in site.food %}
  {% include archive-single.html %}
{% endfor %}