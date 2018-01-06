---
layout: archive
title: "信息可视化作品集"
date: 2017-12-30T11:40:45-04:00
categories：infovis
excerpt: "可视化图表啥的"
tags: []
image: 
  feature: tableau.jpg
  teaser:
---



<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div> 