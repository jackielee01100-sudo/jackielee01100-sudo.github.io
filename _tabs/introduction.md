---
layout: page
title: introduction
icon: fas fa-tasks
order: 3
---

<div id="archives" class="pl-xl-3">
  {% for post in site.categories["Progress"] %}
    {% capture cur_year %}{{ post.date | date: "%Y" }}{% endcapture %}
    {% if cur_year != last_year %}
      <div class="year lead">{{ cur_year }}</div>
      {% assign last_year = cur_year %}
    {% endif %}
    <ul class="list-unstyled">
      <li>
        <span class="date day">{{ post.date | date: "%d" }}</span>
        <span class="date month">{{ post.date | date: "%b" }}</span>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </li>
    </ul>
  {% endfor %}
</div>
