---
layout: default
title: 我的书签
author: Frank
---

{% assign bookmark = site.data.bookmark["bookmark"] %}
{% assign category = site.data.bookmark["category"] %}

## {{page.title}}
* * *

<blockquote>
    <p>一盏灯， 一片昏黄；一书签， 一杯淡茶。 守着那一份淡定， 品读属于自己的寂寞。 保持淡定， 才能欣赏到最美丽的风景！ 保持淡定， 人生从此不再寂寞。</p>
    <footer>Someone famous in
        <cite title="Source Title">书摘</cite>
    </footer>
</blockquote>


{% for c in category %}
<h2>
    {% assign title = c %} {{title}}
</h2>
<h4>
    {% for b in bookmark[ title ] %}
    ◆<a href="{{ b.url }} " target="_blank">{{ b.title }}</a>&nbsp;&nbsp;
    {% endfor %}
</h4>
{% endfor %}