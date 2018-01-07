---
layout: archive
title : "信息可视化"
date: 2018-01-04T00:03:45-04:00
modified:
excerpt: "期末可视化作品展示"
tags: []

---
![仪表板 1.png](https://i.loli.net/2018/01/07/5a51fa0ca9867.png)

其他作品
<div class="tiles">
{% for post in site.categories.message %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 message 的列出來-->
