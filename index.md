---
layout: default
title: Home
---

# Recipe Index

<ul>
  {% for text in site.texts %}
    <li>
      <a href="{{ site.baseurl }}{{ text.url }}">{{ text.title }}</a>
    </li>
  {% endfor %}
</ul>
