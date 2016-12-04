---
layout: about
published: true
---
<div class="works">
    <h2>Publications</h2>

    <ul>
      {% for item in site.data.publications %}
      <li>
          <a href="{{ item.url }}">{{ item.title }}</a>
      </li>
      {% endfor %}
    </ul>
</div>
