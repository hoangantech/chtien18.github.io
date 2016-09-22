---
layout: page
show_meta: false
title: "Hướng dẫn đặt hàng"
subheadline: ""
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/huongdan/"
---
<ul>
    {% for post in site.categories.huongdan %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>