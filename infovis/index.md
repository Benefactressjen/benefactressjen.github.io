---
layout: archive
title: "信息可视化笔记"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "可视化"
tags: []
image: 
  feature: tableau.jpg
  teaser:
---



<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出來-->