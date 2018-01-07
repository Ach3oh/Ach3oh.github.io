---
layout: archive
title: "信息可视化的心得"
date: 2018-01-04T19:00:45-04:00
modified:
excerpt: 随笔( •_•)
tags: []
image: 
  feature: note.jpg
  teaser: note.jpg
---


<div class="tiles">
{% for post in site.categories.message play %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 message play 的列出来-->
