---
title: 'Work'
layout: 'layouts/page.html'
---

Deze vakantie heb ik een website gemaakt [Horizonta](https://www.horizonta.be/ "Medium") , ik heb hieraan op zelfstandige basis aan gewerkt als student.

### Werken

{% for item in collections.featuredWork %}
  <a href="{{ item.url }}">
    <img src="{{ item.data.image }}" alt="{{ item.data.summary }}"/>
  </a>
{% endfor %}
