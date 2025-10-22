---
title: 'MAT 4111A: Putnam Preparation'
layout: layouts/mat4111AF25.njk
---

<h1 style="margin:0;">MAT 4111A</h1>
<h4 style="margin:0;">Putnam Preparation</h4>

<a href="/F25/MAT4111A/proof_techniques/"><h2>Proof techniques</h2></a>
<ul>
  {% for post in collections.proof_techniques %}
    <li>
      <a href="{{ post.url }}">{{ post.data.title }}</a>{% if post.data.week %} (week {{post.data.week}}){% endif %}
    </li>
  {% endfor %}
</ul>

<a href="/F25/MAT4111A/student-selected/"><h2>Student selections</h2></a>
