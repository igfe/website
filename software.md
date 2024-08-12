---
title: software
---
<h1>Software</h1>

<ul>
  {% for f in site.software %}
    <li>
      <h2><a href="{{ f.url }}">{{ f.name }}</a></h2>
      <p>{{ f.excerpt | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
