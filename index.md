---
layout: default
title: "Happy Jekylling!"
---

## You're ready to go!

Start developing your Jekyll website.

---
layout: home
title: "Sam's Kitchen"
---

**A personal recipe collection**

<h1>Recipe Index</h1>

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
