---
layout: layouts/mat3100WF25.njk
---

# MAT 3100W (Fall 2025)

<a href="/mat3100WF25/syllabus/">Syllabus</a>

## Assignments list
<ul>
{% for post in collections.all %}
  {% if post.data.blog == "MAT3100WF25" %}
    <li><a href="{{ post.url }}">{{ post.data.title }}</a> </li>
  {% endif %}
{% endfor %}
</ul>
