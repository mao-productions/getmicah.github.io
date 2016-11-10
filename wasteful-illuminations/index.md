---
layout: about
published: true
---

<div class="works">
  <h1>Wasteful Illuminations, 2008-2016</h1>
  <ul>
    {% for post in site.categories.wasteful-illuminations %}
    {% if post.url %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
</div>
