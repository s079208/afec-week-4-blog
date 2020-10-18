---
title: Blog
layout: 'layouts/page.html'
---

Zoals eerder vermeld is deze blog overgenomen van de site [Medium](medium.com "Medium")  
### Recente posts

<ul class="blog">
{%- for post in collections.post | reverse -%}
  <li>
    <a href="{{ post.url | url }}">{{ post.data.title }}</a>
 </li>
{%- endfor -%}
</ul>
